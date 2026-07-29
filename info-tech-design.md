# 📋 Tech, AI Agent & Design Updates — Juli 2026

> Update harian otomatis yang merangkum tren terbaru seputar Developer Tools, AI Agent Framework, dan UI/UX Design.

---

## 🛠️ TOOLS TERKINI

### 1. Cursor Composer 3: AI Coding Model 1.5 Triliun Parameter
- **Deskripsi:** Cursor baru saja mengumumkan Composer 3, sebuah frontier model berukuran raksasa yang dilatih dari nol di superkomputer Colossus milik SpaceX. Menawarkan 200K token context window dengan kecepatan 200+ token/detik. Berbeda dengan tools lain, ini bukan model pihak ketiga (seperti GPT/Claude) melainkan model *proprietary* khusus untuk *coding agentic* otonom multi-file.
- **Harga & Performa:** Menawarkan biaya input $0,50 per juta token (90% lebih murah dari Claude Opus 4.6) dengan skor CursorBench 61,3.
- **Sumber:** [Mughu.id](https://mughu.id/blog/composer-3-cursor-segera-rilis)

### 2. Figma Akuisisi Platform Vibe-Coding "Bud"
- **Deskripsi:** Figma resmi mengakuisisi tim pengembang di balik platform *vibe-coding* bernama Bud (sebelumnya Orchids) yang didanai Y Combinator. Platform Bud tadinya memungkinkan pembuatan aplikasi hanya dengan bahasa sehari-hari. 
- **Dampak:** Layanan Bud akan ditutup 18 Juli 2026. Ini sinyal kuat Figma bukan lagi sekadar kanvas desain, tapi bersiap menjadi platform prototyping yang utuh (sejalan dengan perilisan Figma Make).
- **Sumber:** [PojokBali](https://pojokbali.com/detail/25797/figma-akuisisi-tim-di-balik-platform-vibe-coding-bud-sinyal-ekspansi-ke-ranah-ai-dan-prototyping)

---

## 🤖 AI AGENT & TECH

### 1. Microsoft Agent Framework Harness Dirilis
- **Deskripsi:** Microsoft merilis *batteries-included harness* untuk ekosistem AI Agent di Python dan .NET. Fitur ini membungkus *loop*, *planning*, *memory*, *tool approval*, dan integrasi OpenTelemetry menjadi satu pemanggilan (*single call*). 
- **Fokus:** Sangat cocok untuk *long-running autonomous work* (riset, data analysis) dengan struktur *pass-by-reference* dan kontrol limit loop.
- **Sumber:** [Microsoft DevBlogs](https://devblogs.microsoft.com/agent-framework/the-microsoft-agent-framework-harness-is-now-released/)

### 2. NVIDIA NOOA: Open-Source AI Agent Framework
- **Deskripsi:** NVIDIA meluncurkan framework agen bernama NOOA yang menggunakan konsep "an agent is a Python object". Yang menarik adalah konsumsi token yang 50% lebih efisien karena menggunakan arsitektur *pass-by-reference* (tidak semua hal dimasukkan ke *context window* LLM).
- **Performa:** Meraih skor 82.2% di SWE-bench (dengan GPT-5.5) dan menduduki puncak leaderboard di CyberGym L1.
- **Sumber:** [ByteIota](https://byteiota.com/nvidia-nooa-open-source-ai-agent-framework-with-50-lower-token-cost/)

### 3. Pembaruan Gemini API: Managed Agents (3.6 Flash) & Hooks
- **Deskripsi:** Google memperbarui Managed Agents API mereka. Kini menggunakan Gemini 3.6 Flash sebagai *default* dan memperkenalkan fitur **Environment Hooks**. Hook ini memungkinkan developer untuk mengaudit, memblokir, atau melinting panggilan *tools* di dalam cloud sandbox sebelum/sesudah dieksekusi.
- **Sumber:** [Google Blog](https://blog.google/innovation-and-ai/technology/developers-tools/expanding-managed-agents-gemini-api-3-6-flash-hooks/)

---

## 🎨 DESIGN & UI/UX

### 1. Figma Weave AI: Gabungkan Ragam Model AI Visual
- **Deskripsi:** Figma memperkenalkan Figma Weave (sebelumnya Weavy), platform kreatif berbasis node untuk menggabungkan model AI seperti OpenAI, Runway, Kling, Black Forest Labs, hingga Bria dalam satu alur visual (node-based).
- **Fitur:** Mengurangi kerepotan desainer yang sebelumnya harus berpindah-pindah tab untuk generate, upscale, lalu relight gambar. Mendukung *channel editor*, z-depth, inpaint, hingga ControlNet.
- **Sumber:** [Hazdo Web](https://hazdo.web.id/cara-kerja-figma-weave-ai-gabungkan-semua-model-ai-jadi-satu/)

### 2. Figma Design Agent (Beta) & Alternatifnya
- **Deskripsi:** Figma merilis Design Agent asli untuk kanvasnya guna membuat UI, iterasi desain, dan meringkas *feedback*. Namun versi ini masih beta dan terbatas untuk paket berbayar tingkat tinggi. 
- **Alternatif:** Plugin seperti "Buddy by Anima" mulai banyak dilirik karena kemampuannya mengimpor URL dan HTML mentah langsung menjadi layer Figma yang dapat diedit (hal yang belum bisa dilakukan agent asli Figma).
- **Sumber:** [Anima Blog](https://www.animaapp.com/blog/id/genai-id/figma-design-agent-review-features-pros-cons-best-alternative-id/)

### 3. Figma Config 2026: Animasi Native (Figma Motion) & Code Layers
- **Deskripsi:** Figma mengubah cara kerja Motion/Animasi. Tidak perlu *export* ke Lottie/After Effects, Figma Motion kini hadir *native* dengan *timeline* komprehensif, *keyframes*, kurva kustom, hingga *path trim*. Ditambah lagi **Code Layers** yang memungkinkan *code* berinteraksi langsung dalam kanvas dan sinkron dengan GitHub PR.
- **Sumber:** [Beryl Design](https://www.beryldesign.fr/en/post/figma-config-2026)

---
*Di-generate secara otomatis oleh Putra (Hermes AI Assistant)*