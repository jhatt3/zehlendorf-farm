# Zehlendorf Farm – Pastured Pork & Poultry

Welcome to the official website for **Zehlendorf Farm**, a family-owned farm specializing in humanely raised, pastured pork and poultry in the heart of Tennessee.

🌱 Website: [pasturedporkandpoultry.com](https://pasturedporkandpoultry.com)  
📍 Location: Limestone, TN  
📦 Order: Whole chicken, sausage, bacon, and more  
📬 Contact: Direct from the website

---

## 🚀 Live Preview

🖥️ Coming soon to [Netlify](https://netlify.com) or [Vercel](https://vercel.com)

---

## 📸 Preview

![Zehlendorf Farm Landing Page](./public/screenshot.jpg) <!-- Add a screenshot if available -->

---

## 🛠 Tech Stack

- [React](https://reactjs.org/)
- [React Router](https://reactrouter.com/)
- [Tailwind CSS](https://tailwindcss.com/)
- EmailJS (optional for contact form)

---

## 📂 Project Structure

zehlendorf-farm/
├── public/
│ └── index.html
├── src/
│ ├── components/
│ │ └── Navbar.jsx
│ ├── pages/
│ │ ├── Home.jsx
│ │ ├── Contact.jsx
│ │ └── Order.jsx
│ ├── App.jsx
│ ├── main.jsx
│ └── index.css
├── tailwind.config.js
├── README.md
└── package.json

yaml
Copy code



---

## 📦 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/zehlendorf-farm.git
cd zehlendorf-farm

npm install

npm run dev

To enable form submission to email:

Create an account on EmailJS

Set up a service, template, and get a user_id

Replace form handlers in Contact.jsx and Order.jsx with emailjs.send(...)


