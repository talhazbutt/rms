# EATS Android Application

Please push your project to this repository. You have to integrate with your respective modules yourself. You will encounter conflicts once you push your project so it is your job to merge the conflicting files sensibly. E.g. each individual project has its own Android Manifest file. You must not replace the Android Manifest file but add your code to the existing Manifest file uploaded on this repository so code of other groups is not overwritten. Please note if any group fails to follow these instructions and overwrites the files shall be penalized as it is very easy to identify the culprit.

You may learn how to use GitHub with Android Studio using the following tutorial:

https://medium.com/code-yoga/how-to-link-android-studio-with-github-312037a13b99


# MODULES TO BE INTEGRATED

1) PiedPiper (Admin Module)
2) Dine In Ordering System (Kitchen Module)
3) The Nepalis (Bill Generation Module)
4) Restaurant Ordering System (Hall Management Module)
5) The Trio (Order Management Module)
6) Where's The Food (Update/Cancel Order)

# IMPORTANT INSTRUCTIONS

The firebase SDK version should be set to 16.0.5 (in build.gradle file), as below:

implementation 'com.google.firebase:firebase-core:16.0.5'
implementation 'com.google.firebase:firebase-database:16.0.5'
implementation 'com.google.firebase:firebase-storage:16.0.5'

 
In addition to this, the Android SDK versions should be:

minSdkVersion 21 (corresponds to Android 5.0)
targetSdkVersion 28 (corresponds to Android 9)

 
and the support libraries should be of version 28:
e.g. implementation 'com.android.support:recyclerview-v7:28.0.0'



Thanks!

Team EATS

Contact Details:

Abdul Hameed Azeemi (l154031@lhr.nu.edu.pk)

Mohammad Hamza Sohail (l154074@lhr.nu.edu.pk)

Talha Zubair (l154166@lhr.nu.edu.pk)

Avais Muhib Ur Rasool (l154289@lhr.nu.edu.pk)






