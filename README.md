# Introduction

This project is a chat Application in which multiple users can connect and chat in real time.
Messaging apps are increasing in popularity. Past few years have brought apps like Whatsapp,Telegram etc. Such applications are surrounding us. Messages are sent in an instant and you get real-time feedback. I tried to implement the same functionality and this was the motivation of the project.
It may sound rather complicated without knowing how it works, but in reality, socket.io makes things super convenient. 
I have separated things into client side and server side. For the client side, I have-
- index.html  holding the markup
- style.css responsible for the styles
- client.js containing the logic for sending messages to server, appending messages in message area,
receiving messages and other functionalities.

and on server side , I have server.js containing codes to run server.

This project has 2 dependencies : 

- socket.io :- socket.io is Javascript library that enables real time, bidirectional communication between browser and server.
- express.js :- express.js is web framework for node.js.

Live Demo : https://project1-chatapp.herokuapp.com/
