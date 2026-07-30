# Info Terbaru Tools, AI Agent & Design
(Update: 30 Juli 2026)

## 🛠️ TOOLS TERKINI

**[GitLens 18](https://www.gitkraken.com/blog/gitlens-18-turns-the-commit-graph-into-an-agent-command-center)**
Versi terbaru dari GitLens mengubah fitur visualisasi history commit menjadi agent command center. Membantu developer untuk bisa memantau pekerjaan agent, me-review dan mengatur perubahan kode AI secara langsung dari dalam editor VS Code (atau editor berbasis VS Code lainnya seperti Cursor dan Windsurf).

**[BrowserStack Test Companion](https://www.prnewswire.co.uk/news-releases/browserstack-launches-test-companion-agentic-ai-that-brings-complete-test-automation-into-the-ide-302837727.html)**
BrowserStack meluncurkan Test Companion, sebuah tool AI generatif untuk mempermudah otomatisasi software testing (authoring, execution, debugging, dan maintenance), langsung dari dalam IDE.

**[env0 Agentic Experience (AX)](https://www.env0.com/blog/announcing-the-env-zero-agentic-experience-point-your-coding-agent-at-your-infrastructure)**
Platform env0 merilis Agent CLI baru yang memungkinkan AI coding agents (seperti Claude Code, Cursor, Copilot) untuk langsung mengakses infrastruktur pengguna, berinteraksi melalui natural language, dan melakukan tugas infra berdasarkan kondisi state dan deployment yang sesungguhnya.

---

## 🤖 AI AGENT & TECH

**[GitHub Copilot Code Review & MCP](https://github.blog/changelog/2026-07-29-copilot-code-review-agent-skills-and-mcp-now-generally-available/)**
GitHub Copilot meresmikan dua fitur utamanya, yaitu Agent Skills dan dukungan Model Context Protocol (MCP) server. Fitur ini memungkinkan Copilot membaca panduan pengembangan internal (*SKILL.md*) dan mengakses sistem pihak ketiga (misalnya issue trackers) untuk me-review kode dengan lebih pintar dan spesifik.

**[Google Gemini Enterprise Agent Platform & A2UI v0.9](https://cloud.google.com/blog/products/ai-machine-learning/whats-new-in-gemini-enterprise-agent-platform)**
Google Cloud memperbarui Gemini Enterprise Agent Platform dengan kapabilitas baru seperti Agent Memory Bank, operasi asinkron hingga 7 hari, dan sistem IAM native (Agent Identity) untuk akses least-privilege. Bersamaan dengan itu, Google merilis standar A2UI v0.9 untuk memudahkan integrasi UI generatif dari AI ke dalam existing design system menggunakan JSON schema.

**[Moonshot AI Kimi K3 & vLLM](https://theagenttimes.com/articles/moonshot-ai-s-2-8-trillion-parameter-kimi-k3-gets-day-zero-v-219baf5d)**
Moonshot AI merilis model open-weight Kimi K3 yang memiliki arsitektur Mixture-of-Experts 2,8 triliun parameter, context window 1 juta token, dan visual understanding bawaan. Model ini langsung didukung oleh engine vLLM untuk mempermudah implementasi *self-hosted*.

**[NVIDIA NOOA Framework](https://byteiota.com/nvidia-nooa-open-source-ai-agent-framework-with-50-lower-token-cost/)**
NVIDIA memperkenalkan open-source framework bernama NOOA, yang secara signifikan mampu memangkas penggunaan token model AI hingga 50%. Frameowrk ini juga dipublikasikan bersamaan dengan pengumuman pembentukan *Open Secure AI Alliance* beranggotakan 37 entitas teknologi terkemuka.

**[Databricks Omnigent 0.7.0](https://theagenttimes.com/articles/databricks-signals-omnigent-0-7-0-with-scheduled-automations-8f8e64ac)**
Databricks merilis Omnigent versi 0.7.0 dengan pembaruan utama mencakup fitur penjadwalan otonom, sistem routing model yang lebih baik, dikte suara (voice dictation), serta *first-class projects*.

---

## 🎨 DESIGN & UI/UX

**[Replit Design](https://replit.com/blog/introducing-replit-design)**
Replit meluncurkan "Replit Design", sebuah workspace UI visual canvas yang terhubung langsung dengan kode dan memanfaatkan AI (Claude, GPT-5, Gemini) untuk mempermudah perancangan app UI. Terintegrasi pula dengan referensi dari Mobbin untuk kebutuhan perancangan sistem desain (design system) yang bisa langsung direalisasikan menjadi web/app yang responsif.

**[Canva Code 2.0](https://autonainews.com/canva-code-2-0-cuts-website-and-app-generation-time-75/)**
Canva meluncurkan Canva Code 2.0 yang membawa konsep "Vibe Coding" untuk desain antarmuka. Dengan input teks, fitur ini bisa menghasilkan framework HTML interaktif dalam platform Canva. Pembaruan ini diklaim memangkas waktu code generation hingga 75%.

**[Claude Design Workspace](https://we0.ai/articles/how-claude-design-grew-from-a)**
Anthropic mengungkap bagaimana proyek internal eksperimental mereka telah berkembang pesat menjadi Claude Design, yang kini telah digunakan oleh lebih dari satu juta pengguna. Workspace ini berfokus pada pembuatan layout UI/UX awal, prototype interaktif, atau konten marketing statis yang kemudian dapat dilanjutkan oleh *Claude Code* untuk dikerjakan secara nyata ke tahap *production*.

**[Standardisasi DESIGN.md](https://medevel.com/markdown-is-the-new-figma-welcome-to-the-era-of-design-md/)**
Konsep penggunaan file markdown baru bernama `DESIGN.md` (serupa dengan instruksi `AGENTS.md`) kini mulai mendapatkan adopsi luas (seperti di Vercel, Atlassian, dll). Konsep ini bertujuan untuk menyertakan instruksi gaya bahasa visual (brand look and feel) dan komponen UI, sehingga agent AI untuk coding dapat membuat hasil UI yang presisi tanpa memerlukan referensi ekspor schema atau prompt panjang.