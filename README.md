# StudyNation (Frontend)

StudyNation is a full-stack EdTech platform I built where anyone can either **learn** by enrolling in courses, or **teach** by creating and selling their own. Think of it as a mini Udemy — students can browse a catalog, add courses to their cart, pay securely, and track their progress, while instructors get their own dashboard to build courses, upload video lectures, and see how their courses are performing.

This repo contains the **frontend (React)**. The backend/API lives in a separate repo: **[StudyNation Backend](https://github.com/your-username/studynation-backend)** — you'll need it running for this app to actually work.

**Made by [Ashadullah Haneef]((https://github.com/Ashadullahhaneef/StudyNation-Frontend))**

---

## What can you actually do on it?

**As a Student**
- Sign up / log in with email OTP verification
- Browse courses by category, view detailed course pages, ratings & reviews
- Add courses to cart and pay securely via Razorpay
- Access enrolled courses and track your progress lecture by lecture
- Edit your profile, change your password, or delete your account

**As an Instructor**
- Create courses with sections and sub-sections (a proper course builder, step by step)
- Upload course thumbnails and video lectures
- Publish/unpublish courses
- View a dashboard with stats and a chart of how your courses are doing

**General**
- Forgot password / reset password via email
- Contact Us page
- Fully responsive UI

---

## Tech Stack

- React (Create React App)
- Redux Toolkit for state management
- Tailwind CSS for styling
- React Router, React Hook Form, React Hot Toast, Swiper, and a few other handy libraries

---


## Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/ashadullahhaneef/studynation-frontend.git
cd studynation-frontend
```

### 2. Install dependencies
```bash
npm install
```

### 3. Set up environment variables
Create a `.env` file in the root with:
```env
REACT_APP_BASE_URL=(https://studynation-eso8.onrender.com/api/v1)
```
(This should point to wherever your **backend** is running — see the [backend repo](https://github.com/your-username/studynation-backend) for setup.)

### 4. Run the app
```bash
npm start
```

The app should now be running at `https://study_nation_frontend.vercel.app` 

>  Make sure the backend server is up and running first, otherwise features like login, courses, and payments won't work.

---

## Why I built this

I wanted a project that wasn't just a to-do list clone — something with real-world complexity: authentication flows, file uploads, payments, role-based access, and a proper course-builder UX. This project pushed me to work with Redux Toolkit at scale and build a UI that actually talks to a real backend and third-party services.

---

## Feedback

If you spot a bug, have a suggestion, or just want to say hi — feel free to open an issue or reach out. Always happy to improve this further!
