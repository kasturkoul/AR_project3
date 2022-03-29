## AR Project 3

# Proposal

While thinking about initial ideas for this project, I thought about using pictures to create three dimensional virtual models that could be used in AR. This is a concept called photogrammetry, which is “the art and science of extracting 3D information from photographs” [1]. I checked for any software that is available and found an Apple API that does photogrammetry. Now that I had the tool, I thought of the idea to create an iOS game using photogrammetry and augmented reality where the user is given a prompt, takes photos of real-world objects, and uses three-dimensional augmented reality models created from those images. 

The game will start with a blank screen containing a field for the user to enter the number of words they want in the prompt and a button that will instruct the user to push it to receive the prompt. The prompt will be a set of between one to five words that will be selected from a word bank. If the user does not select a number, the application will default to 1. 

Once the user has selected a prompt, the application will open the iPhone camera and instruct the user to find real-world objects to take photos of. These real-world objects should relate to the prompt, but do not necessarily have to do so. The prompt will be shown on top of the screen while the camera is open. The user will indicate when they have found a real-world object by pressing a button. The application will instruct them to take a required number of photos of the object. These photos will be used to create a three-dimensional virtual model that is stored in the application database. Once the user has created the required number of models for the prompt, they will be instructed by the application to show their camera the image markers. The image targets will be associated with the order in which the models were created. The models will then be displayed on top of the appropriate image targets. Once the prompt has been fulfilled, the models will be deleted from the database, and the user can either play again or exit the application.

For the tools, Apple has an API called Object Capture that can be used to turn photos into virtual models. Because this is an Apple specific API, the main tools to create the application interface will be XCode, ARkit, and Swift. The application will be run on an iPhone XR, and the image targets will be in black ink on standard size white paper. 

There are some limitations to this application because of time constraints and lack of knowledge. One limitation is that users can take pictures of whatever images they want to despite the prompt. As a future improvement, the application can use a machine learning algorithm to check if the images are related to any of the prompts the user is given. Another future improvement is to let the users reselect prompts if they do not like the ones they are given. A bigger limitation is that this is an application built only for iOS devices. This is because the Object Capture API is only available for Apple devices, and I have a Mac and iPhone to work with. Otherwise, this will hopefully be a new and fun project to work on. 


Apple’s Object Capture: https://developer.apple.com/augmented-reality/object-capture/

Citations: 
[1] Autodesk.com. 2022. Photogrammetry Software | Photos to 3D Model | Autodesk. [online] Available at: <https://www.autodesk.com/solutions/photogrammetry-software> [Accessed 28 March 2022].

