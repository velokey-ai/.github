<!--
  Velokey 组织 Profile README。
  发布：在组织下建一个名为 `.github` 的 public 仓库，把本文件放到该仓库的 `profile/README.md`，
  并把 assets/header.png 一并放到 `profile/assets/header.png`。即会显示在组织主页顶部。
  上线前替换：Discord 邀请链接、X/Twitter handle、docs 真实域名（若非 docs.velokey.ai）。
-->

<div align="center">

<!-- 品牌横幅（gpt-image-2 生成） -->
<a href="https://velokey.ai?sourceChannel=github-profile" target="_blank" rel="noopener">
  <img src="./assets/header.png" alt="Velokey — One API for text, image and video models" width="100%">
</a>

<br/><br/>

[![🚀 Get API Key](https://img.shields.io/badge/🚀_Get-API_Key-2563eb?style=for-the-badge)](https://velokey.ai?sourceChannel=github-profile)
[![🧩 All Models](https://img.shields.io/badge/🧩_All-Models-0ea5e9?style=for-the-badge)](https://velokey.ai?sourceChannel=github-profile)
[![📘 API Docs](https://img.shields.io/badge/📘_API-Docs-1d4ed8?style=for-the-badge)](https://velokey.ai?sourceChannel=github-profile)
[![🌐 Website](https://img.shields.io/badge/🌐-velokey.ai-111827?style=for-the-badge)](https://velokey.ai?sourceChannel=github-profile)

[![Status](https://img.shields.io/website?url=https%3A%2F%2Fvelokey.ai&style=flat-square&label=status&color=2563eb)](https://velokey.ai)
[![Discord](https://img.shields.io/badge/chat-discord-5865F2?style=flat-square&logo=discord&logoColor=white)](https://velokey.ai)
[![Followers](https://img.shields.io/github/followers/velokey?style=flat-square&logo=github&logoColor=white&label=followers&color=111827)](https://github.com/velokey)
[![Stars](https://img.shields.io/github/stars/velokey?style=flat-square&logo=github&logoColor=white&label=stars&color=2563eb)](https://github.com/velokey)

**Access leading text, image, and video models through one OpenAI‑compatible API.**
<br/>Switch models without rebuilding integrations. Pay only for what you use.

</div>

---

## 🌐 One endpoint, every modality

| Category | Models |
| :--- | :--- |
| **🔤 Text** | ![GPT](https://img.shields.io/badge/GPT--5.5-111827?style=flat-square) ![Claude](https://img.shields.io/badge/Claude_Opus_4.8-D97757?style=flat-square) ![Gemini](https://img.shields.io/badge/Gemini_3_Pro-4285F4?style=flat-square) ![DeepSeek](https://img.shields.io/badge/DeepSeek_V4-4D6BFE?style=flat-square) ![Kimi](https://img.shields.io/badge/Kimi_K2-000000?style=flat-square) ![MiniMax](https://img.shields.io/badge/MiniMax_M3-FF5A5F?style=flat-square) |
| **🖼️ Image** | ![GPT Image](https://img.shields.io/badge/GPT_Image_2-111827?style=flat-square) ![Nano Banana](https://img.shields.io/badge/Nano_Banana_Pro-F59E0B?style=flat-square) ![Seedream](https://img.shields.io/badge/Seedream_5.0-10B981?style=flat-square) ![Qwen](https://img.shields.io/badge/Qwen_Image-6B7280?style=flat-square) ![Midjourney](https://img.shields.io/badge/Midjourney_V7-5865F2?style=flat-square) |
| **🎬 Video** | ![Sora](https://img.shields.io/badge/Sora_2-0F172A?style=flat-square) ![Veo](https://img.shields.io/badge/Veo_3.1-4285F4?style=flat-square) ![Kling](https://img.shields.io/badge/Kling_O3-2563EB?style=flat-square) ![Seedance](https://img.shields.io/badge/Seedance_2.0-7C3AED?style=flat-square) ![Hailuo](https://img.shields.io/badge/Hailuo_2.3-059669?style=flat-square) ![Wan](https://img.shields.io/badge/Wan_2.7-EC4899?style=flat-square) |

<div align="center">

[![Browse all models](https://img.shields.io/badge/Browse_all_models-2563eb?style=for-the-badge)](https://velokey.ai?sourceChannel=github-profile)

</div>

---

## ⚡ Quickstart — keep your OpenAI SDK

Already using an OpenAI‑compatible client? Migration is a **Base URL + API key** change.

```python
from openai import OpenAI

client = OpenAI(
    api_key="YOUR_VELOKEY_API_KEY",
    base_url="https://api.velokey.ai/v1",
)

response = client.chat.completions.create(
    model="claude-opus-4-8",  # or gpt-5.5, gemini-3-pro, deepseek-v4 …
    messages=[{"role": "user", "content": "Hello from Velokey!"}],
)
print(response.choices[0].message.content)
```

<div align="center">

[![🔑 Get your API key](https://img.shields.io/badge/🔑_Get_your-API_key-2563eb?style=for-the-badge)](https://velokey.ai?sourceChannel=github-profile)
[![📘 Read the docs](https://img.shields.io/badge/📘_Read_the-docs-0ea5e9?style=for-the-badge)](https://velokey.ai?sourceChannel=github-profile)

</div>

---

## 💡 Why Velokey

- **🔌 One API across providers** — one familiar, OpenAI‑compatible format for text, image, and video. Add or switch models without rebuilding your stack.
- **🎛 Choose by capability and price** — compare capabilities, billing units, and pricing *before* you integrate.
- **🛡 Reliable by design** — route‑health monitoring and **automatic failover** to healthy routes, with usage, latency, errors, and spend in one console.
- **💸 Pay as you go** — token‑based for LLMs, per‑image and per‑second for media. Transparent pricing, no lock‑in.
- **🔒 Private by default** — we don't retain prompt or model‑output content, and never train on your API data.

---

<div align="center">

<sub>One key. Text, image & video models. OpenAI‑compatible. · <a href="https://velokey.ai?sourceChannel=github-profile">velokey.ai</a> · <a href="mailto:support@velokey.ai">support@velokey.ai</a></sub>

<br/><sub>Built for developers worldwide · © 2026 Velokey</sub>

</div>
