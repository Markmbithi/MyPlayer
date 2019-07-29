# MyPlayer
This is a very simple app that streams a live video to a mobile app. I am using the bambuser.com SDK. This particular project is for Android and can run on any device starting from Android 6 all the way up to Android 9. 

Fork this folder into your PC, open the project with Android Studio and setup the necessary libraries and AVD as required.

# Setup steps;
1. Clone this folder to your desktop machine.
2. Create a bambuser.com account. We will use this account to extract our ApplicationId and API Key.
3. Download this Android SDK that is usefull to make this application work. https://backend.irisplatform.io/api/downloads/231?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJleHAiOjE1NjM3NTk5NTEsImRvd25sb2FkZXIiOiJtYXJrbWJpbGFAZ21haWwuY29tIn0.0EpyUSp5j6c3N00oWjdZtVGBgrV-UCh9-sDokMyh8hI
4. Replace the APPLICATION_ID and API_KEY values in LiveStream.java to reflect your obtains keys after you have logged in to to your bambuser account. You will create and Application ID and API Key once you have created and logged in to your bambuser account;
5. You will also need to download and install the packages okhttp3 and libbambuser-0.9.18 userful for creating the software and the various applications useful for making app with videos and streaming.
