Milestone 2

Team #1544: GruPix+

Shreyas and Ruhani

Targeted Level of Achievement: Apollo 11 (Advanced)

Project Aim: 

An Android application which is able to group all the non-private pictures present in a user’s gallery by the people present in it. That is, forming a folder for each person which contains all the pictures in which that particular person is present.

Scope:

For the present prototype, we have successfully made a homepage with our logo, which leads to the workpage displaying the gallery pictures. The pictures are imported from the external storage on the device and are divided into album folders displayed in Card View. Each album has details of the pictures within it and the name (mostly the source) of the pictures, such as Camera, Downloads, WhatsApp Images, etc. The pictures displayed are updated each time the app is run. 

One opened, each album lists the photo in Grid View. The photos also have a basic preview functionality along with zooming feature. This ensures that the user can use basic gallery features within the application itself, thereby reducing the need to go back to the Android gallery when using this application.

We intend to completely integrate facial recognition in the upcoming sprints to produce the first version of the final product. We envision to give the user the ability to run their pictures through the API and have the pictures displayed in folders sorted by faces. We will continue to use only the new non-private pictures available at the point of time when the user chooses to sync the application, which is updated every time the app is launched. The application will run on the most recent Android version and will be available to install on the Google Play Store.

Core Features:

The core features we have developed in the present prototype are:

Homepage: A transient homepage displaying the ‘GruPix+’ logo. This displays the group icon for 4 seconds and automatically transits to the next working page.
Main Workpage: The gallery page contains the albums stored on the external storage of the device. The pictures are divided into albums to give more control to the user and to replace the need to use the default gallery application on the android device. We have used card view to divide the gallery into albums, each displaying the number of pictures contained within and the name of the folder. When opened, each folder lists all the pictures inside it in a 2 column grid view, which is free to scroll and zoom. This is updated in real time, automatically when the app is launched. The photos also have preview functionality with zooming feature implemented. Thus, solving the issue of unnecessarily having to fall back to the default gallery application.

The features we intend to develop in the upcoming sprints are:

Sync Button: The sync button allows the user to sync his gallery so as to group the new pictures which might have been added since the previous sync, into their respective folders
Facial Recognition: Integrate the facial recognition APIs to run on the gallery images and create dedicated folders for each individual recognised. Each person will have a dedicated folder for storing their pictures and will be uniquely identified by their name or the default name assigned by the application, should the user decide not to name some folders. 
Search Bar: The search bar will allow to search between all the folders by the folder name, which is either the default name assigned by the application or a name the user assigns to it for convenience. This feature will be useful at times when the number of folders, ie. faces in the gallery exceed beyond a point and the user wants to search his/her named folders by their titles instead of scrolling through the entire list.

Resources used for this Milestone: 

Android Studio: We plan to use this working environment to create an application that can run on the Android O.S. We have gathered from our research that this platform might be the easiest and most efficient way to construct an Android application, especially for beginners.
Java 10: For the purpose of this project, we programme using the Java language (tentatively, version 10). Android Studio along with Java forms an ideal starter pack to actualize a workable Android application.
Online Courses: From YouTube channels and Android Authority articles to courses in Udemy and Coursera, we have studied the software we are working with in great detail. This includes studying working with Studio, Java for Android, how Android internal storage works, amongst others.

Problems Encountered:

Difficulty in sticking to the intended schedule. We are slightly behind schedule due to undermining the difficulty of importing the pictures on the external storage of the android device and displaying them as folders (Camera/Downloads etc) on the application itself.
Difficulty in integrating different parts of code written by the team members.
Inadequate planning of tentative schedule resulting in not being able to complete the major core feature- Face recognition before Milestone 2.
Tried out different versions for the same feature, for instance we tried using both recyclerview and grid view for displaying the pictures as a list but decided to use grid view in the end. This resulted in unnecessary time overheads as the code used for recyclerview wasn’t included in the present prototype. 
Replanning the scope, such as whether or not to include a sync button and which implementation to carry out the grouping of pictures by.

Tasks performed by each member:

Shreyas:
Decided on the homepage and the logo with Ruhani.
Wrote the code for the transient homepage.
Wrote the code for importing the gallery pictures from the external storage of the device.
Wrote the code for displaying the pictures as albums using card view.
Designed the UI of the application and integrated different parts of code.

Ruhani:
Decided on the homepage and the logo with Shreyas.
Wrote the code for displaying the pictures using recyclerview which however wasn’t included in the present prototype.
Wrote the code for displaying the pictures using grid view.
Designed the preview functionality of the pictures.

Tentative Schedule ahead:

Sprint 3. 2nd July to 15th July - Finish integration and get face recognition working; begin working on using FR on the user gallery pictures and give a unique identifier to the unique photos (person’s name).
Sprint 4. 16th July to 29th July - The user should be able to feed a name and get all pictures containing the same person, and implement a ‘Sync’ button to also group the new pictures added into the gallery since the last syncing and grouping.
Final Sprint. 30th July to 5th September - Spillovers margin, testing the application, and further enhancements and extensions depending on time.

User Stories:

As a user, I want the app to run the FR API on the gallery pictures, and display the pictures grouped by faces.
As a user, I want to have a sync button which allows me to run the FR on newly synced pictures from the gallery.
As a user, I want to able to search through the folders by name.

Project code: 

Available on Github: https://github.com/ShreyasKp/GruPixPlus
