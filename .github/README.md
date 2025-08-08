<h2 align="center"> 
Audify Music 🎧 + Management 
</h2>

---

<p align="center">
   <img src="https://files.catbox.moe/8drqda.jpg">
 </p>

<p align="center">
<a href="https://github.com/GrayBots/Audify/stargazers"><img src="https://img.shields.io/github/stars/GrayBots/Audify?color=black&logo=github&logoColor=black&style=for-the-badge" alt="Stars" /></a>
<a href="https://github.com/GrayBots/Audify/network/members"> <img src="https://img.shields.io/github/forks/GrayBots/Audify?color=black&logo=github&logoColor=black&style=for-the-badge" /></a>
<a href="https://github.com/GrayBots/Audify/blob/master/LICENSE"> <img src="https://img.shields.io/badge/License-MIT-blueviolet?style=for-the-badge" alt="License" /> </a>
<a href="https://www.python.org/"> <img src="https://img.shields.io/badge/Written%20in-Python-orange?style=for-the-badge&logo=python" alt="Python" /> </a>
<a href="https://github.com/GrayBots/Audify/commits/GrayBots"> <img src="https://img.shields.io/github/last-commit/GrayBots/Audify?color=blue&logo=github&logoColor=green&style=for-the-badge" /></a>
</p>

---

### 🛠 Fix for YouTube Blocking VPS IPs Try Our Cookies Method Below 👇

## **Using Cookies for Authentication**

### **Method: Netscape HTTP Cookie File**

To authenticate requests using cookies, follow these steps:

> ⚠️ **Note:** Use a **second account** for generating cookies. Once you create and upload the cookies, **do not open
the account again** until the cookies expire — reopening may invalidate the session early.

#### **1. Export Cookies in Netscape Format**

Use a browser extension to export cookies in the **Netscape HTTP Cookie File** format:

