# 🚀 Getting Started

Follow the steps below to set up and run the project on your local machine.

## Prerequisites

Before running the project, make sure you have the following installed:

- Node.js
- MongoDB Atlas Account
- Cloudinary Account
- Git

---

# 📦 Server Setup

1. Clone the repository.

```bash
git clone <repository-url>
```

2. Navigate to the server directory.

```bash
cd server
```

3. Install dependencies.

```bash
npm install
```

4. Create a `.env` file inside the `server` folder.

5. Add the required environment variables.

```env
PORT=5000
JWT_SECRET="gs#secret"

MONGODB_URI="mongo-url"

CLOUDINARY_CLOUD_NAME='cloud-name'
CLOUDINARY_API_KEY='api-key'
CLOUDINARY_API_SECRET='secret-key'

```

6. Start the backend server.

```bash
npm run server
```

---

# 💻 Client Setup

Open a new terminal.

1. Navigate to the client directory.

```bash
cd client
```

2. Install dependencies.

```bash
npm install
```

3. Create a `.env` file inside the `client` folder.

```env
VITE_API_BASE_URL=http://localhost:5000/api/v1
```

4. Start the React development server.

```bash
npm run dev
```

---

# 🌐 Access the Application

Once both servers are running, open your browser and visit:

```
http://localhost:5173
```

---

# 📁 Project Structure

```
project-root/
│
├── client/
│   ├── src/
│   ├── public/
│   └── .env
│
├── server/
│   ├── src/
│   ├── uploads/
│   └── .env
│
└── README.md
```

---

# ⚠️ Important Notes

- Start the backend server **before** starting the frontend.
- Make sure your MongoDB Atlas database is configured correctly.
- Ensure Cloudinary credentials are valid.
- Never commit your `.env` files to GitHub.
- Add `.env` to your `.gitignore`.

---

# 🛠️ Troubleshooting

### MongoDB Connection Error

- Verify your MongoDB URI.
- Ensure your IP address is whitelisted.
- Check that your database user credentials are correct.

### Cloudinary Errors

- Verify your Cloudinary Cloud Name, API Key, and API Secret.
- Restart the server after updating environment variables.

### Port Already in Use

Terminate the process using the port or change the server port in the `.env` file.

---

## 🌐 Live Demo

🔗 **Application:** https://quick-chat-client-woad.vercel.app/

# 📄 License

This project is licensed under the MIT License.