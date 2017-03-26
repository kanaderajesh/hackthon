Welcome to Hackathon!
===================


Tooling Required for POC
-------------

> **Note:**

> - Please refrer to url https://css-tricks.com/image-upload-manipulation-react/ which will give you details about a service called cloudinary which we will be evaultng in the first phase.

> - Install postman for API testing, its a chrome plugin install it from chrome store.

> - Please check Azure main page https://www.microsoft.com/cognitive-services/en-us/face-api for SDK related information.

Steps of testing Azure Face API with Zappier
-------------

> **Steps:**

> - Upload image manually to dropbox source and target. upload mulitiple images and make sure that there wil be an image for comparision. Get URLs uploaded images.

> - use Azure FACE API to target image and soruce images from comparision. Azure FACE Api SDK is documented at https://www.microsoft.com/cognitive-services/en-us/face-api

> - First create a Face list Use API Face List - Add a Face to a Face List Sample URL: https://westus.api.cognitive.microsoft.com/face/v1.0/facelists/{faceListId}/persistedFaces[?userData][&targetFace]
Sample documentation is available at https://westus.dev.cognitive.microsoft.com/docs/services/563879b61984550e40cbbe8d/operations/563879b61984550f30395250

> - Add images to Create Face lisy above Face List - Add a Face to a Face List
API documentation is avaiable at  https://westus.dev.cognitive.microsoft.com/docs/services/563879b61984550e40cbbe8d/operations/563879b61984550f30395250

> - Create person by using API Person - Create a Person
API documentation is avaiable at  https://westus.dev.cognitive.microsoft.com/docs/services/563879b61984550e40cbbe8d/operations/563879b61984550f30395250

> - Use face detect API to detect face 
API documentation is avaiable at 
https://westus.dev.cognitive.microsoft.com/docs/services/563879b61984550e40cbbe8d/operations/563879b61984550f30395236/console

> - Please use the console to fire REST call