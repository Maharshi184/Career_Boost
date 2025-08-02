
# 🚀 Career Boost

**Career Boost** is a full-featured **Job Finding Platform** designed to help job seekers find the right opportunities and connect with companies based on their preferences and qualifications. Built with the **MERN stack**, the platform provides a smooth, dynamic, and scalable job application experience.

---

## 🌟 Features

- 👤 **User Authentication**
  - Sign up and login functionality
  - Secure password handling

- 📄 **Profile Management**
  - Update user profile and resume
  - Store personal and professional information

- 🔍 **Job Search**
  - Search companies using filters like:
    - 💰 Salary / Compensation Range
    - 🏢 Company Name
    - 📍 Location (optional)

- 📝 **Job Applications**
  - Apply to jobs directly from the platform
  - Track applications

- 📈 **Admin/Company Panel** *(future enhancement)*
  - Post job listings
  - Manage applications

---

## 🛠️ Tech Stack

| Layer      | Technology                     |
|------------|--------------------------------|
| Frontend   | React.js, HTML, CSS, Tailwind  |
| Backend    | Node.js, Express.js            |
| Database   | MongoDB (via Mongoose)         |
| Auth       | JWT / bcrypt                   |

---

## 🗃️ MongoDB Collections

### 🔧 Installation Steps

#### 1. 📁  Clone the repository

```bash
git clone https://github.com/Maharshi184/Career_Boost
```
#### 2. Change into the frontend directory
```bash
cd client
```
#### 3. Install the frontend dependencies
```bash              
npm install
```
#### 4. Run the development frontend server:
```bash              
npm run dev
```
#### 5. Return to the main directory and change into the backend directory
```bash
cd ..                    # Return to the main directory
cd server 
```
#### 6. Install the backend dependencies:
```bash               # Change into the backend directory
npm install              # Install the backend dependencies
```
#### 7. Configure env file
```bash
cp config.env config.sample.env
```
#### 8. Open config.env file from config folder replace the following credentials
```bash 
DB = 
CLOUDINARY_NAME = 
CLOUDINARY_API_KEY =
CLOUDINARY_API_SECRET =
```
#### 9 Run the development backend server:
```bash
nodemon server.js
```


