# Android AI ChatBot

Built using Android Studio and Java , the app integrates the ChatGPT API to provide operational resources for chatbots. 
Users can chat in real time with the chatbot and get answers to their questions.

# Libraries Used
* OkHttp for handling HTTP requests and responses
(You can also use java.net.http package if you are using JAVA 17 or higher)
* Gson for parsing JSON data

Add these dependencies in your build.gradle
```
dependencies {
implementation 'com.squareup.okhttp3:okhttp:4.12.0'
implementation group: 'com.google.code.gson', name: 'gson', version: '2.10.1' 
}  
```

# Usage

* Add your ChatGPT API key in the [MainActivity.java](https://github.com/gangulwar/Android-ChatBot/blob/main/app/src/main/java/com/gangulwar/layouttest/MainActivity.java#L85) file.

# Important Points

* Try to use higher SDK version (33 or higher) of Android.
