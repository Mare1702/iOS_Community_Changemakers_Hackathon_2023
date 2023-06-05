
While not displaying the actual code for this project for security reasons, I'll show videos of the App running with explanations on the technologies and ideas behind everything in RCPAR

## What is RCPAR?
It is a Swift Playgrounds App designed to teach some medical maneuvers with Augmented Reality, while what is presented here is just a prototype, RCPAR is planned for use in medschools, where licenced professors could use the app as a tool for explaining physical medical procedures like CPR, the Heimlich maneuver or breathing technics.

## - Functionalities
There are 2 completed fucntionalities implemented on the app, firstable, the "¡Aprenda sobre estas técnicas..." buttom takes the user to certified sites (in this case to the official RCP-México site, the official page for CPR training and information centre in Mexico) in wich to learn more about the technics displayed in the App.

https://github.com/Mare1702/SwiftUI_Development/assets/92188399/39a83738-f856-41ac-af51-b718f7604d89

On the other hand, the "Videos Explicativos" button is meant to show how one should use the App, since RCPAR requires to track the body and proportions of a person (and given that we didn't have access to hardware that could run the body tracking functionalities of ARKit and SwiftUI) we planned to train the App for it to recognize 4 different images that would be placed on each of the pacient shoulders and hips, so, with the use of these 4 targets, we can track any person's proportions for accurate display of where to perform a certain medical technic.

https://github.com/Mare1702/SwiftUI_Development/assets/92188399/e87d93c2-0817-4524-8d02-7a08e247322a

In the video, we are shown one example on the AR capabilities to demonstrate how to operate the app. While we weren't able to implement the target system mentioned earlier, the App is ready to be scaled up with the functionalities it needs to improve.

More information about RCPAR can be found on the Keynote presentation used to present the product to the hackathon's jury contained in this very folder.  

