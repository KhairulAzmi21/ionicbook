## Installing the Requirements

---

#### 1. Java Development Kit \(JDK\)

Install [Java Development Kit \(JDK\) 8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) or later.

> **We need to set**`JAVA_HOME`**Environment Variable according to your JDK installation path  \(Step 4\)**

#### 2. Android SDK

Android SDK is included inside [Android Studio](https://developer.android.com/studio/index.html). So we install android studio ![](/assets/Screen Shot 2017-10-09 at 4.13.06 PM.png)

> **We need to set**`ANDROID_HOME`**Environment Variable according to your JDK installation path  \(Step 4\)**

#### 3. Adding SDK Packages

After installing the Android Studio, Open android studio and you will see .  
![](/assets/Screen Shot 2017-10-09 at 4.16.21 PM.png)

1. **Click configure and choose SDK Manager , on tab SDK Platform**
   you must also install the packages for whatever API level you wish to target.
   ![](/assets/Screen Shot 2017-10-09 at 4.19.34 PM.png)
2. **Go to tab SDK Tools, installed :**
   * Android SDK build-tool  
     Android Emulator  
     Android SDK Platform-Tools  
     Android SDK tools  
     Intel x86 Emulator Accelerator \(HAXM Installer\)  
     Support Repository  
     ![](/assets/Screen Shot 2017-10-09 at 4.25.54 PM.png)

### 4. Setting environment variables

Cordova's CLI tools require some environment variables to be set in order to function correctly. The CLI will attempt to set these variables for you, but in certain cases you may need to set them manually. The following variables should be updated:

1. Set the
   `JAVA_HOME`
   environment variable to the location of your JDK installation
2. Set the
   `ANDROID_HOME`
   environment variable to the location of your Android SDK installation

#### OS X and Linux

On a Mac or Linux, you can use a text editor to create or modify the`~/.bash_profile`file. To set an environment variable, add a line that uses`export`like so \(substitute the path with your local installation\):

```
export 
ANDROID_HOME
=
/Development/android-sdk/
```

#### Windows

These steps may vary depending on your installed version of Windows. Close and reopen any command prompt windows after making changes to see them reflected.

1. Click on the**Start**menu in the lower-left corner of the desktop

2. In the search bar, search for**Environment Variables**and select**Edit the system Environment Variables**from the options that appear

3. In the window that appears, click the**Environment Variables**button

##### To create a new environment variable:

1. Click
   **New...**
   and enter the variable name and value

##### To set your**PATH**:

1. Select the**PATH**variable and press**Edit**.

2. Add entries for the relevant locations to the**PATH**. For example \(substitute the paths with your local Android SDK installation's location\):

   ```
   C:\Development\android-sdk\platform-tools
   C:\Development\android-sdk\tools
   ```

  


