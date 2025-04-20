
# 🏋️‍♂️ FitnessTrack Project Setup

## 📋 Prerequisites

- Node.js installed on your system
- MongoDB connection string

---

## ⚙️ Setting Up the Server

1. **Navigate to the server directory:**
   ```bash
   cd server
   ```

2. **Create a `.env` file** inside the `server` directory and add the following:
   ```env
MONGODB_URL=mongodb+srv://vedantutekar1405:4VCgZVK7G3Myzypz@cluster0.5aozt.mongodb.net/fitness


JWT = 2814eac3e3abfde5366148042bfa9a8dff0cfdf59d25b234c6b3ce1135cf6727
   ```
   > Replace `<your_mongodb_connection_string>` with your actual MongoDB URI and `<your_jwt_secret_key>` with a secure secret key.

3. **Install server dependencies:**
   ```bash
   npm install
   ```

4. **Start the server:**
   ```bash
   npm start
   ```

---

## 💻 Setting Up the Client

1. **Navigate to the `client` directory:**
   ```bash
   cd client
   ```

2. **Install client dependencies:**
   ```bash
   npm install
   ```

3. **Start the client:**
   ```bash
   npm start
   ```

---

## 🚀 Running the Application

- Ensure **both the server and client are running** simultaneously.
- Open your browser and navigate to [http://localhost:3000](http://localhost:3000) to access the app.

---

## ⚠️ Notes

- The server runs on port **8080** by default. Make sure this port is free.
- The client runs on port **3000** by default.
- **Never share your `.env` file** or its contents publicly, as it contains sensitive information.

