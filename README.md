
- # AncestroPedia - Backend Server

  \![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge\\&logo=nodedotjs\\&logoColor=white)

  \![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge\\&logo=express\\&logoColor=white)

  \![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge\\&logo=mongodb\\&logoColor=white)

  \![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge\\&logo=redis\\&logoColor=white)

  \![Passport.js](https://img.shields.io/badge/Passport-34E27A?style=for-the-badge\\&logo=passport\\&logoColor=white)

  \![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge\\&logo=JSON%20web%20tokens\\&logoColor=white)

  \![Razorpay](https://img.shields.io/badge/Razorpay-02042B?style=for-the-badge\\&logo=razorpay\\&logoColor=00C3FF)

  \![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge\\&logo=cloudinary\\&logoColor=white)

  This is the backend server for **AncestroPedia**, a Family Tree Application. Built using **Node.js**, **Express**, **MongoDB**, and **Redis**, the backend handles user authentication, family tree management, order tracking, notifications, reports, and more.

  ---

  ## 🚀 Getting Started

  ### Requirements

  \* Node.js \>= 16

  \* MongoDB

  \* Redis

  \* Cloudinary/ImageKit credentials

  ### Install & Setup

  \`\`\`bash

  git clone https://github.com/DheerajVerma945/server-ancestropedia.git

  cd ancestropedia-backend

  npm install

  \`\`\`

  ### Environment Variables

  Create `.env` from the sample:

  \`\`\`bash

  cp .env.example .env

  \`\`\`

  Update with:

  \* `MONGO_URI`

  \* `REDIS_URL`

  \* `JWT_SECRET`

  \* `RAZORPAY_KEY`, `RAZORPAY_SECRET`

  \* `CLOUDINARY_*` / `IMAGEKIT_*`

  ### Start Server

  \`\`\`bash

  npm start

  \`\`\`

  Server will run at: `http://localhost:7777`

  ---

  ## 🐳 Docker Support

  Launch project with Docker:

  \`\`\`bash

  docker-compose up --build

  \`\`\`

  It sets up Node, Redis, and optionally MongoDB (if configured).

  ---

  ## 🧪 API Testing

  \* Use [Postman](https://www.postman.com/) or [Thunder Client](https://www.thunderclient.com/)

  \* Add `Authorization: Bearer <token>` header for protected routes

  ---

  ## ✅ Features

  \* 👤 User Authentication

  \* 🌳 Family Tree (up to 7\+ generations)

  \* 💳 Razorpay payments

  \* 🔗 Family link requests & approval

  \* 📂 Folder & multimedia uploads

  \* 📢 Notifications system

  \* 🚼 Admin tools & token management

  \* 🛠️ Well-structured modular code

  ---

  ## 📌 Contribution Guide

  \* Fork the repository

  \* Create a new branch

  \* Commit and push your changes

  \* Open a pull request

  ---

  ## 🧠 Author

  Made with ❤️ by [\*\*Ancestropedia Team\*\*](https://ancestropedia.online)

  ---

  ## 📄 License

  This project is licensed under the **MIT License**.