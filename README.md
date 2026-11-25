<div align="center">

<!-- Banner or Logo -->
<img src="https://raw.githubusercontent.com/NjabuloJf/njabulo-data/main/njabuloimg/njabuloimg.png" alt="Njabulo API Hub" width="200" style="border-radius: 50%;" />

# 🚀 Njabulo API Hub

**A powerful, free, and lightning-fast RESTful API ecosystem built for modern solutions.**

[![Vercel Deployment](https://img.shields.io/badge/Deployed_on-Vercel-black?style=for-the-badge&logo=vercel)](https://njabulo-ai.vercel.app/apis)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org)
[![Next.js](https://img.shields.io/badge/Next.js-black?style=for-the-badge&logo=nextdotjs&logoColor=white)](https://nextjs.org)
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](https://choosealicense.com/licenses/mit/)

<p align="center">
  <a href="https://njabulo-ai.vercel.app/apis">🌐 Live Dashboard</a> •
  <a href="https://github.com/NjabuloJf">GitHub Profile</a> •
  <a href="https://wa.me/26777821911">WhatsApp Bot</a>
</p>

</div>

---

## 📖 About The Project

Welcome to the **Njabulo API Hub**! This repository contains a collection of fast, reliable, and completely **free** APIs designed for developers, bots, and web applications. Whether you need AI integrations, media downloaders, or search tools, this hub has everything you need with zero setup.

> *"Built for developers, by developers. Free forever."*

---

## ✨ Amazing Features

Dive into our rich ecosystem of APIs. Here is what you can integrate right now:

| Feature | Description |
| :--- | :--- |
| 🤖 **AI Chat & Assistants** | Powerful AI endpoints for chatting, answering questions, and generating text using modern LLMs. |
| 🔍 **Google & Image Search** | Search the web, find high-quality images, and scrape results instantly. |
| 🎵 **YouTube Downloads** | Download YouTube videos (MP4) and audio (MP3) at high speeds with direct links. |
| 🎬 **Social Media Downloaders** | Fetch media from TikTok, Facebook, Instagram, and more (Coming Soon). |
| 📱 **APK Downloader** | Search and download your favorite Android applications seamlessly. |
| 📝 **Lyrics Finder** | Get full song lyrics for any track in seconds. |
| 🔐 **Pairing System** | Generate WhatsApp pairing codes easily to connect your bots. |
| 🚥 **Live Status Monitor** | Interactive dashboard showing real-time API health (Online/Offline traffic lights). |

---

## 🛠️ API Endpoints

All endpoints use a simple `GET` request with a `?q=` or `?url=` query parameter.

| API Name | Endpoint | Example Usage |
| :--- | :--- | :--- |
| **AI Chat** | `/api/ai` | `https://njabulo-ai.vercel.app/api/ai?q=Hello` |
| **YouTube MP3** | `/api/ytmp3` | `https://njabulo-ai.vercel.app/api/ytmp3?q=YOUTUBE_URL` |
| **YouTube MP4** | `/api/ytmp4` | `https://njabulo-ai.vercel.app/api/ytmp4?q=YOUTUBE_URL` |
| **YouTube Search** | `/api/yts` | `https://njabulo-ai.vercel.app/api/yts?q=Faded` |
| **Image Search** | `/api/image` | `https://njabulo-ai.vercel.app/api/image?q=Naruto` |
| **APK Search** | `/api/apk` | `https://njabulo-ai.vercel.app/api/apk?q=whatsapp` |
| **Lyrics** | `/api/lyrics` | `https://njabulo-ai.vercel.app/api/lyrics?q=Faded` |
| **Shazam Info** | `/api/shazam` | `https://njabulo-ai.vercel.app/api/shazam?q=Faded` |

---

## 🤝 Join The Community!

I love building open-source projects, and **everyone is welcome to join, contribute, and explore all my repositories!** 

Whether you are a developer looking to use the APIs, or someone who wants to learn how to build bots like **Njabulo-Jb**, you are in the right place.

<div align="center">

### 🌐 Connect With Me
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/26777821911)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/NjabuloJf)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@Njabulo-JBOffice)
[![Facebook](https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://www.facebook.com/profile.php?id=100094314013209)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/njabulojb871)

<br>

**Join my WhatsApp Channel for updates and new API releases!**
<br><br>
<a href="https://whatsapp.com/channel/0029VbC9yTmElah0BO3KD509">
  <img src="https://img.shields.io/badge/Join_WhatsApp_Channel-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="Join Channel" />
</a>

</div>

---

## 🚀 How to Use (For Developers)

You can easily call these APIs from any programming language. Here is a simple example using JavaScript:

```javascript
// Example: Fetching an AI response
fetch('https://njabulo-ai.vercel.app/api/ai?q=What%20is%20Njabulo%20API')
  .then(response => response.json())
  .then(data => console.log(data.result))
  .catch(error => console.error(error));
