# SoundML
Apple Swift Machine Learning System for Analysis of Sound Scenes and Events

SoundML will use Apple Swift CoreML and CreateML tools and develop iOS and MacOS apps that allow users to set up iOS devices to "listen" and recognize sounds for various purposes.

An example demo App is included here that "listens" to your home or office and recognizes many of the sounds in that environment. Certain sounds may or may not generate alerts -- the demo app is a prototype audio home security system that learns to recognize and categorize sounds. Recognized sounds are configurable. You can customize the alert status for each recognized sound. For example, breaking glass will, if you choose, generate an alert. Barking dogs (in your house) will generate an alert, if you choose. A doorbell ring or knock on the door will generate an alert, if you choose. You get the idea.

This project is about developing/testing Swift sound analysis libraries that take advantage of Machine Learning models to "learn" all the common sounds in a sound scene, and label those events accurately with user feedback for sound identification. 

iOS is chosen as the target platform because: 
- security and privacy are built-in. 
- iOS hardware performance is fine for ML applications. Users can train their iOS microphones in their sound environments on their iOS devices without sending data to a central server.
- the market is large, diverse, untapped, and commercially viable.

The eventual goal is to develop (and sell) smart microphones for many applications. The first proof-of-concept is a demo app for a home security system.

A Mac desktop client app (and command-line client) is also included here to gather data files and bootstrap a series of Machine Learning tasks that will produce/tune CoreML Models that can be used in the iOS client apps. 

Views will be developed for visualizing and reviewing the sound data files, visualizing and listening to the recognizers results, and, possibly most importantly, efficiently annotating the sound timeline with a growing list of identifiers for the local world where the microphones are "listening" to sounds overlapping in a constantly changing background.

Most accurate sound identification via ML requires locally sourced/trained data from stationary microphones, or else you also need a very complex world model to represent location and signal complexity, which is beyond the scope here.

Sound scenes are idiosyncratic -- even pure common sounds will have distinctive characteristics in a different room or from a different distance. Machine Learning systems can detect, identify, and learn to recognize all sounds, possibly as well as we can ourselves, if we train or "tune" the models to discriminate the subtleties in these sounds. This will take some user effort, but we hope to make it a fun process, as well as a rewarding one.

Swift CoreML and CreateML tools will be used to create localized SoundML Models that will eventually become "smart" or "good" at recognizing sounds and classifying them into Alert or No Alert categories. 

## Project Vision Reference
Heittola T., Çakır E., Virtanen T. (2018) The Machine Learning Approach for Analysis of Sound Scenes and Events. In: Virtanen T., Plumbley M., Ellis D. (eds) Computational Analysis of Sound Scenes and Events. Springer, Cham

## Community Hub
- http://dcase.community/community_info
- https://github.com/TUT-ARG
