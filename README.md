# demo
link-https://youtu.be/Mtk3Kh37pdI
# Chat application
1.It is an scalable Realtime Chatting Application that provides an interface for multiple user chatting at the same time.

FrontEnd Technologies- HTML, CSS.

BackEnd Technologies- JavaScript, Node.js

Used Socket.io module for a two-way connection between client and server.

FrontEnd includes a navigation bar, Chat window and a form submit button for sending the messages.

HTML has been used for preparing the structure of application.

CSS has been used for styling the application.

Added Client sided JavaScript for the purpose of playing with DOM elements.

First of all stored all the DOM elements in a respectives JS variable.

Used Audio file (ting.mp3) which gives notification on receiving the messages.

Everytime a new user tries to join, first of all ask his/her name and let the server know.

If a new user joins, receive the event from the server using eventListner.

Receive message from server using receive function.

If a user leaves the chat, tell all the other users that this user has left the chat.

Server Side JavaScript will handle the Socket IO connections.

If a new user joins, let the other users connected with server know.

If someone sends the message, broadcast it to other people.

There is option to add emojis in message area other than from using "Window + .".

# Process to run the app
1.Run nodemon nodeserver/index.js

2.Install the extension 'live server' for Vs Code.

3.After the extension gets installed navigate to index.html and open it to edit.

4.Right click anywhere in the file index.html and from the menu that appears select Open with Live server.

5.A instance of the application will appear in the browser.

6.Copy the url from the address bar and open another instance in another tab or in incognito or on another browser.

# User Log in Prompt
<img width="960" alt="2022-07-21" src="https://user-images.githubusercontent.com/88128030/180169598-54e59ef4-7287-461f-8bc4-d75f5ffdb071.png">

# Ram portal
<img width="960" alt="2022-07-21 (2)" src="https://user-images.githubusercontent.com/88128030/180169553-6621197b-06e1-429f-9158-1e63dc7b8ccb.png">

# Raj Portal
<img width="960" alt="2022-07-21 (3)" src="https://user-images.githubusercontent.com/88128030/180169579-4f0cac9f-0b3d-43c3-ae51-14faf8e52b47.png">

# Ram left
<img width="960" alt="2022-07-21 (4)" src="https://user-images.githubusercontent.com/88128030/180170156-1c0fd2cb-159d-4721-910c-4a29c8fe5cdb.png">


