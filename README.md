# AR_Object_placment

This API contains our application's main function which is object handling.

Function:

- Search surface
This function looks for the surface and once surface found, show the surface plane. When surface search unavailable, it shows the alert below.

- Show depth-map
This shows the distance of objects. When the object is close enough, the map turns blue and when object is far, the map turns red.

- Place an object with a single touch
When you touch a display after surface recognition, the default object 'Andy' is placed.

- Move an object by dragging
When moving the object, place your finger on the object and drag it. Now you can see the object moved.

- Rotate the object with two finger
Using two fingers, you can rotate the object.


# Installation Environment

Implmented With: Android Studio, Java

Installation Environment:

>> Android Studio: IDE for Android app development officially supported by Google. Based on IntelliJ IDEA and using Gradle build system.

Android Studio App module:
>> manifests: includes the file "AndroidManifest.xml"

>> java: Contains Java source code files, including JUnit test code.

>> res: Contains all non-code resources (XML layout, UI string, bitmap image, etc.)

Library:

> implementation 'com.google.ar:core:1.19.0'
>
> implementation 'de.javagl:obj:0.2.1'
>
> implementation 'com.google.firebase:firebase-storage:19.2.0'
>
> implementation 'com.google.firebase:firebase-auth:19.4.0'
>
> implementation platform('com.google.firebase:firebase-bom:25.12.0')
>
> implementation 'jp.wasabeef:glide-transformations:4.0.0'
>
> implementation 'com.github.bumptech.glide:glide:4.11.0'

