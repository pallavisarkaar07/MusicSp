## 🚀 𝑫𝒆𝒑𝒍𝒐𝒚𝒎𝒆𝒏𝒕 𝑴𝒆𝒕𝒉𝒐𝒅𝒔

### 🟣 𝑶𝒏𝒆-𝑪𝒍𝒊𝒄𝒌 𝑯𝒆𝒓𝒐𝒌𝒖 𝑫𝒆𝒑𝒍𝒐𝒚𝒎𝒆𝒏𝒕

<p align="center">
  <a href="https://dashboard.heroku.com/new?template=https://github.com/pallavisarkaar07/MusicSp">
    <img src="https://img.shields.io/badge/Deploy%20On%20Heroku-7928CA?style=for-the-badge&logo=heroku&logoColor=white" alt="Deploy on Heroku Badge">
  </a>
  <br><br>
  <a href="https://dashboard.heroku.com/new?template=https://github.com/pallavisarkaar07/MusicSp">
    <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy to Heroku Button">
  </a>
</p>

---

### 🚀 𝑽𝑷𝑺 𝑫𝒆𝒑𝒍𝒐𝒚𝒎𝒆𝒏𝒕

<details>
<summary align="center">
  <b><font color="#1E90FF" size="3">⚡ 𝑽𝒊𝒆𝒘 𝑽𝑷𝑺 𝑫𝒆𝒑𝒍𝒐𝒚𝒎𝒆𝒏𝒕 𝑪𝒐𝒎𝒎𝒂𝒏𝒅𝒔 (Click Here) ⚡</font></b>
</summary>
<br>

#### 🔹 𝑺𝒕𝒆𝒑 𝟏: 𝑼𝒑𝒅𝒂𝒕𝒆 & 𝑼𝒑𝒈𝒓𝒂𝒅𝒆 𝑺𝒚𝒔𝒕𝒆𝒎
```bash
sudo apt-get update && sudo apt-get upgrade -y
```

#### 🔹 𝑺𝒕𝒆𝒑 𝟐: 𝑪𝒍𝒐𝒏𝒆 𝑴𝒖𝒔𝒊𝒄𝑺𝒑 𝑹𝒆𝒑𝒐𝒔𝒊𝒕𝒐𝒓𝒚
```bash
git clone https://github.com/DevloperSP/MusicSp
```

#### 🔹 𝑺𝒕𝒆𝒑 𝟑: 𝑬𝒏𝒕𝒆𝒓 𝑹𝒆𝒑𝒐𝒔𝒊𝒕𝒐𝒓𝒚 𝑫𝒊𝒓𝒆𝒄𝒕𝒐𝒓𝒚
```bash
cd MusicSp
```

#### 🔹 𝑺𝒕𝒆𝒑 𝟒: 𝑹𝒖𝒏 𝑨𝒖𝒕𝒐𝒎𝒂𝒕𝒆𝒅 𝑺𝒆𝒕𝒖𝒑 𝑰𝒏𝒔𝒕𝒂𝒍𝒍𝒆𝒓
```bash
bash setup
```

#### 🔹 𝑺𝒕𝒆𝒑 𝟓: 𝑪𝒐𝒏𝒇𝒊𝒈𝒖𝒓𝒆 𝑬𝒏𝒗𝒊𝒓𝒐𝒏𝒎𝒆𝒏𝒕 𝑽𝒂𝒓𝒊𝒂𝒃𝒍𝒆𝒔
```bash
cp sample.env .env && vi .env
```

#### 🔹 𝑺𝒕𝒆𝒑 𝟔: 𝑺𝒕𝒂𝒓𝒕 𝑴𝒖𝒔𝒊𝒄𝑺𝒑 𝑩𝒐𝒕
```bash
bash start
```

</details>

---

### 🛠️ 𝑴𝒐𝒓𝒆 𝑫𝒆𝒑𝒍𝒐𝒚𝒎𝒆𝒏𝒕 𝑶𝒑𝒕𝒊𝒐𝒏𝒔 (Click to Expand)

<details>
<summary><b>🐳 𝑫𝒐𝒄𝒌𝒆𝒓 𝑪𝒐𝒏𝒕𝒂𝒊𝒏𝒆𝒓 𝑫𝒆𝒑𝒍𝒐𝒚𝒎𝒆𝒏𝒕</b></summary>
<br>

Deploy with containerization using the pre-configured [`Dockerfile`](Dockerfile):

```bash
# 1. Clone repository
git clone https://github.com/DevloperSP/MusicSp
cd MusicSp

# 2. Setup environment variables
cp sample.env .env
vi .env

# 3. Build Docker container image
docker build -t musicsp .

# 4. Run Docker container in detached mode
docker run -d --name musicsp_bot --env-file .env musicsp
```

</details>

<details>
<summary><b>💻 𝑴𝒂𝒏𝒖𝒂𝒍 𝑳𝒐𝒄𝒂𝒍 / 𝑫𝒆𝒗𝒆𝒍𝒐𝒑𝒎𝒆𝒏𝒕 𝑺𝒆𝒕𝒖𝒑</b></summary>
<br>

For local development and testing:

```bash
# 1. Clone repository
git clone https://github.com/DevloperSP/MusicSp && cd MusicSp

# 2. Create and activate virtual environment
python3 -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate

# 3. Install dependencies
pip install -U pip
pip install -U -r requirements.txt

# 4. Configure .env and run
cp sample.env .env
python3 -m MusicSp
```

</details>

---

## ⚙️ 𝑬𝒏𝒗𝒊𝒓𝒐𝒏𝒎𝒆𝒏𝒕 𝑽𝒂𝒓𝒊𝒂𝒃𝒍𝒆𝒔 (𝑪𝒐𝒏𝒇𝒊𝒈𝒖𝒓𝒂𝒕𝒊𝒐𝒏)

