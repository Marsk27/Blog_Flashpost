Flashpost Blog

Flashpost Blog is a fast and lightweight blog built using Vite, React.js, MongoDB, Express.js, Node.js, and styled with Tailwind CSS. It provides a platform to create and share your thoughts, ideas, and insights through well-crafted blog posts.
Features

    User-friendly interface with a clean and responsive design.
    Easy-to-use editor for creating and editing blog posts.
    Markdown support for formatting blog content.
    Image handling using ImgKit CDN for efficient image processing and delivery.
    Secure authentication system for user registration and login.
    CRUD operations for managing blog posts, including create, read, update, and delete functionality.
    Search functionality to find specific blog posts based on keywords and Creator.
    Social sharing options for easily sharing blog posts on various platforms. (todo)
    Commenting system to enable readers to engage and provide feedback. (Yet to implemet)
    Separate frontend and backend folders for easy deployment and hosting.

Repository Structure

This repository follows a specific structure:

    server: Contains the backend code for the Flashpost Blog.
    Newfrontend/Flashpost: Contains the frontend code for the Flashpost Blog.

Deployment

The Flashpost Blog is hosted separately for the frontend and backend:

    Frontend: The frontend is hosted on Netlify and can be accessed at https://flashpost.netlify.app.
    Backend: The backend is hosted on Render .

Getting Started

To run the Flashpost Blog locally, follow these steps:

    Clone the repository: git clone <repository-url>
    Navigate to the backend folder: cd server
    Install the backend dependencies: npm install
    Set up the MongoDB connection by providing the necessary credentials in a .env file.
    Start the backend server: npm start
    Open a new terminal window and navigate to the frontend folder: cd Newfrontend/Flashpost
    Install the frontend dependencies: npm install
    Start the frontend development server: npm run dev
    Access the Flashpost Blog in your browser at http://localhost:3000
