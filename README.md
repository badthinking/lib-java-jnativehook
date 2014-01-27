lib-java-jnativehook
====================

Maven version of project : jnativehook.

https://code.google.com/p/jnativehook/

This library provide global keyboard and mouse listeners for Java.

About

JNativeHook is a library to provide global keyboard and mouse listeners for Java. This will allow you to listen for global shortcuts or mouse motion that would otherwise be impossible using pure Java. To accomplish this task, JNativeHook leverages platform dependent native code through Java's native interface to create low level system wide hooks and deliver those events to your application. 

The following events are globally available via their respective listeners.

Key Press Events
Key Release Events
Key Typed Events
Mouse Down Events
Moues Up Events
Mouse Click Events
Mouse Move Events
Mouse Drag Events
Mouse Wheel Events 

In addition to global keyboard and mouse events, the following system properties are exposed by the native library. Please note that there is no guarantee that any of these properties will be available.

jnativehook.autoRepeatRate
jnativehook.autoRepeatDelay
jnativehook.multiClickInterval
jnativehook.pointerSensitivity
jnativehook.pointerAccelerationMultiplier
jnativehook.pointerAccelerationThreshold 
        
######################
JNativeHook-1.1.4
