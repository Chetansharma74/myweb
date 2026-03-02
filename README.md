# myweb

🚀 Coding Vieb – Developer Learning Platform
Coding Vieb is a modern EdTech platform built for beginner to intermediate developers.
This platform provides tutorials, blogs, resources, and future-ready course systems.
🌐 Live Demo
(Add your deployed link here)
Copy code

https://yourwebsite.com
👨‍💻 Founder
Chetan Sharma
Web Developer | Content Creator | Founder of Coding Vieb
Instagram: @coding_vieb
🛠 Tech Stack
Frontend
Next.js / React.js
TypeScript
Tailwind CSS
Framer Motion
Backend
Node.js
Express.js
JWT Authentication
Database
MongoDB Atlas
Media & Payments
Cloudinary
Razorpay (future ready)
✨ Features
🔥 Modern SaaS UI (Dark Theme)
📚 Tutorials Hub with filters & search
📝 SEO Optimized Blog System
🎓 Course Structure (Free + Premium Ready)
👤 User Dashboard
🛠 Admin Panel
📂 Resource Vault (PDFs & Projects)
🔐 Authentication System
📈 Progress Tracking
💌 Newsletter System
📂 Project Structure
Copy code

coding-vieb/
│
├── client/ (Frontend)
│   ├── components/
│   ├── pages/ or app/
│   ├── hooks/
│   ├── styles/
│
├── server/ (Backend)
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│
├── .env
├── package.json
└── README.md
⚙️ Installation & Setup
1️⃣ Clone Repository
Bash
Copy code
git clone https://github.com/yourusername/coding-vieb.git
cd coding-vieb
2️⃣ Install Dependencies
Frontend:
Bash
Copy code
cd client
npm install
Backend:
Bash
Copy code
cd server
npm install
3️⃣ Setup Environment Variables
Create .env file inside server:
Copy code

MONGO_URI=your_mongodb_url
JWT_SECRET=your_secret_key
CLOUDINARY_URL=your_cloudinary_key
Frontend .env.local:
Copy code

NEXT_PUBLIC_API_URL=http://localhost:5000
4️⃣ Run Project
Backend:
Bash
Copy code
npm run dev
Frontend:
Bash
Copy code
npm run dev
🚀 Deployment
Frontend → Vercel
Backend → Render
Database → MongoDB Atlas
Make sure environment variables are added in production dashboard.
🔐 Future Improvements
Payment Integration (Razorpay)
Certificate Generation
Community Forum
Gamification System
Mobile App Version
📈 Vision
To build Coding Vieb into a scalable EdTech brand that helps students learn coding in a practical and simple way.
⭐ Support
If you like this project, give it a ⭐ on GitHub.
