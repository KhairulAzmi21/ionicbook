# Step 2: Use npm to install the Ionic CLI and Cordova for native app development

If you have followed the step 1 of installing npm, now lets use the npm to install **Ionic CLI** and **Cordova**. Apache **Cordova** is a popular mobile application development framework owned by Adobe now as PhoneGap.

**Ionic 3** use Cordova to access mobile native features like camera.

## Steps to install Cordova:

#### Prerequisites:

npm should be installed on your machine. Run this command to see the npm is installed.

```
npm -v
```

Output of the command should display the npm version:  
![](/assets/Screen Shot 2017-10-09 at 11.50.37 AM.png "npm -info")

#### Step 1: Open the Terminal / Bash

Run this command on your terminal

```
npm install -g ionic cordova 
*note: you might need to add sudo for mac/linux user
```

![](/assets/Screen Shot 2017-10-09 at 3.18.39 PM.png "cordova-command")

Wait till the installation complete:

![](/assets/Screen Shot 2017-10-09 at 3.22.12 PM.png "cordova")

#### Step 2: Verifying the installation

Run this command on your terminal to check if **cordova** and **ionic CLI** is installed

```
cordova -v
ionic -v
```

![](/assets/Screen Shot 2017-10-09 at 3.22.59 PM.png "cordova-3")

