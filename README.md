# LinkedIn Clone

A full-stack LinkedIn Clone built using **MERN Stack**.  
Users can create posts, like, comment, and connect — just like the real LinkedIn.

## 🚀 Live Demo
🔗 [View Live Project](https://linkedin-frontend-m27s.onrender.com)

## 🛠️ Tech Stack
- MongoDB
- Express.js
- React.js
- Node.js
- Render

## 📸 Screenshots
### 🏠 Homepage
![Homepage](<img width="1886" height="1044" alt="home page" src="https://github.com/user-attachments/assets/27c3f192-11e1-4bd3-bc76-d109942ab2bc" />
)
### 📰 Post Page
![Post Page](<img width="1716" height="928" alt="post page" src="https://github.com/user-attachments/assets/b559ae97-9bbb-447c-ae40-4eb64d90c6b9" />)
### 👤 Profile Page
![Profile Page](<img width="1920" height="1050" alt="profile page" src="https://github.com/user-attachments/assets/5afdbe43-2f1c-42ab-a09c-95f69841b1a7" />)

## 🧑‍💻 Setup Locally

Follow these steps to run the project on your local machine:

```bash
# Clone the repository
git clone https://github.com/your-username/your-repo-name.git

# Navigate into project folder
cd your-repo-name
1️⃣ Backend Setup
cd backend
npm install

Create a .env file inside the backend folder and add:
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

Then run:
npm run dev

2️⃣ Frontend Setup (Vite + React)
cd ../frontend
npm install
npm run dev
