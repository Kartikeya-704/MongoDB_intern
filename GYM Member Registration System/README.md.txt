🚀 Gym Member Registration System
Effortless Gym Member Management with Node.js, Express, and MongoDB

✨ Features
⚡ Quick Member Registration: Easily sign up new gym members with essential details.
Username (unique) 



Password 



Membership Type (Basic, Premium, VIP) 



Membership Expiry Date 



📊 Member Directory: View a clean and concise list of all registered members.
🗑️ Seamless Member Deletion: Remove members from the system with a single click.
💾 Persistent Data Storage: All member data is securely stored in a MongoDB database.
🖥️ Intuitive Web Interface: A simple and responsive front-end for smooth user interaction.
🛠️ Technologies Used
Backend
Node.js: The powerful JavaScript runtime.
Express.js: Fast, unopinionated, minimalist web framework for Node.js.
Mongoose: MongoDB object data modeling for Node.js.
Body-parser: Node.js body parsing middleware.
Frontend
HTML5: Structure for the web pages.
CSS3: Styling for a clean look.
JavaScript: Dynamic interactions and API communication.
Database
MongoDB: A NoSQL database for flexible data storage.
🚀 Getting Started
Follow these steps to get your Gym Member Registration System up and running on your local machine!

Prerequisites
Make sure you have the following installed:

Node.js (LTS version recommended)
MongoDB Community Server
Installation
Clone the repository:

Bash

git clone https://github.com/YourUsername/gym-member-registration-system.git
cd gym-member-registration-system
```

Install Node.js dependencies:

Bash

npm install
Configure MongoDB:

Ensure your MongoDB server is running. You can typically start it by typing mongod in your terminal.
The application is configured to connect to a database named sampledb at mongodb://127.0.0.1:27017.
Running the Application
Start the Node.js server:

Bash

npm start
You should see console output indicating:

MongoDB connected
Server started on http://localhost:3000
Access the application:
Open your web browser and go to:

http://localhost:3000
👨‍💻 Usage
Register a New Member:
Navigate to http://localhost:3000.
Fill out the "Gym Member Signup" form with the required details: username, password, membership type, and expiry date.
Click "Register Member". You will be redirected to a success page.



View All Members:
From the signup success page, click "View Members".
Alternatively, directly visit http://localhost:3000/members.html.
Delete a Member:
On the "Registered Members" page, locate the member you wish to remove.
Click the "Delete" button next to their details.
Confirm the deletion in the prompt.
📂 Project Structure
.
├── config.js               # MongoDB connection URI configuration 
├── public/                 # Static files (HTML, CSS)
│   ├── index.html          # Main signup form 
│   ├── members.html        # Displays list of members with delete functionality 
│   ├── signup.html         # Signup success page 
│   └── style.css           # Global styles 
├── server.js               # Express.js server, API routes, Mongoose schema 
├── package.json            # Project metadata and dependencies 
├── .gitignore              # Specifies intentionally untracked files to ignore
└── LICENSE                 # Project license information
├── README.md               # This documentation file
🙌 Contributing
Contributions are always welcome! If you have suggestions, find a bug, or want to add a new feature, please feel free to:

Fork the repository.
Create your feature branch (git checkout -b feature/AmazingFeature).
Commit your changes (git commit -m 'Add some AmazingFeature').
Push to the branch (git push origin feature/AmazingFeature).
Open a Pull Request.
📝 License
This project is licensed under the ISC License[cite: 14]. See the LICENSE file for more details.

📧 Contact
Your Name – your.email@example.com

Project Link: https://github.com/YourUsername/gym-member-registration-system