- **Chrome:** [Get cookies.txt (Chrome Extension)](https://chromewebstore.google.com/detail/get-cookiestxt-clean/ahmnmhfbokciafffnknlekllgcnafnie)
- **Firefox:** [Get cookies.txt (Firefox Add-on)](https://addons.mozilla.org/en-US/firefox/addon/cookies-txt/)

#### **2. Upload Cookies**

1. **Add Cookies**: Paste the generated cookies into the `cookies` folder in your forked repository.
2. **Deploy the Bot**: Continue with the

This process will allow you to bypass the YouTube restrictions and ensure smooth operation of the bot.

---

## 🎵 Using the API for Audio Streaming
If you do not want to deal with YouTube restrictions, you can rely on our API for audio streaming. The API allows you to fetch audio directly without needing cookies, making the process simpler and more reliable.

### How to Get an API Key
To use the API, you need an API key. Follow these steps to obtain one:

1. **DM on Telegram**: Contact the bot admin on Telegram at [Nickhil](https://t.me/Nickhiil) to request an API key.
2. **Free Plan**: New users can request **Free Plan** with a 1,000 song request limit to the API. Simply mention "I want a free Plan" in my DM, and I will provide a API key (Need to renew it monthly).
3. **Choose a Plan**: After the trial (or if you want a higher limit), select a plan based on your song request limit needs (all prices are in INR, on a **monthly basis**):
   - **5,000 Song Requests Daily**: ₹9/month
   - **10,000 Song Requests Daily**: ₹14/month
   - **15,000 Song Requests Daily**: ₹19/month
   - **20,000 Song Requests Daily**: ₹24/month
4. **Payment**: After selecting a plan, You will be provided payment details. Once the payment is confirmed, you will receive your API key via Telegram DM.
5. **Integrate the API Key**: Add the API key to your bot's configuration (refer to the setup instructions for details on where to add the key).

### Important Notes About API Usage
- **Daily Reset**: The song request limit resets daily at midnight (IST). For example, if you have a 5,000 song request limit, you can request up to 5,000 songs each day.
- **Audio Only**: The API provides audio streaming only. If you need video play support, you must add cookies as described in the section above.
- **Support**: If you face any issues with the API or need help with integration, join our [support group](https://t.me/GrayBotSupport) and ask for assistance.

---

## 🎧 Features

* 🎼 **Play Music** from YouTube, Spotify, and more.
* 📋 **Queue Manager** to control what's next.
* 🎚 **Volume Control** and audio enhancements.
* ⚒ **Admin Tools** like ban, mute, warn, etc.
* 🚫 **Anti-Spam** with advanced filtering.
* 📝 **Logging System** for admin actions.
* 🎨 **Custom Commands** and flexible configs.

---

### 🛠 Commands & Usage

The Audify Music Bot offers a range of commands to enhance your music listening experience on Telegram:

| Command        | Description                    |
| -------------- | ------------------------------ |
| `/play <song>` | Play a song instantly.         |
| `/pause`       | Pause the current track.       |
| `/resume`      | Resume paused playback.        |
| `/skip`        | Skip current song.             |
| `/stop`        | Clear queue and stop playback. |
| `/warn <user>` | Warns a member.                |
| `/ban <user>`  | Bans the mentioned user.       |
| `/mute <user>` | Mutes the user in group.       |
| `/log`         | Shows recent moderation logs.  |

For a full list of commands, use `/help` in [telegram](https://t.me/AudifyMusicBot).


<h3 align="center">
Deploy 🚀  

<h3 align="center">
Easiest Heroku Deploy 🤭  
</h3>

<p align="center">  
    <a href="https://heroku.com/deploy?template=https://github.com/ramavtarchauhan420/Mehak">  
    <img src="https://github.com/nacbots/broadcastbot/blob/main/herokudeploy-01.svg" alt="herokudeploy-01" border="0" height="90" width="285"></a>  
</p>  

---

<h3 align="center">
Host Locally 🤕
</h3>

- Get your [Necessary Variables](https://github.com/GrayBots/Audify/blob/main/sample.env)

## ⚙️ Setup Guide

1. **Update Your System:**
```sh
   sudo apt-get update && sudo apt-get upgrade -y
   ```
2. **Install Required Packages:**
```sh
   sudo apt-get install python3-pip ffmpeg -y
   ```
3. **Install pip:**
```sh
   sudo pip3 install -U pip
   ```
4. **Install Node.js:**
```sh
   curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash && source ~/.bashrc && nvm install v18
   ```  
5. **Clone Repo:**
```sh
   git clone https://github.com/GrayBots/Audify && cd Audify
   ``` 
6. **Install Python Requirements:**
```sh
   pip3 install -U -r requirements.txt
   ``` 
7. **Configure Environment:**
```sh
   vi sample.env
   ``` 
Press `I` on the keyboard for editing env<br>

Press `Ctrl+C` when you're done with editing env and `:wq` to save the env<br>

8. **Rename .env File:**
```sh
   mv sample.env .env
   ```
9. **Use Tmux for Persistent Session:**
```sh
   sudo apt install tmux && tmux
   ``` 
10. **Finally Run the Bot:**
```sh
   bash start
   ``` 
11. **Detach from Tmux:** Press `Ctrl+b` and then `d`<br>

---

<h3 align="center">
Support Group
</h3>

<p align="center">
<a href="https://t.me/GrayBots"><img src="https://img.shields.io/badge/Telegram-Updates%20Channel-blue.svg?logo=telegram"></a>  
<a href="https://t.me/GrayBotSupport"><img src="https://img.shields.io/badge/Telegram-Support%20Group-blue.svg?logo=telegram"></a>
</p>

---

### 🤝 Contributing

Found a Bug ? 🐛 

We welcome contributions to the Audify Music Bot project. If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch with a meaningful name.
3. Make your changes and commit them with a descriptive commit message.
4. Open a pull request against our `main` branch.
5. Our team will review your changes and provide feedback.

For more details, reach out us on telegram.

---

## 💡 About Audify

Audify is your all-in-one Telegram music and management bot. Seamlessly integrates music streaming with group moderation tools to help admins maintain order while users enjoy high-quality music from multiple sources.

### 📜 License

This project is licensed under the MIT License. For more details, see the [LICENSE](https://github.com/GrayBots/Audify/blob/main/LICENSE) file.

---

## Credits  

- [Yukki Music](https://github.com/TeamYukki/YukkiMusicBot) & [TgMusicBot](https://github.com/AshokShau/TgMusicBot) & [AviaxMusic](https://github.com/CyberPixelPro/AviaxMusic) & [AnonXMusic](https://github.com/AnonymousX1025/AnonXMusic) For their Source Codes.

---

## Dev 🚀

- [Nickhil](https://t.me/Nickhiil)

---

## Bot 🎧

- [Audify Music Bot](https://t.me/AudifyMusicBot)
