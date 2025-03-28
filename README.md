# Tagline

xSynth Connected iDrive, is an automobile/console mounted, embodied Ai/3d humanoid/conversational friend/helpful assistant utilizing IBM's Ai infrastructure enabling functions from friendly conversation to xSynth being able to tell driver of the nearest hospital, or getting xSynth to remind the driver of the closest oil filter depot. (Works with default car console)

Read more here: https://github.com/iCosmosNeuroverse/XSYNTH_CONNECTED_IDRIVE/blob/main/data/PricingPlan.md



![image](https://github.com/iCosmosNeuroverse/XSYNTH_CONNECTED_IDRIVE/blob/main/data/xSynthIcon.jpg)

# xSynth by Cosmos Bennett @iCosmosNeuroverse

![image](https://github.com/iCosmosNeuroverse/XSYNTH_CONNECTED_IDRIVE/blob/main/data/XSYNTH_CONNECTED_DRIVE_LQ_GIF_III.gif)


# World's 1st 3d automobile Ai friend and assistant for Honda Civic 10th generation 

![image](https://github.com/iCosmosNeuroverse/XSYNTH_CONNECTED_IDRIVE/blob/main/data/xSynth_ProjectRun_Civic.jpg)

# Youtube Demo:
https://youtu.be/pxgLJSd3_-s


# Tech Stack
Unity3d, C# including custom shader adjustments to enable compatibility/rendering on Honda Civic.
Without these adjustments, the Honda Civic renders a blank screen.


# Goals (Long term)
* A friendly conversational ai agent doubling as an assistant and interactive automobile manager, embodied in [cryptosynth aeon](https://github.com/iCosmosNeuroverse/Cryptosynth) being form.
* Instead of stopping to type in directions in Waze for eg, or voicing commands to car play, one could speak with my 3d being xSynth in natural language to get useful data.
* This could occur in self driving as well. Instead of typing in things to do for eg 'cruise' control, one would instruct xSynth to do this by natural language.
* ...
* In particular, xSynth is as a “low energy consumption” attempt to deliver an Ai friend in car, perhaps while parked.
* ...




# One known bug

The Ai sucessfully detects my voice/questions and optional text inputs on both Civic car screen and PC Desktop, but fails to move her mouth on the Civic car screen.

She moves her mouth according to IBM Assistant's lipsync tech on [Desktop LQ Unity version](https://github.com/iCosmosNeuroverse/XSYNTH_CONNECTED_IDRIVE/#replicate-xsynth-outside-of-the-2017-civic-10th-gen-and-on-your-desktop) successfully.

This Civic lack of mouth movement could be either due to the Civic's low 512 mb ram limit or lack of compatibility with the Civic for IBM Ai Assistant.




# Download and run xSynth in your Honda Civic 10th gen
 

1.	Ensure you have Android version 4 eg, 4.2.2 in your Honda Civic/Car display console.
2.	Turn on your Wifi on your Civic/Car display.
3.	Root/hack your Honda Civic display, using Honda Hack. (25 usd) Allows installation of custom apps, like my xSynth app, or File Manager, or Youtube to your Civic, and other cool things like putting your reverse camera on while moving forward. (This can be done directly from your car, from the “search” icon in app list, by visiting autohack.org. You can buy the 25 usd key on desktop first, on the same site, then use the site in car to root your car’s display)
4.	In your car/Civic, after you rooted it, install Play Store, and login into your google account, or create one if desired.
5.	In your car/Civic, after you rooted it, install a File Manager, (I suggest File Manager+). (This should be fine, as I find that my civic had about 2gb memory free internal, and more than 6 gb on sd card. Sadly ram is low around 512 mb, but my ai runs quickly regardless)
6.	On your desktop or laptop, download my [xSynth app](https://drive.google.com/file/d/1sECZtaJS7osv5DrjIShSb7RMxy02Gc_P/view?usp=sharing) (apk file ~45mb) and put it on a flash drive.
7.	On your desktop or laptop, put the flash drive into the usb port. (I used the one under the cup holder in center)
8.	In your car/Civic, load your File Manager app, and navigate to “USB” icon, and find my app called xSynth, with the icon below:

a. ![image](https://github.com/iCosmosNeuroverse/XSYNTH_CONNECTED_IDRIVE/blob/main/data/xSynthIcon.jpg)	 

9.	Next, in your car/Civic tap the xSynth icon, and install, and ignore hardware limit warning with continue. Ignore Google Play store’s limits for unknown apps as well, similar to Honda Hack. Wait for install (about 40 seconds)
* DO NOT TRY TO INSTALL FROM HONDA HACK, IF YOUR FLASH DRIVE HAS LOTS OF STUFF LIKE LARGE MOVIES! IT WILL TAKE A LONG TIME TO FINALLY BEGIN TO INSTALL XSYNTH OR ANY APP YOU TRY TO INSTALL. IF YOU HAVE LOTS OF FILES IN THE GIGABYTE RANGE OR SO ON YOUR FLASH DRIVE ALONG WITH MY APK/APP, USE THE FILEMANAGER I SUGGESTED ABOVE, AND NAVIGATE DIRECTLY TO MY APK INSTALLER. IF YOU HAVE ONLY THE APK ON THE FLASH DRIVE, THEN INSTALLING THROUGH HONDA HACK IS FINE AND QUICK.
11.	Next, in your car/Civic, in File Manager, navigate to “Apps” icon, and scroll down if needed to find my installed xSynth app (It looks the same like the icon from (8)). Tap/Hold, and open to run the app. 
12.	Talk freely to xSynth (by Voice or by text) about BOV mod safety inquiries, parts inquiries, honda history, meaning of life, or about xSynth itself. Say hello or good bye or other similar expressions. xSynth uses Ai to detect your voice.
13.	An update may fix mouth animation, and make the app useful by integration actual honda location data like dealership data.
14. BE SURE TO CLOSE XSYNTH WHEN NOT USING IT, IF YOU HAD STARTED IT. (File Manager > Apps > xSynth > Force Stop or Honda Hack > Uninstall apps > xSynth > Force Stop (not uninstall). Although it has about 8 gb of free space, the civic xgen has only roughly 512 mb of ram.




# Replicate xSynth outside of the 2017 Civic 10th gen, and on your Desktop

See [my manuscript, page 4](https://github.com/iCosmosNeuroverse/XSYNTH_CONNECTED_IDRIVE/blob/main/data/xSynth_Manuscript.pdf).

Download desktop LQ android build (Warning: 342 mb rar file extracts to 1.08 gb): https://drive.google.com/file/d/18hIA206_M7b15lhL66kfXyyWpi5uitl_/view?usp=sharing


# Powered by IBM Cloud Ai Assistant

•	xSynth is powered by IBM Watson assistant. xSynth uses an IBM skill file, made by Cosmos Bennett concerning Honda Civics and casual topics.

•[The skill/technique file](https://github.com/iCosmosNeuroverse/XSYNTH_CONNECTED_IDRIVE/blob/main/data/xSynth_CivicTenthGeneration_Technique_byCosmosBennett.json) consists of samples of the types of questions/statements that the xSynth ai is expected to be able to process. IBM Watson then uses the aforesaid samples to anticipate a variety of inputs related to the samples, using Machine Learning/Ai.

•	xSynth [builds on Scott Hwang’s IBM Watson unity3d template for Desktop](https://github.com/snhwang/Unity-Watson-STT-Assistant-TTS), however using custom IBM skill file discussed prior. Note that you have to use [my version of this template](https://drive.google.com/file/d/18hIA206_M7b15lhL66kfXyyWpi5uitl_/view?usp=sharing), because I downgraded Scott’s Desktop version in 2 ways, first to unity3d 2019.2 instead of 2019.4, to comply with my Honda Civic’s android level as well as shader/material properties again for Civic compliance.


