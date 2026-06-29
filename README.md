# 👨‍💻 Edrich Josh Mabalot — Personal Portfolio

> A full-stack personal portfolio website showcasing my skills, experience, and certifications as a Software Engineer — featuring a working contact form powered by a Vercel backend and Supabase database.

🌐 **Live Site:** [https://my-profile-tau-gray.vercel.app](https://my-profile-tau-gray.vercel.app)

---

## 📖 About

This personal portfolio was developed as part of an academic requirement to demonstrate proficiency in:
- Version control using **Git** and **GitHub**
- Deployment via **Vercel**
- Full-stack web development (frontend + backend API)
- Database integration with **Supabase (PostgreSQL)**
- Use of **AI tools** for design and content assistance

---

## 🎯 Features

- ✅ Responsive design (mobile, tablet, desktop)
- ✅ Professional profile section with bio
- ✅ Skills showcase (Technical & Soft Skills)
- ✅ Work experience timeline
- ✅ Certifications display (TESDA NC II, SFPC)
- ✅ Dynamic Tech Stack section with live search filter
- ✅ **Working contact form** — saves messages to a Supabase database via a Vercel serverless API
- ✅ Clean, modern navy-blue theme with smooth scroll animations

---

## 🛠️ Built With

| Tool | Purpose |
|------|---------|
| **HTML5** | Page structure |
| **CSS3** | Styling and responsive design |
| **JavaScript** | Interactivity & dynamic content |
| **Node.js** | Serverless backend runtime |
| **Vercel** | Hosting + serverless API functions |
| **Supabase** | PostgreSQL database for contact messages |
| **Git & GitHub** | Version control |
| **AI Tools** | Content & design assistance (ChatGPT/Claude) |

---

## 📂 Project Structure

\`\`\`
MyProfile/
├── index.html          # Main portfolio page (HTML, CSS, JS)
├── api/
│   └── messages.js     # Vercel serverless API (Supabase integration)
├── profile.jpg         # Profile picture
├── .gitignore          # Ignored files (env, node_modules, etc.)
└── README.md           # Project documentation
\`\`\`

---

## 🚀 Getting Started

### View Online
Visit: [https://my-profile-tau-gray.vercel.app](https://my-profile-tau-gray.vercel.app)

### Run Locally
\`\`\`bash
# Clone the repository
git clone https://github.com/Edrixxxxx/MyProfile.git

# Navigate to the folder
cd MyProfile

# Open in browser
open index.html
\`\`\`

> ⚠️ The contact form requires environment variables (`SUPABASE_URL` and `SUPABASE_ANON_KEY`) configured in Vercel to function.

---

## 🔧 Backend & Database

The contact form sends messages to a **Vercel serverless function** (`/api/messages`), which securely inserts the data into a **Supabase PostgreSQL** database. Row Level Security (RLS) is enabled to protect the data.

---

## 👤 Author

**Edrich Josh Mabalot**
- 📍 Aringay, La Union
- 📧 ejmabalot23102013@student.dmmmsu.edu.ph
- 📱 09293785889
- 🐙 [GitHub](https://github.com/Edrixxxxx)

---

## 🏆 Certifications

- TESDA National Certificate II (NC II) – Computer Systems Servicing
- Open Test Scrum Foundation Professional Certification (SFPC™) – CertiProf
- Civil Service Passer

---

## 📜 License

This project is created for educational purposes as part of a class requirement.

---

⭐ *Developed with assistance from AI tools as per assignment requirements.*



Prompt:

Give me a complete step-by-step terminal command guide to:

Initialize a Git repository in my project folder
Create a .gitignore for a static HTML/CSS/JS project
Make my first commit with a meaningful message
Create a new GitHub repository named "MyProfile" via command line
(using GitHub CLI 'gh') OR explain manual creation
Connect my local repo to GitHub remote
Push my code to the main branch
Enable GitHub Pages from the main branch
Show me the final live URL format
Also include best-practice commit message examples following
Conventional Commits (feat:, fix:, docs:, style:).
