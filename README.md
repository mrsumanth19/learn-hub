# 📚 LearnHub – Online Learning Platform

**LearnHub** is a full-stack online learning platform built using the **MERN** stack (MongoDB, Express.js, React.js, Node.js). It provides a powerful interface for students to learn, teachers to create and manage courses, and admins to oversee platform activity.

🔗 **Live Demo**: [Coming Soon]

---

## 🚀 Features

### 👨‍🎓 Students
- Register and log in
- Browse and enroll in courses
- Track progress and resume learning
- Download completion certificates

### 👨‍🏫 Teachers
- Create and manage courses
- Add sections and content
- Monitor enrolled students

### 🛡️ Admin
- Oversee all platform activity
- Manage users and content

---

## 🧰 Tech Stack

| Layer       | Technology                            |
|-------------|----------------------------------------|
| Frontend    | React, Vite, Axios, Bootstrap, Material UI |
| Backend     | Node.js, Express.js                   |
| Database    | MongoDB (via Mongoose)                |
| Auth        | JWT, bcryptjs                         |
| Dev Tools   | dotenv, CORS, Multer                  |

---

## 📁 Project Structure

```

learn-hub/
├── backend/
│   ├── models/
│   ├── routes/
│   ├── .env
│   └── index.js
├── frontend/
│   ├── src/
│   └── index.html

````

---

## 🔧 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/mrsumanth19/learn-hub.git
cd learn-hub
````

---

### 2. Setup Backend

```bash
cd backend
npm install
```

Create a `.env` file:

```env
MONGO_URI=mongodb://localhost:27017/olp
JWT_SECRET=your_jwt_secret_key
```

Start the backend server:

```bash
node index.js
```

---

### 3. Setup Frontend

```bash
cd ../frontend
npm install
npm run dev
```

Frontend runs at: [http://localhost:5173](http://localhost:5173)

---

## 📸 Screenshots

> Add screenshots here like Landing Page, Dashboard, Course List, etc.
![Screenshot 2025-06-25 135439](https://github.com/user-attachments/assets/846806ec-3879-4d1b-a082-b6746d0ed486)
![Screenshot 2025-06-25 135356](https://github.com/user-attachments/assets/6c379c01-ee04-483d-b403-0320b4e91f22)
![Screenshot 2025-06-25 135318](https://github.com/user-attachments/assets/a14eb3f9-d4be-41ed-973d-be9859f938e2)
> ![Screenshot 2025-06-25 140200](https://github.com/user-attachments/assets/a8e30a41-1353-46fa-bcf7-fe42113ea929)
![Screenshot 2025-06-25 140237](https://github.com/user-attachments/assets/3d6afcff-a9ca-499e-8519-dfc094936ab2)
![Screenshot 2025-06-25 135949](https://github.com/user-attachments/assets/18bca558-cbf4-4948-83fc-400f7c733304)


---

## 🛠 Future Improvements

* 🎓 Dashboard UI for students/teachers/admin
* 💳 Payment gateway integration
* 🧾 Certificate generation (PDF)
* ⭐ Course ratings and reviews
* 📅 Live class scheduling

---

## 📜 License

This project is licensed under the [MIT License](LICENSE)

---

## 🙌 👥 Contributors

Feel free to fork this repo, submit issues, or open pull requests!
Made with ❤️ by 

| Name                    | GitHub Profile |
|-------------------------|----------------|
| Sumanth Vanapalli       | [@mrsumanth19](https://github.com/mrsumanth19) |
| Surekha Pamulapati      | [@surekhapamulapati](https://github.com/surekhapamulapati) |
| Mallikharjuna Madamanchi| [@mallikharjuna007](https://github.com/mallikharjuna007) |

