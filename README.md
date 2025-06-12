# 🌟 Daily Motivation Quote API

This project delivers motivational quotes through a simple API. It includes user registration, daily usage limits, email notifications, and an admin dashboard. It’s perfect for developers, content creators, or apps that want to show daily inspirational content.

---

## 🚀 Live Demo

- 🔗 **Landing Page:** [https://your-netlify-site.netlify.app](https://your-netlify-site.netlify.app)
- 🔗 **Live API URL:** [https://d530b6d0-22f6-441c-a13e-2f316b3e390c-00-j7hnx5gjbvzt.riker.replit.dev](https://d530b6d0-22f6-441c-a13e-2f316b3e390c-00-j7hnx5gjbvzt.riker.replit.dev)

---

## 🔧 Features

- 📬 **User Registration & Login** with email verification  
- 🔐 **API Key Management** – secure, unique keys for each user  
- 📈 **Quote Limit Tracking** – up to 10 quotes per day per user  
- 📤 **Daily Usage Email Reports** to admin  
- 🛠️ **Admin Dashboard** to view users and logs  
- 🌐 **CORS-enabled** for frontend use

---

## 📦 Tech Stack

- **Backend:** Python Flask, SQLite, SQLAlchemy  
- **Email:** Flask-Mail (Gmail App Password)  
- **Frontend:** HTML, CSS, JavaScript  
- **Deployment:** Replit (API) + Netlify (Landing Page)  
- **Version Control:** GitHub

---

## 📋 API Endpoints

| Endpoint       | Method | Description                         |
|----------------|--------|-------------------------------------|
| `/register`    | POST   | Register new user                   |
| `/login`       | POST   | Login to get API key                |
| `/rotate-key`  | POST   | Rotate your API key                 |
| `/quote`       | GET    | Get a daily quote (API key required)|
| `/admin`       | GET    | Admin dashboard                     |
| `/send-report` | GET    | Send daily usage report to admin    |

---

## 🔐 Example `fetch` Usage

```js
fetch('https://d530b6d0-22f6-441c-a13e-2f316b3e390c-00-j7hnx5gjbvzt.riker.replit.dev/quote', {
  headers: {
    'x-api-key': 'your-api-key-here'
  }
})
.then(res => res.json())
.then(data => console.log(data));


🧠 Business Use Case
This Quote API can be used in:

Mobile apps

Web apps

Daily newsletter services

Mental health and wellness platforms

Content automation bots (Telegram, WhatsApp, Discord, etc.)

🙌 Contributing
Want to improve this project? Open an issue or fork the repo and submit a pull request.

📫 Contact
Made with ❤️ by Andrew Yamba
📧 Email: apikey1992@gmail.com
🌍 Location: Sierra Leone

📝 License
This project is licensed under the MIT License.

 






