# This task is about connecting En_bot to telegram.

To do this, at first you must run:\

$pip install rasa\
$pip install pyngrok

(I installed them befor runing jupyter)

this is like creating En_bot , for connecting bot to telegram we should change "credentials.yml" file and get our telegram bot information in that like this:

telegram:\
  access_token: "490161424:AAGlRxinBRtKGb21_rlOEMtDFZMXBl6EC0o"\
  verify: "your_bot"\
  webhook_url: "https://your_url.com/webhooks/telegram/webhook"
  
 We get our bot token and verify(bot name) from " @Bot Father" in telegram, Next For geting webhook_url we run "!ngrok http 5005" after runing this part we can get the 2th forwarding URL as webhook_url.
 For example:
 
 ![image](https://user-images.githubusercontent.com/113304112/202919185-bee59d7f-4d1b-462e-a49c-a097a1dcfcc8.png)

 
 we can get " https://3ba5-5-113-148-223.ngrok.io " as webhook_url.
 
