<div align="center">

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=24&duration=3000&pause=1000&color=FF6A3D&center=true&vCenter=true&width=600&lines=Web+Research+Agent+%C2%B7+Object+Detection" alt="Typing SVG" />

Hi, I'm Aryan 👋 — a B.Tech AI/ML student in Delhi who builds end-to-end:
*from async research pipelines that synthesize cited reports to real-time CV demos deployed on Hugging Face Spaces.*

</div>

---

## About Me

- 🧪 Currently building framework-free AI agents and computer-vision tools, alongside DSA prep
- 🛠️ Comfortable across ML (PyTorch, OpenCV, Ultralytics) and backend automation (Python, asyncio)
- 🏆 Smart India Hackathon 2025 — top-24 finalist
- 📩 Reachable via email below

---

## Tech Stack

<div align="center">

**AI / CV**
<br/>
<img src="https://skillicons.dev/icons?i=python,pytorch,opencv" />

**Automation & APIs**
<br/>
<img src="https://skillicons.dev/icons?i=python,bash,githubactions" />

**Tools**
<br/>
<img src="https://skillicons.dev/icons?i=git,github,vscode,linux" />

</div>

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🔎 [Web Research Automation Agent](https://github.com/xTrapcoder/web-research-automation-agent)

A CLI research agent that turns a topic into a structured, cited Markdown report — no agent framework, no paid APIs. Plans sub-queries, searches DuckDuckGo, fetches pages concurrently, and synthesizes a sourced report through a pluggable Groq/Gemini LLM layer.

**Key features**
- Plan → Gather → Synthesize pipeline, hand-written for full transparency
- Concurrent page fetching with `asyncio` + semaphore (~8× faster than sequential)
- Swappable LLM provider (Groq / Gemini) via a single `.env` line
- Graceful degradation — retries then falls back instead of crashing mid-run
- 28 tests, fully mocked, GitHub Actions CI on Python 3.11 & 3.12

`Python` `asyncio` `httpx` `BeautifulSoup4` `Groq` `Gemini` `DuckDuckGo` `pytest`

</td>
<td width="50%" valign="top">

### 🎯 [Real-Time Object Detection](https://github.com/xTrapcoder/real-time-object-detection)

Computer vision app built on a pretrained YOLO11 model, with two front ends sharing one inference core: a live local webcam mode and a deployable Gradio web demo on Hugging Face Spaces.

**Key features**
- Live annotated webcam feed (boxes, labels, confidence, FPS) via OpenCV
- Gradio web demo — upload an image/video, adjustable confidence threshold
- Shared `detector/core.py` inference core, no duplicated logic across entry points
- Handles failure cases cleanly (no detections, bad files, webcam errors)
- CPU-only by design — runs on Hugging Face's free tier, no GPU needed

`Python` `YOLO11` `Ultralytics` `OpenCV` `Gradio` `Supervision` `Hugging Face Spaces`

</td>
</tr>
</table>
