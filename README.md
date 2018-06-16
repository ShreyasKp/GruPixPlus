Team #1544: GruPix+

Members: Shreyas and Ruhani

Targeted Level of Achievement: Apollo 11 (Advanced)

Project Aim: 

An Android application which is able to group all the non-private pictures present in a user’s gallery by the people present in it. That is, forming a folder for each person which contains all the pictures in which that particular person is present.

Motivation:

For the purposes of making a birthday collage for your friend, or when sending a friend all his pictures from an event, or when trying to revisit the good times you spent with someone special, we often have to manually scroll through the entirety of our gallery in search of all those pictures having that specific someone. Our team thought it would be of great convenience to many if we can make an application which is able to sort the pictures in the user’s gallery by the people present in. That is, forming a folder each for each person with all the pictures of him/her.

Most galleries in the early Androids do not have this feature and most other facilities that offer something similar do so online (such as Google Pictures) or are paid. We aim to make an offline application that can perform a similar function, and is free of charge.

Scope:

For the first version of this project, we intend to implement the basic feature of facial recognition using which the application is able to sort the user’s gallery into folders for each person. We will only use the new non-private pictures available at the point of time when the user chooses to sync his gallery with the application. The application will run on most recent Android version and will be available to install on the Google Play Store. 

In the future, we may look at further enhancements and extensions, as discussed in the heading ‘Future Extensions’ below.

Target Audience: 

This application is available to all users with no age limit. Anyone keen on having such a feature applied to their gallery will find this application useful. Based on statistics, we expect most users to be teenagers or young adults.

Resources: 

Android Studio: We plan to use this working environment to create an application that can run on the Android O.S. We have gathered from our research that this platform might be the easiest and most efficient way to construct an Android application, especially for beginners.

Java 10: For the purpose of this project, we programme using the Java language (tentatively, version 10). Android Studio along with Java forms an ideal starter pack to actualize a workable Android application.

Android APIs: To understand how and to what level we can interact with and access the gallery on an Android device, we will make use of the Android API documentations made available.

Facial Recognition APIs: To get this main feature of the app functioning, we plan to use some pre-existing APIs. We will explore and choose what fits the needs, test to ensure they give correct output and then begin integrating it into our application.

Project Description:   

Some of the salient features we wish to include in this application include:

A homepage: This is what the application will open to. This will ideally contain the name of the application ‘GruPix+’, a logo and maybe a tagline/short description of the application.

Main Workpage: Before the gallery is synced for the first time, this page will display a message like ‘Press the Sync button below to begin!’. After the gallery from the user’s phone is synced, this page’s body will tentatively display all the unique faces in each folder, grouping all the pictures of that person. The user will be given an option to name the folder for each person if they desire too, for further convenience. 

Sync Button: The sync button allows the user to sync his gallery so as to group the new pictures which might have been added since the previous sync, into their respective folders

Individual Folder: Each person will have a dedicated folder for storing their pictures and will be uniquely identified by their name or the default name assigned by the application, should the user decide not to name some folders. 

Search Bar: The search bar will allow to search between all the folders by the folder name, which is either the default name assigned by the application or a name the user assigns to it for convenience. This feature will be useful at times when the number of folders, ie. faces in the gallery exceed beyond a point and the user wants to search his/her named folders by their titles instead of scrolling through the entire list.

How we are different:

Applications on Android which have the aforementioned functionality do so online (Google Photos). We, however aim to make an offline application for the same.
Some Android phones do not offer this feature in their gallery functionality.
Some services charge for this feature! We plan to do it for free :).
We also aim to include a feature for accessing photos with more than one person, that is, grouping those pictures with all those people (minimum) present as specified by the user; a functionality which does not exist in competitor applications.
We also aim to include a feature by which the user is able to tell the number of people he wants in the pictures. 
Lastly, a feature which makes it possible to apply these constraints simultaneously when searching through pictures.

User Stories:

As a smartphone user who wants to manage his/her gallery well, I want to be able to group pictures by the people present in my gallery.
As a user, I want the application to have access only to the non-private pictures in my gallery.
As a user, I want to be able to take pictures within the application itself to save the hassle of shifting between applications.
As a user, I want to be able to obtain those pictures with more than one person in my gallery as specified by name or number.

Tentative Schedule:

Sprint 1. 4th June to 17th June - Make a working application, decide on the homepage design and get the gallery to be imported on the working page.

Sprint 2. 18th June to 1st July - Study Facial Recognition (FR) APIs and other options available, testing the APIs and integrating into the application.

Sprint 3. 2nd July to 15th July - Finish integration and get face recognition working; begin working on using FR on the user gallery pictures and give a unique identifier to the unique photos (person’s name).

Sprint 4. 16th July to 29th July - The user should be able to feed a name and get all pictures containing the same person, and implement a ‘Sync’ button to also group the new pictures added into the gallery since the last syncing and grouping.

Final Sprint. 30th July to 5th September - Spillovers margin, testing the application, and further enhancements and extensions depending on time.

Future Extensions:

Possible future enhancements that we may implement if time and resources permit (maybe after Orbital 2018):

To group photos with more than one person in it. Gather photos containing all persons as specified in the search criteria.
Grouping by number of people, that is a user is able to specify if they want a picture containing a group of 10 or all solo pictures.
Allow the application to have access to the Camera and hence be able to take pictures within the application.
Adding a deleting option, whereby the users are able to remove certain or all pictures of a person from their gallery storage.

