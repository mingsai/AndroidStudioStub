# AndroidStudioStub
An application stub created in Automator that will use a specific version of Java when loading. 

To edit this stub, download the zipped automator file, open in Automator and edit the script to point to the JDK of your choice in the location on your machine. I recommend storing the file in the Utilities folder and if needed drag an alias to the Dock. This has the added benefit on allowing one to call the stub from Spotlight. Using the stub allows one to conveniently update Android Studio without having to constantly  deal with java versioning conflict messages. Whenever one wants to update to a new release of the JDK simply update your Java installation (SDK & JDK) as needed and then edit the Automator file. To update Android Studio just always open using the stub and perform the updates as normal within the Android Studio app. The Automator file also has had it's icon updated with the official icon from the Android Studio app. 

Just the script (useful if you'd prefer not using Automator and want to put this in a bash script):
export STUDIO_JDK=/Library/Java/JavaVirtualMachines/jdk1.8.0_65.jdk
open  /Applications/Android\ Studio.app

Tips:
When starting Andriod Studio just check to ensure that you are runnign from Utilities (after a few uses Spotlight will alawys pick this first). 

Putting the stub into your dock is another way to make sure you always use the version of JDK that you want with Android Studio.

