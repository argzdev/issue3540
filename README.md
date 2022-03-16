# issue3540
### Prerequisite
- Add google-services.json
### Summary
- Card type In-App Message layout disorder when rotating from portrait to landscape on Android
### Steps to reproduce issue
- Run the app, retrieve installation ID for testing via logs. Type "I/FIAM.Headless: Starting InAppMessaging runtime with Installation ID " to find ID.
- Close app
- In Firebase Messaging dashboard, create an inappmessaging campaign
- Add a title, a very long body, and image
- Click `Test on Device` and insert previously copied ID
- Open app, change orientation of the app.
