
 **Before you run your application, you need a Google Maps API key.**
 
 To get one, follow this link, follow the directions and press "Create" at the end:
 
    https://console.developers.google.com/flows/enableapi?apiid=maps_android_backend&keyType=CLIENT_SIDE_ANDROID&r={SHA-1}%3Bcom.lelasoft.googlemapv2test

    You can also add your credentials to an existing key, using these values:


**SHA-1 certificate fingerprint:**
  In Android Studio you can find all your app signing information without any console command:

  > Open your project
    
 1. Click on Gradle from right side panel
    
 2. In Gradle projects panel open folders: Your Project -> Tasks-> Android
    
 3. Run signingReport task (double click) and you will see the result in Gradle console (keystore paths,SHA1,MD5 and so on).

    Alternatively, follow the directions here:
    https://developers.google.com/maps/documentation/android/start#get-key
    
    
    
**Implemented how to ask user for enable GeoLocation dialog.**
