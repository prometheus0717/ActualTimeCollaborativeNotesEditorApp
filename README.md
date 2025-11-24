# Real Time Collaborative Notes Editor  
A Real-time Collaborative Editor using Node.js, WebSockets, and React   
 
## Overview        
    
Collab Editor is a real time collaborative editor that allows multiple users to edit a document simultaneously. This project uses Node.js, WebSockets, and React to provide a seamless collaborative experience.     
      
## Features     
   
* Real-time collaborative editing   
* Runs locally on your machine  
* Supports multiple users   
  
## Technologies Used  
  
* Node.js
* WebSocket
* React

## Dependencies

* express
* ws
* cors

## Getting Started

To run the Collab-Editor, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/Collab-Editor.git`
2. Install dependencies: `npm install express ws cors`
3. Start the server: `npm start server.js`
4. Open multiple browser windows and navigate to `http://localhost:3000` to start collaborating

## Working Demo


<img width="1355" height="717" alt="Screenshot 2025-08-18 005426" src="https://github.com/user-attachments/assets/b0990db9-f7da-44c5-a22a-74d88f81f19b" />


https://github.com/user-attachments/assets/705485b1-b3ca-41bf-95c5-1dd89f829443


## How it Works

The Collab-Editor uses WebSockets to establish a real-time connection between the client and server. When a user makes changes to the document, the changes are broadcasted to all connected clients using WebSockets. The React frontend updates the document in real-time, providing a seamless collaborative experience.

