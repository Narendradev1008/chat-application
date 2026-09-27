Real-Time Chat App 
A feature-rich, full-stack real-time chat application built from scratch.

 What It Can Do:
Real-Time Chat: Instantly send and receive messages with live online user status.

Media Sharing: Effortlessly share images and videos (optimized via ImageKit).

Customization: Choose from 13 custom wallpapers, 11 themes, light/dark modes, and optional keyboard sound effects.

Secure Auth: Seamless user authentication powered by Clerk, complete with webhooks.

Automation: Smart background tasks managed using automated cron jobs.

Built With:
Frontend: React, Tailwind CSS, Hero UI, Zustand, and Socket.io Client

Backend: Node.js, Express.js, MongoDB, Socket.io, and Clerk

Hosting & Database: Render (for deployment) & MongoDB Atlas

Environment Configuration:
Backend (/backend/.env)
Bash
PORT=5000
NODE_ENV=development
MONGO_URI=your_mongodb_connection_string

CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
CLERK_WEBHOOK_SIGNING_SECRET=your_clerk_webhook_signing_secret

IMAGEKIT_PRIVATE_KEY=your_imagekit_private_key
FRONTEND_URL=http://localhost:5173
Frontend (/frontend/.env)
Bash
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key

Developer: Narendra darji


Live Demo: https://chat-application-lrqe.onrender.com

Built this project to master full-stack real-time communication using WebSockets and modern UI frameworks like Hero UI.
