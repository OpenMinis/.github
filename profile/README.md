<div align="center">

<img src="https://raw.githubusercontent.com/OpenMinis/openminis.github.io/main/icon-light.png" width="96" alt="Open Minis" />

# Open Minis

**Your Private On-Device AI Agent**

An on-device AI agent that goes beyond chat. It takes action — browsing the web, accessing your health data, managing your schedule, controlling your smart home, and automating complex tasks. All privately on your device.

[![App Store](https://img.shields.io/badge/App_Store-Download-black?logo=apple&logoColor=white&style=flat-square)](https://apps.apple.com/app/id6759188481)
[![Android](https://img.shields.io/badge/Android-Preview-3DDC84?logo=android&logoColor=white&style=flat-square)](https://github.com/OpenMinis/OpenMinis/releases)
[![Telegram](https://img.shields.io/badge/Community-Telegram-2CA5E0?logo=telegram&logoColor=white&style=flat-square)](https://t.me/openminis)
[![Website](https://img.shields.io/badge/Website-openminis.app-FF6B35?style=flat-square)](https://openminis.app)

</div>

---

## 🚀 Core Repositories

| Repository | Description | Stars |
|---|---|---|
| [**OpenMinis**](https://github.com/OpenMinis/OpenMinis) | Main app repository — AI Agent for iOS, iPadOS, macOS & Android. Open source coming soon. | [![Stars](https://img.shields.io/github/stars/OpenMinis/OpenMinis?style=flat-square&color=gold&label=stars)](https://github.com/OpenMinis/OpenMinis/stargazers) |
| [**MinisSkills**](https://github.com/OpenMinis/MinisSkills) | Official skills collection — reusable `SKILL.md` instruction sets that extend the agent with specialized workflows. | [![Stars](https://img.shields.io/github/stars/OpenMinis/MinisSkills?style=flat-square&color=gold&label=stars)](https://github.com/OpenMinis/MinisSkills/stargazers) |
| [**AwesomeMinis**](https://github.com/OpenMinis/AwesomeMinis) | Community-curated real-world use cases, workflows, and creative scenarios built with Minis. | [![Stars](https://img.shields.io/github/stars/OpenMinis/AwesomeMinis?style=flat-square&color=gold&label=stars)](https://github.com/OpenMinis/AwesomeMinis/stargazers) |
| [**MinisDefaults**](https://github.com/OpenMinis/MinisDefaults) | Default configuration presets — providers, models, and agent loop entries. | [![Stars](https://img.shields.io/github/stars/OpenMinis/MinisDefaults?style=flat-square&color=gold&label=stars)](https://github.com/OpenMinis/MinisDefaults/stargazers) |

---

## ✨ Features

<table>
<tr>
<td width="50%">

**🤖 Multi-Model AI**<br>
Connect to Anthropic Claude, OpenAI GPT, Google Gemini, OpenRouter, or any OpenAI-compatible endpoint. Switch models per conversation.

</td>
<td width="50%">

**🐚 Built-in Linux Shell**<br>
A full Alpine Linux environment runs on-device. The agent writes and executes scripts, installs packages, and processes data — no server needed.

</td>
</tr>
<tr>
<td>

**📱 Deep iOS Integration**<br>
Native access to HealthKit, Calendar, Reminders, HomeKit, Contacts, Bluetooth, Location, Photos, Speech, and more.

</td>
<td>

**🌐 Web Browser**<br>
The agent browses the web, fills forms, extracts content, and takes screenshots — all within the app.

</td>
</tr>
<tr>
<td>

**🛠️ Custom Skills**<br>
Import or create AI skills to extend the agent's capabilities. Compatible with the open `SKILL.md` format.

</td>
<td>

**🔒 Privacy by Design**<br>
API keys stay in your device Keychain. No data collected. No third-party analytics. Your conversations are yours.

</td>
</tr>
</table>

---

## 📦 Download

| Platform | Download | Requirements |
|---|---|---|
| 🍎 **iOS / iPadOS** | [**App Store →**](https://apps.apple.com/app/id6759188481) | iOS 16+ / iPadOS 16+ |
| 🖥️ **macOS** | [**App Store →**](https://apps.apple.com/app/id6759188481) | macOS 13+ (Apple Silicon) |
| 🥽 **visionOS** | [**App Store →**](https://apps.apple.com/app/id6759188481) | visionOS 1.0+ |
| 🤖 **Android** | [**GitHub Releases →**](https://github.com/OpenMinis/OpenMinis/releases) | Preview — coming soon |

---

## 🔌 Supported AI Providers

Open Minis supports multiple AI providers. You need at least one API key to get started.

| Provider | Models | Get API Key |
|---|---|---|
| **Anthropic** | Claude Opus 4.6, Sonnet 4.6, Haiku 4.5 | [console.anthropic.com](https://console.anthropic.com/) |
| **OpenAI** | GPT-4o, o-series | [platform.openai.com](https://platform.openai.com/api-keys) |
| **Google Gemini** | Gemini 2.5 Pro/Flash, 3 Pro/Flash | [aistudio.google.com](https://aistudio.google.com/apikey) |
| **OpenRouter** | Multi-provider routing | [openrouter.ai](https://openrouter.ai/keys) |
| **Custom** | Any OpenAI-compatible API | Your provider's dashboard |

---

## 🛠️ Skills Ecosystem

Skills are reusable instruction sets stored as `SKILL.md` files that give the agent specialized knowledge and workflows — install in seconds, share with the community.

**Popular skills from [MinisSkills](https://github.com/OpenMinis/MinisSkills):**

| Skill | What it does |
|---|---|
| `github-trending` | Fetch GitHub Trending and generate bilingual summaries with optional TTS playback |
| `twitter-x-hub` | Read/write Twitter/X data via cookie auth |
| `bilibili-hub` | Search, download, and analyze Bilibili content |
| `health-sleep-analysis` | Analyze Apple Health sleep data with AI insights |
| `ppt-generator` | Generate beautiful presentations from a prompt |
| `qbt-hub` | Manage qBittorrent downloads remotely |
| `12306-query` | Query China rail tickets and schedules |
| `doubao-tts` | Text-to-speech via Doubao (ByteDance) |

→ [Browse all 40+ skills in MinisSkills](https://github.com/OpenMinis/MinisSkills)

---

## 🌟 Community Use Cases

Real workflows built by the Minis community. See [**AwesomeMinis**](https://github.com/OpenMinis/AwesomeMinis) for the full collection — contributions welcome!

- 🫀 Apple Watch heart health monitoring with daily AI summaries
- 📊 One-click PPT generation from a topic
- 🌅 Smart daily briefing with weather, calendar, and news
- 🚄 Travel planning with 12306 + maps integration
- 📰 GitHub Trending podcast with TTS playback

---

## 🤝 Contributing

We welcome contributions across all repositories!

- **Submit a skill** → Open a PR to [MinisSkills](https://github.com/OpenMinis/MinisSkills)
- **Share a use case** → Open a PR or Issue to [AwesomeMinis](https://github.com/OpenMinis/AwesomeMinis)
- **Report bugs / request features** → [OpenMinis Issues](https://github.com/OpenMinis/OpenMinis/issues)
- **Join the discussion** → [Telegram Community](https://t.me/openminis)

---

<div align="center">

Made with ❤️ by [@wsvn53](https://github.com/wsvn53) and the Open Minis community<br>
[openminis.app](https://openminis.app) · [Privacy Policy](https://openminis.github.io/privacy-policy.html) · [Contact](mailto:dev@openminis.me)

</div>
