<div align="center">

<img src="assets/penguin.png" width="96" height="96" alt="Penguin">

# Penguin

### Your own AI office, running on your machine.

A local-first **multi-agent workspace**: delegate real work to a coordinated team of AI agents that plan, talk to each other, and ship finished deliverables — slide decks, dashboards, Word, Excel, PDF and PowerPoint.

<p>
<a href="https://github.com/dovannam115/penguin-releases/releases/latest"><img src="https://img.shields.io/github/v/release/dovannam115/penguin-releases?label=download&style=for-the-badge&color=2e90ff&logo=github" alt="Latest release"></a>
<img src="https://img.shields.io/badge/platform-Windows-1f6feb?style=for-the-badge&logo=windows" alt="Windows">
<img src="https://img.shields.io/badge/runs-100%25%20local-16a34a?style=for-the-badge" alt="Local first">
</p>

<br>

<img src="assets/menu.png" width="760" alt="Penguin slide template library">

</div>

---

## What is Penguin?

Penguin is a desktop AI workspace. Instead of chatting with one model, you open a **task** and pull in a team of specialist agents — a manager, analysts, a designer, a writer, a developer. They split the work, hand off to each other, and produce **actual files** you can open and send, not just text.

Everything runs on your own machine. Your data, chats and files stay in a local folder and are never uploaded anywhere except to the AI provider you choose.

## Highlights

- **A team, not a chatbot.** Eight pre-configured agents out of the box (BI / Data Analyst / Data Engineer / Designer / Developer / Writer / Prompt Master). Pick several and they answer in parallel; call one by name with `@Agent`.
- **Real deliverables.** Agents write and export **PowerPoint, Word, Excel, PDF** and interactive **dashboards** — with live formulas in Excel and editable text in native PPTX.
- **A beautiful slide library.** 20 ready-made, self-contained slide languages grouped by use, each in a refined **jewel palette** (emerald · sapphire · plum · gold). Hover any card to watch the slides auto-play, search by **color or style** ("blue", "dark", "minimal"…), click to open full size.
- **Visual + AI editor.** Tweak any slide right in the app: click an element to change text, size, color and box; drag to reposition; or box a region and **describe the change in plain language** and the model rewrites that fragment.
- **Brand-aware export.** One-click **PPTX with a corporate background** (e.g. PVI) baked under every slide, native and editable.
- **Local-first & private.** Chats, tasks and files live in a local `.data/` folder. Nothing leaves your machine except your prompts to the model.
- **Bring your own brain.** Works with **Claude (Max plan)** out of the box, or plug an **OpenRouter / Gemini** API key for faster, cheaper agents.

## The slide template library

Twenty styles, from clean executive dashboards to dense consulting decks, warm editorial and dark analytics — all light-first friendly and Vietnamese-ready.

<div align="center">
<img src="assets/templates.png" width="760" alt="A selection of Penguin slide templates">
</div>

---

## Download & install

1. Grab the latest **`Penguin_v*.zip`** from the [**Releases**](https://github.com/dovannam115/penguin-releases/releases/latest) page.
2. Unzip anywhere, then double-click **`start.bat`**. The first run installs dependencies (with a progress bar); later runs start instantly.
3. Open **http://localhost:3000**.

> Already have Penguin installed? Just open **Settings → Update → Check now** and it pulls the latest release in place.

### Cài đặt nhanh (Tiếng Việt)

1. Tải file **`Penguin_v*.zip`** mới nhất ở trang [**Releases**](https://github.com/dovannam115/penguin-releases/releases/latest).
2. Giải nén ra thư mục bất kỳ, nhấp đúp **`start.bat`** — lần đầu nó tự cài (1-2 phút), lần sau chạy ngay.
3. Mở trình duyệt vào **http://localhost:3000**. Bấm **⚙ Settings** để đặt xưng hô và dán **OpenRouter API key** (nếu muốn).
4. Bấm **+ New chat**, chọn vài agent, rồi giao việc. Gọi đích danh bằng `@TênAgent`. File xuất ra nằm ở tab **Files** của task.

## Requirements

- **Windows** with **Node.js 22+** ([nodejs.org](https://nodejs.org), LTS).
- To use **Claude** agents: be signed in to **Claude Code (Max plan)** once on the machine.
- To use **OpenRouter / Gemini** agents: an [OpenRouter API key](https://openrouter.ai/keys), pasted into Settings.
- Either one is enough to get going.

## Updating

Penguin updates itself. In the app: **Settings → Update → Check now**, or drop a downloaded zip into **Settings → Update → Install from a local zip**, then **Restart Penguin**.

## Tech

Next.js 16 · TypeScript · Tailwind 4 · `@anthropic-ai/claude-agent-sdk` · local SQLite (`node:sqlite`) · Puppeteer (Edge) for PPTX/preview rendering.

<div align="center">
<br>
<sub>Made with 🐧 for people who'd rather delegate than copy-paste.</sub>
</div>
