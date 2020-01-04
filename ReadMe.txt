-------------------------------------
CONFIGURATION INSTRUCTIONS
-------------------------------------

GOOGLE CLOUD TRANSLATION API V2
-------------------------------------
Please note this content app utilises Google ‘Cloud Translation API’ V2. You can find more information regarding the API here.
https://www.googleapis.com/language/translate/v2


CREATE AN API KEY
-------------------------------------
You are required to create your own API Key to use within this content app. You can create an API Key for Google Cloud Translation here.
https://console.cloud.google.com/


ADD THE API KEY TO YOUR WEB.CONFIG
-------------------------------------
Once you have created an API Key you are required to add this to your web.config file within the <appSettings> section.
EG.

<appSettings>
  <add key="GoogleTranslateApiKey" value="YOUR API KEY TO GO HERE" />
</appSettings> 


IMPORTANT! WHAT IS TEST MODE?
-------------------------------------
For the purpose of evaluating this content app I have added my own Cloud Translation API Key. This is encrypted and compiled within a dll so you wont be able to see this in your web.config. 

If you don’t add an API key in your <appSettings> then this content app will assume you are using it for evaluation purposes. You will still have full functionality but there will be a red message at the top of the app reminding you that you’re still in ‘TestMode’. Once you add your API Key into your <appSettings> file then this message will disappear.

I’m happy for everyone to use my API Key for evaluation purposes but please do not abuse this to the point it will start costing me money. I think there’s quite a lot of free requests which should be enough for everyone to successfully review the app. Once you have reviewed the app then please try and create your own API Key as soon as possible.

If you need help with this, please don’t hesitate to drop me an email at.
david@recsitedesign.com


PLEASE SHOW YOUR APPRECIATION
-------------------------------------
If you like this content app then please feel free to show your appreciation by voting and leaving comments here.
https://our.umbraco.com/packages/backoffice-extensions/content-translator-content-app/



WHERE TO REPORT ISSUES
-------------------------------------
You can either drop me an email at david@recsitedesign.com or you can log a issue at the following URL.
https://github.com/DavidArmitage/Umbraco8_ContentTranslator_ContentApp/issues


LATEST VERSION
-------------------------------------
The latest version of the app can be found here
https://github.com/DavidArmitage/Umbraco8_ContentTranslator_ContentApp

