# SkillConnect 🎓

> **Find Skills. Share Knowledge.**  
> A platform connecting people who want to learn with people who can teach them.

---

## 🌐 Live Demo

🔗 https://skillconnect-app-rho.vercel.app/

---

## 💡 The Problem We Solve

Every day, thousands of people want to learn something — a new programming language, how to play piano, advanced math, design, physics — but don't know where to find someone who can actually teach them.

At the same time, experts and teachers struggle to reach students who need them.

**SkillConnect bridges that gap.**

Teachers post their profile with the skills they offer. Students browse, find the right teacher, and send a real lesson request — directly to their email — in seconds. No agencies. No fees. No barriers.

---

## ⚙️ How It Works

```
1. Sign Up → Choose your role: Teacher or Learner
2. Browse  → Teachers see students, Learners see teachers
3. Connect → View a teacher's profile and click "Request a Lesson"
4. Email   → A real email is sent to the teacher with your details
5. Learn   → The teacher replies and you get started!
```

### 📧 The Email Flow

When a student sends a lesson request, the teacher receives a real email like this:

```
Subject: [SkillConnect] New Lesson Request from Dana Green

Hi Jonathan! 👋

You got a new lesson request on SkillConnect:

👤 Student:  Dana Green
📧 Email:    dana@example.com
📌 Field:    Mathematics
📚 Topic:    Calculus — derivatives and integrals
💬 Message:  Hi! I saw your profile and I'd love to start lessons ASAP.

Reply to this email to connect!
— SkillConnect Team
```

No middleman. Teacher replies directly to the student.

---

## 🛠️ Built With

| Technology | Purpose |
|------------|---------|
| **HTML5** | Structure & layout |
| **CSS3** | Styling — glassmorphism, gradients, animations |
| **Vanilla JavaScript** | All logic, routing, state management |
| **localStorage** | User data persistence (no backend needed) |
| **EmailJS** | Real email delivery without a server |
| **Google Fonts** — Syne + DM Sans | Typography |

> ⚡ **Zero frameworks. Zero backend. Zero cost to host.**  
> The entire app is a single `.html` file.

---

## ✨ Features

- 🔐 **Auth system** — Register & login as Teacher or Learner
- 🔄 **Dual role support** — Same email can register as both Teacher and Learner
- 🔍 **Smart search** — Filter by name, field, or skill
- 👤 **User profiles** — Bio, skills, field, role badge
- 📩 **Lesson request form** — Sends a real email to the teacher via EmailJS
- ⭐ **Favorites** — Save teachers or students you like
- 🌙 **Dark / Light mode** — Remembers your preference
- 📱 **Fully responsive** — Works on mobile and desktop

---

## 🔒 Access Rules

| Role | Sees |
|------|------|
| 🎓 Teacher | Only students |
| 📚 Learner | Only teachers |
| 🚫 Not logged in | Nothing — must sign up first |

A teacher who also wants to learn can register with the same email in Learner mode and access the teacher directory.

---

## 💰 Future Monetization

This is currently **100% free** during beta. Future premium plans:

### 🔓 Free Plan (current)
- Browse teachers/students
- Send lesson requests
- Basic profile

### ⭐ Premium Teacher — *$9.99/month*
- **Promoted profile** — appear first in search results
- **"Active Today" badge** — students see you joined recently, not last week
- **Priority inbox** — lesson requests marked as urgent
- **Analytics dashboard** — see how many students viewed your profile

### 🚀 Premium Learner — *$4.99/month*
- **Filter by "Active Today"** — only see teachers who are currently active, not teachers who signed up months ago and disappeared
- **Save & compare** teachers side by side
- **Direct chat** — message teachers without email

> 💡 The key insight: students want to reach teachers who are **available now**, not profiles from 6 months ago. Premium gives them exactly that filter — see who joined or was active **today**.

---

## 🚀 Getting Started

### Run locally
Just open `skillconnect.html` in any browser. No installation needed.

### Deploy to Vercel (free)
1. Go to [vercel.com](https://vercel.com) → **New Project**
2. Drag & drop `skillconnect.html`
3. Done — get a live link in 30 seconds

### Deploy to Netlify (free)
1. Go to [netlify.com](https://netlify.com) → **Deploy manually**
2. Drag & drop the file
3. Done ✅

---

## 📁 Project Structure

```
skillconnect/
│
├── skillconnect.html     # Entire app — HTML + CSS + JS in one file
├── README.md             # This file
```

---

## 🗺️ Roadmap

- [ ] Backend integration (Node.js / Supabase)
- [ ] Real-time chat between teachers and students
- [ ] Lesson scheduling calendar
- [ ] Reviews & star ratings
- [ ] Payment processing for premium lessons
- [ ] Mobile app (React Native)

---

## 👩‍💻 Author

Built as a school project demonstrating full-stack thinking with frontend-only technologies.

**SkillConnect** — *because great teachers deserve to be found.*

---

*Made with ❤️ using HTML, CSS, JavaScript & EmailJS*
