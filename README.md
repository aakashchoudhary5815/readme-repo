<h2>Hey Folks!</h2>

<h3>How's all doin?</h3>

<h2> Brief Introduction </h2>

<p>Here I present you the interactive Microsoft Teams Clone built with best technologies like Node.js ExpressJS and MongoDB database.

It also contains featuring technologies like NodeMailer for sending the mails, Socket.io for chatting purposes and Firebase for Google Authentication and Chat Database Service.</p>

<p>Follow the instructions below to run the project.</p>

<pre>
  <code>
    1. Clone this project using <strong> git clone </strong> command or download the .zip file and extract it.
    2. cd to project directory and move inside <strong> microsoft-engage-dashboard. </strong>
    3. Use <strong> npm install </strong> command to install all the required modules.
    4. Open the terminal and type <strong> npm start </strong> to run the project.
    5. Move to <strong> views -> home.ejs -> Join Room button </strong> in line 32.
    6. Replace the href in anchor tag by <strong> http://localhost:3000 </strong> and save the file.
    7. Open new terminal and cd to <strong> ms-engage-video-call. </strong>
    8. Repeat Step 3.
    9. <strong> cd to src and run npm start </strong> to start the server.
    10. Open <strong> http://localhost:8000 </strong> in your browser and follow the flow.
  </code>
</pre>

<h2> Brief Overview of Code </h2>

<h3> 1. Microsoft Engage Dashboard </h3>

<p> This provides an intercative view of Personalised the Dashboard for room participants where they can,
    
    1. View all the announcements and updates.
    2. Add Comments to the Announcements.
    3. View all the participants.
    4. Setup their profile post authorised login.
    5. Chat with the fellow participants.
  
  The <strong> authorisation, post storage and user storage is implemented using Mongodb Database and Mongoose Client, </strong> whereas, <strong> the chat service is implemented by Socket.io module.</strong>
  
  In addition to this, <strong> the moment any user post any announcement in the channel, they get a personalised mail containing a copy of their post for further reference which is implemented by much useful NodeMailer. </strong> </p>
  
  <h3> 2. Microsoft Engage Video Call </h3>
  
  <p> This provides an interactive view of Meet Room where,
    
      1. User authorise himself/herself to create a meet room link which can be shared by fellow participants who he/she wish to be in room. 
      2. The meet contains all basic and additional interactive features like,
          
         2.1 Controlling toggles of Camera and Microphone
         2.2 User can share their screen and can view side by side by interactive feature of picture in picture.
         2.3 User are allowed to record screen as well as video of other users.
         2.4 Users can chat with other meet participants which is governed by firebase real time database.
         2.5 Chats are accessible to all users even they join late.
    
      3. Once the admin who made the meet room logs out, the chats are cleared taking security protocols in consideration.
    
   The video streaming feature is controlled by web RTC module and else the authorization and chat storage part is managed by firebase and socket.io. </p>
   
  <div class="footer">
        &copy; 2021 Under the Guidance of Microsoft Corporation
   </div>
