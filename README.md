# SoundML
Apple Swift Machine Learning System for Analysis of Sound Scenes and Events

SoundML will use Apple Swift CoreML CreateML tools and develop iOS and MacOS apps that allow users to set up iOS devices to "listen" and recognize sounds for various purposes.

An example demo App is included here that listens to your home and recognizes sounds that may or may not generate alerts -- a prototype audio home security system. For example, breaking glass will generate an alert. Barking dogs will generate an alert. Doorbell or knocking on the door will generate an alert. You get the idea.

This project is about developing Swift sound analysis libraries and apps that take advantage of Machine Learning models to "learn" what happens in a typical sound scene, and label those events accurately.

The demo app is an audio home security system. We need to bootstrap the whole system. A Mac desktop client app (and command-line client) will be developed to gather data files and start a series of Machine Learning tasks that will produce CoreML Models that can be used in the iOS client apps for reviewing the data, visualizing and listening to the results of the recognizers, and creating a localized SoundML Model that will eventually become "smart" or "good" at recognizing sounds and classifying them into Alert or No Alert categories. Sound simple enough?

Sound scenes are idiosyncratic -- even common sounds, when recognized, will have distinctive characteristics in a different room or from a different distance. Machine Learning systems can detect and learn the differences in sounds, possibly as well as we can ourselves, if we "train" or "tune" the software to recognize these sounds. This will take some effort on our part, but we hope to make it a fun process, as well as a rewarding one.

## Project Vision Reference
Heittola T., Çakır E., Virtanen T. (2018) The Machine Learning Approach for Analysis of Sound Scenes and Events. In: Virtanen T., Plumbley M., Ellis D. (eds) Computational Analysis of Sound Scenes and Events. Springer, Cham

## Community Hub
- http://dcase.community/community_info
- https://github.com/TUT-ARG