<details>
<summary><b>📋 𝑽𝒊𝒆𝒘 𝑭𝒖𝒍𝒍 𝑬𝒏𝒗𝒊𝒓𝒐𝒏𝒎𝒆𝒏𝒕 𝑽𝒂𝒓𝒊𝒂𝒃𝒍𝒆𝒔 𝑻𝒂𝒃𝒍𝒆</b></summary>
<br>

| Variable | Required | Default | Description |
| :--- | :---: | :---: | :--- |
| `API_ID` | **Yes** | — | Telegram API ID from [my.telegram.org](https://my.telegram.org). |
| `API_HASH` | **Yes** | — | Telegram API Hash from [my.telegram.org](https://my.telegram.org). |
| `BOT_TOKEN` | **Yes** | — | Telegram Bot Token from [@BotFather](https://t.me/BotFather). |
| `OWNER_ID` | **Yes** | — | Telegram numeric ID of the bot owner. |
| `MONGO_DB_URI` | **Yes** | — | MongoDB Atlas connection URI string. |
| `LOG_GROUP_ID` | **Yes** | — | Telegram Private Group ID for logging (e.g., `-100xxxxxxx`). |
| `STRING_SESSION` | **Yes** | — | Pyrogram v2 / Kurigram String Session for Assistant 1. |
| `STRING_SESSION2` - `5` | Optional | `None` | Multi-assistant string sessions for load balancing. |
| `SPOTIFY_CLIENT_ID` | Optional | `None` | Spotify Developer API Client ID. |
| `SPOTIFY_CLIENT_SECRET`| Optional | `None` | Spotify Developer API Client Secret. |
| `API_URL` | Optional | `None` | Custom YouTube audio extraction API URL. |
| `API_KEY` | Optional | `None` | Authentication Key for custom YouTube API. |
| `DURATION_LIMIT` | Optional | `1700` | Maximum song duration limit in minutes. |
| `AUTO_LEAVING_ASSISTANT`| Optional | `False` | Auto-leave voice chat assistant when call terminates. |

</details>

---

## 🏗️ 𝑺𝒚𝒔𝒕𝒆𝒎 𝑨𝒓𝒄𝒉𝒊𝒕𝒆𝒄𝒕𝒖𝒓𝒆

```mermaid
graph LR
    User([👤 Telegram User / Group]) -->|Commands / Play Request| Bot[🤖 MusicSp Bot Core]
    Bot -->|Async Query| DB[(🗄️ MongoDB Atlas)]
    Bot -->|Metadata Search| Fetcher[📡 YouTube / Spotify / Apple]
    Bot -->|Stream Dispatch| VC[🔊 PyTgCalls WebRTC Engine]
    VC -->|Audio & Video Feed| Call([🎙️ Group Voice Chat / Video Call])
    Assistant[👥 Assistant Userbot] -->|Active Call Participant| Call
```

---

## 🤝 𝑪𝒐𝒏𝒕𝒓𝒊𝒃𝒖𝒕𝒊𝒐𝒏 & 𝑳𝒊𝒄𝒆𝒏𝒔𝒆

Contributions are welcome! Follow these steps:
1. 🍴 **Fork the Repository** to your GitHub account.
2. 🌿 **Create a Feature Branch**: `git checkout -b feature/cool-feature`
3. ✍️ **Commit Changes**: `git commit -m 'Add cool feature'`
4. 🚀 **Push Branch**: `git push origin feature/cool-feature`
5. 📬 **Submit a Pull Request** to our `main` branch.

<p align="center">
  <a href="https://github.com/DevloperSP/MusicSp/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/License-GNU%20AGPL%20v3.0-10B981?style=for-the-badge&logo=gnu&logoColor=white" alt="AGPL v3.0 License">
  </a>
  <a href="https://github.com/DevloperSP">
    <img src="https://img.shields.io/badge/Developer%20Sparrow-DevloperSP-7928CA?style=for-the-badge&logo=github&logoColor=white" alt="Developer Sparrow">
  </a>
</p>

---

## 💬 𝑪𝒐𝒎𝒎𝒖𝒏𝒊𝒕𝒚 & 𝑺𝒖𝒑𝒑𝒐𝒓𝒕

<p align="center">
  <a href="https://t.me/Mecobots">
    <img src="https://img.shields.io/badge/Join-Developer%20Home-2563EB?style=for-the-badge&logo=telegram&logoColor=white" alt="Developer Home">
  </a>
  <a href="https://t.me/Spparow_92">
    <img src="https://img.shields.io/badge/Contact%20Owner-%40Spparow__92-0088cc?style=for-the-badge&logo=telegram&logoColor=white" alt="Contact Owner">
  </a>
  <a href="https://t.me/MusicSp1_bot">
    <img src="https://img.shields.io/badge/Demo%20Bot-%40MusicSp1__bot-06B6D4?style=for-the-badge&logo=telegram&logoColor=white" alt="Demo Bot">
  </a>
</p>

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=17&duration=3800&pause=1000&color=00F2FE&center=true&vCenter=true&width=850&lines=%E2%9C%A8+MusicSp+%E2%80%94+Crafted+with+excellence+for+Telegram+voice+%26+video+streaming+communities.;%E2%9A%A1+Fast%2C+Reliable+%26+Secure+%E2%80%94+Join+our+community+%40Mecobots!;%F0%9F%9A%80+Powered+by+Developer+Sparrow+Engine+%E2%80%A2+24%2F7+Lossless+Streaming!">
</div>
