# Video-conferencing-web-application
* Developed a WebRTC enabled multi-party video conferencing and web chat application
* Enhanced app by adding collaborative drawing canvas, presentation sharing and video sharing.
* Optimized application for low-bandwidth scenarios by providing an optional audio stream only toggle.

Please refer to the project report pdf file for detailed summary.

Features:
* User Registry – Maintains a list of registered users in our database and allows
only those users to use our application.
* Dynamic Rooms – The rooms are created dynamically giving users the freedom
to name the rooms according to their choice.
* Video conferencing - Supports live video conferencing for multiple rooms at the same time
Canvas sahring - Real-time whiteboard sharing with one controller (who can be changed)
* Public Chat – It is a common per-room chat where the user can type a message
which will be sent to all the members of the room.
* Private Chat – It is a chat between any two users of the room which is exclusive
to them.
* Presentation sharing - Real-time presentation sharing functionality
Video streaming and sharing - Real-time video streaming and sharing 

User types:
* General user - The participant in the meeting. Can view videos of other users, view canvas, view presentations and participate in chats. Can be converted into a controller by the administrator.
* Administrator – The creator of the room is known as the administrator. Holds
various powers like granting control to other users, muting other users and ending
the meeting.
* Controller – The user who has the rights to present a presentation, stream a local
video or draw on the canvas is known as the controller.

Modes: 
* Videos Mode – Displays the video stream from the cameras of all the other
meeting participants.
* Canvas Mode – Allows the current controller to add, manipulate and delete
objects on the canvas which will be visible to all the other users.
Page 4NG-I2I, Real Time Communication with WebRTC
* Presentation Mode - Allows the current controller to present a presentation
which will be visible to all the other users.
* Video Stream Mode – Allows the current controller to stream a locally stored
video file to al the other users in addition to his camera stream.

Specifications:
* Application development framework: Spring (Java)
* Front end code: Javascript, AJAX, WebRTC, websockets, Apache POI, Kurento client APIs, Material design, Fabric.js


Made By :- Aryan Dinodia