# Microsoft Teams Clone by Deekshita Verma

## Motivation Behind the Project 

This project has been developed as a part of the **Microsoft Engage Mentorship Program 2021**. The soul purpose of this project was to make the group video call experience more comfortable for the end user keeping in mind a good and easy user interface, smooth experience and easy to connect. This project has been made possible by NodeJS, Javascript, ExpressJS, HTML, CSS, WebRTC, PeerJS and Socket IO. This project definitely made me step out of my comfort zone. Being a Game Developer and an Augmented Reality Developer, the concept of websites was very new to me and hence I initially decided to stick to my gaming engine and make a video call app but after talking to my amazing mentors : **Swarandeep Sir** and **Abhilekh Sir**, I made up my mind to challenge myself and learn a new technology along with making this project. 

## Features
1. Unique room ID's for every meeting or chat
2. Mail the invitation link via a single button click
3. One-on-One Video Calling ( minimum feature )
4. Group Video Call ( works very smooth upto 4 participants, can lag after that )
5. Display name is taken as an input from the user
6. Participants appear in structured grids
7. Can be used as an individual chat application without initiating the video call
8. In-meeting chat
9. Meeting chat window can be minimized when not in use
10. Video on/off
11. Mic mute/unmute
12. Chat backup stays on the same link 
13. A new user entering the room can view the previous chat
14. Chat before and after the meeting so as to not disturb the flow of the video conferencing
15. Auto scroll when a new message is sent
16. The meeting chat is linked to the chat room corresponding to it hence a user can chat with people in the meeting without being there
17. Leave video conferencing feature redirects to the chat room
18. The video is removed from the grid when the user leaves the call
19. Both the meeting and chat have the same room ID corresponding to them so as to ease the process for the user
20. Chat messages can be sent by pressing enter or the send button present in the chat window
21. Video conference room is generated and redirected to when you press on join call in the chat room

## Challenges Faced

Learning a new technology and coming up with an industrial project brings along a lot of challenges and shapes your project furthermore. I definitely feel if someone hasn't had challenges then they definitely didn't step out to explore more. Some of the challenges I went through : 

1. Learning and adapting a foreign concept. Being an Augmented Reality Developer the way of implementation and process is very different from developing websites, so I had to reasearch and go over 4-5 tutorials to find out the flow of work, list down all the necessities and find resources which could help me understand what exactly was I implementing.
2. Documenting and making notes for every statement I found online related to the code so that I am 100% sure of what each statement is doing because learning experience definitely matters more.
3. Understanding frontend and backend and how to link them together. I did have a basic knowledge of HTML and CSS so building a frontend design was not that much of a task but this was the first time I used firebase and implemented a real-time database to link the chat perfectly.
4. I wasn't able to link 2 socket connections in 1 server and since my chat app and video call app were based on 2 different sockets and it was difficult to understand how to make it work I had no other option so I switched them to 2 individual projects and linked them via the redirecting page code.     
5. Authentication. Having security and authentication in the code is really important and I was trying to link authentication via firebase but it was a little tricky to understand and given the time constraint I prioritised the adapt feature over authentication.

## Future Scope

This project can be scaled up quite a lot. There are features which I planned but wasn't able to apply : 
1. Authentication
2. Better UI
3. Extracting display name directly via the authentication ID
4. Linking both chat and call in the same domain
5. Screen Sharing
6. Reducing size of video grid when a new person enters so that the video grids are more flexible to incorporate people
7. Participant List
8. Announcing entry and leaving of a user from the chat

## Try the web app

Link : https://roomchat-deekshitaverma.herokuapp.com
