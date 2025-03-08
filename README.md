🎥 Amigo - Video Conferencing App
Amigo is a robust video conferencing platform that offers secure logins, meetings, screen sharing, and more. Built using Next.js and TypeScript, it replicates popular tools like Zoom. Whether you're scheduling future meetings, joining a session, or managing participants, Amigo provides a seamless user experience.

📋 Table of Contents
🤖 Introduction
⚙️ Tech Stack
🔋 Features
🤸 Quick Start
🕸️ Assets & Code
🚀 More
🤖 Introduction
Amigo is a video conferencing app built with the latest Next.js and TypeScript. It allows users to log in securely, create and join meetings, and use various features like screen sharing, recording, and managing meeting participants. Inspired by Zoom, Amigo offers robust features for both casual and professional meetings.

✨ Key Highlights
✔ Authentication & Security – Secure sign-in via Clerk (Social & Email/Password login).
✔ Real-Time Interactions – Instant communication with smooth audio/video streaming.
✔ Meeting Management – Host & manage meetings effortlessly.

⚙️ Tech Stack
Technology	Purpose
Next.js	React framework for a fast, scalable app
TypeScript	Type safety & better code maintainability
Clerk	Authentication & user management
GetStream	Real-time messaging & stream management
Shadcn	Modern UI components & styling
Tailwind CSS	Responsive & customizable styling
🔋 Features
🔑 Authentication
Secure login via Clerk with support for both social sign-on and email/password authentication.
🎥 Create & Join Meetings
Start new meetings with customizable camera and microphone settings.
Join meetings via a simple meeting link.
🛠 Meeting Controls
Full control over meeting features like recording, screen sharing, muting/unmuting, and participant management (pinning, blocking, and unmuting).
🏠 Personal Room
A unique link for each user’s personal room, enabling instant meetings anytime.
📅 Schedule Future Meetings
Schedule meetings for the future and access them from the 'Upcoming Meetings' page.
🔄 View Past Meetings & Recordings
Easy access to past meetings and recordings for review or sharing.
⚡ Real-time Interaction
Instant messaging, screen sharing, and video/audio adjustments.
📱 Responsive Design
Fully responsive design ensures compatibility across different devices and screen sizes.
🔚 End Meeting Controls
Participants can leave or end the meeting for everyone.
🤸 Quick Start
📌 Prerequisites
Ensure you have the following installed:

Git
Node.js
npm
🔽 Clone the Repository
bash
Copy
Edit
git clone https://github.com/soumya-123-code/amigo.git
cd amigo
⚡ Install Dependencies
bash
Copy
Edit
npm install
🛠 Configure Environment Variables
Create a .env file in the root directory and add:

env
Copy
Edit
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

NEXT_PUBLIC_STREAM_API_KEY=
STREAM_SECRET_KEY=
🔹 Get your Clerk and GetStream credentials from:

Clerk Dashboard
GetStream Dashboard
▶ Start the Project
bash
Copy
Edit
npm run dev
🔗 Open http://localhost:3000 in your browser.

🕸️ Assets & Code
All assets such as UI components, images, and design files are included in the assets/ directory.
The code is modular, reusable, and scalable.
🚀 More
💙 Project By: Soumya Ranjan Nayak
📧 Email: soumya050794@gmail.com
🔗 GitHub: soumya-123-code
🔗 LinkedIn: Soumya Ranjan Nayak

Feel free to contribute to the project by submitting issues, feature requests, or pull requests.

🚀 Happy Coding!! 😁✌🏻