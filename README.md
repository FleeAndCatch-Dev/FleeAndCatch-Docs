# FleeAndCatch - Documentation
FleeAndCatch is a project about swarm behaviour to control a lot of small robots in a close system. This project is a part of the education of the cooperatice state university Karlsruhe germany.

The system is build by three different applications, which you can find in our repositories.
* FleeAndCatch-App [App](https://github.com/FleeAndCatch-Dev/FleeAndCatch-App)
* FleeAndCatch-Backend [Backend](https://github.com/FleeAndCatch-Dev/FleeAndCatch-Backend)
* FleeAndCatch-Robot [Robot](https://github.com/FleeAndCatch-Dev/FleeAndCatch-Robot)

## FleeAndCatch-App
The mobile application is based on the project Xamarin with an implementation in .NET C#, which can run on Android, iOS and Windows. With this application the user can control the robots in different szenarios, from a direct control system to complex szenario with multiple users and robots, with only one instance of an server application for handling. In our wiki we have a little description how you can install our application on your device.

<img src="https://www.xamarin.com/content/images/pages/branding/assets/xamarin-logo.png" width="250">

## FleeAndCatch-Backend
The server application is based on java 8. It provides a system for a registration of multiple LEGO robots an mobile applications, with a user interface for a specific information view. The devices communicate wireless to other devices with definied json commands through the server application, so this is the head of the hole project. 

<img src="https://upload.wikimedia.org/wikipedia/de/e/e1/Java-Logo.svg" height="100">

## FleeAndCatch-Robot
The robot is based on the LeJos system, which is implementing with java 7 and a specific library for the LEGO robot EV3. At our source code you can find implemented code for the registration of an robot, the communication and the control commands. The robot is controled of the server application and only get control commands from them, so it does not no somethin from other devices in a started szenario.

<img src="http://www.pgs-holzwickede.de/wordpress/wp-content/uploads/2015/09/mindstorms-schriftzug.png" width="250">

## Start guide
* Setup your LEGO robot - Link is coming
* Setup the server application - Link is coming
* Install an instance of the mobile application on your device - Link is coming

For more detail, you can have a look in our wiki our the documentation of our project.
Have fun with our application, we are open to any suggestions ;)
