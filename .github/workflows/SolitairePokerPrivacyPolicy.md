## Solitaire Poker: Privacy policy

Welcome to the Solitaire Poker app for Android!

This is the privacy policy for the app.

### Data collected by the app

I hereby state, to the best of my knowledge and belief, that I have not programmed this app to collect any personally identifiable information. All data (game settings, points, badges achieved) created by you (the user) is stored locally in your device only, and can be simply erased by clearing the app's data or uninstalling it. No analytics software is present in the app either.

### Explanation of permissions requested in the app

I set a custorm `AndroidManifest.xml` file in unity and removed the following permissions:<br>
  \<uses-permission android:name="android.permission.FOREGROUND_SERVICE" tools:node="remove" /><br>
  \<uses-permission android:name="android.permission.FOREGROUND_SERVICE_DATA_SYNC" tools:node="remove" /><br>
  \<uses-permission android:name="android.permission.POST_NOTIFICATIONS" tools:node="remove" /><br>
  \<uses-permission android:name="android.permission.SCHEDULE_EXACT_ALARM" tools:node="remove" /><br>
  \<uses-permission android:name="android.permission.RECEIVE_BOOT_COMPLETED" tools:node="remove" /><br>
  \<uses-permission android:name="${applicationId}.DYNAMIC_RECEIVER_NOT_EXPORTED_PERMISSION" tools:node="remove" /><br>
  
So the app requests no permissions at all.
Please notify me if the app requests any permission which is added by unity or gradle, so I can remove it.

If you find any security vulnerability that has been inadvertently caused by me, or have any question regarding how the app protectes your privacy, please send me an email, and I will surely try to fix it/help you.

Yours sincerely,  
Péter Dunaszegi.  
dunapeti@gmail.com
