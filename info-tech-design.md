# Info Tech & Design Terkini
*(Update: Agustus 2026)*

## 🛠️ TOOLS TERKINI
- **Terminal-Browser (oleh Zenbu)**
  Sebuah tool inovatif yang mengintegrasikan Chromium browser langsung ke dalam terminal. Tool ini dirancang sebagai komponen *agent development environment*, memungkinkan developer dan AI agent untuk melihat preview lokal, memeriksa elemen, dan melakukan QA berbasis browser tanpa harus berpindah aplikasi. 
  [Referensi: RuntimeWire](https://runtimewire.com/article/zenbu-terminal-browser-coding-agents-chromium-terminal)
  
- **Topcoat**
  Framework baru berbasis Rust untuk membangun aplikasi web reaktif full-stack. Topcoat merender markup di sisi server dan mengompilasi subset Rust menjadi JavaScript untuk interaktivitas, mengurangi overhead WebAssembly sekaligus menjaga logika tetap aman dan terpusat di Rust.
  [Referensi: Tokio Blog](https://tokio.rs/blog/2026-07-22-announcing-topcoat)
  
- **Numbat (oleh Perplexity)**
  Framework keamanan *open-source* berupa binary Go ringan yang mengawasi AI coding agent di perangkat lokal (macOS, Linux, Windows). Numbat menangkap *hooks* dari berbagai *harness* agent (seperti Claude Code dan Codex), menerapkan 52 aturan bawaan, dan dapat memblokir aksi berbahaya sebelum dieksekusi oleh agent.
  [Referensi: Oton Technology](https://otontechnology.com/perplexity-numbat-open-source-ai-coding-agent-security/)


## 🤖 AI AGENT & TECH
- **DeepSeek V4-Flash-0731**
  Pembaruan versi rilis dari model V4-Flash (284B parameter / 13B aktif MoE). Tanpa mengubah arsitektur, pembaruan *post-training* ini meningkatkan secara drastis kemampuan agent, *coding*, dan integrasi API (native Responses API), membuatnya mampu mengungguli V4-Pro pada sembilan benchmark agen dan pemrograman dengan biaya jauh lebih murah.
  [Referensi: TechTimes](https://www.techtimes.com/articles/322513/20260731/deepseek-retrained-v4-flash-beats-its-flagship-pro-nine-agent-benchmarks.htm)
  
- **SkillRise**
  Kerangka kerja AI agent inovatif yang melatih *reinforcement learning policy* tunggal untuk menyelesaikan tugas sekaligus menyusun "dokumen keahlian" (*skill document*) yang dapat ditransfer langsung ke tugas berikutnya, mengungguli metode multi-tahap pada berbagai tolok ukur.
  [Referensi: TechTimes](https://www.techtimes.com/articles/322394/20260731/one-agent-learns-every-task-skillrise-compiles-transferable-know-how.htm)
  
- **K-EXAONE 2.0 (oleh LG AI Research)**
  Model AI *foundation* terbesar asal Korea dengan 750 miliar parameter yang dirilis ke open-source (Hugging Face) dengan lisensi Apache 2.0. Model ini meningkatkan skor rata-rata hingga 10% di berbagai benchmark dibandingkan versi sebelumnya dan bersaing ketat dengan model global dalam pemahaman konteks panjang dan kemampuan agentik.
  [Referensi: LG AI Research News](https://www.lgresearch.ai/news/view?seq=678)
  
- **Genkit Agents (Google)**
  API baru dari Google untuk membangun aplikasi AI *full-stack* yang *agentic*. Genkit menyederhanakan pengelolaan memori, loop alat (tool loop), dan protokol streaming, memungkinkan developer mendefinisikan *agent* di server dan mengelolanya dari *frontend* menggunakan antarmuka yang sama.
  [Referensi: Google Developers Blog](https://developers.googleblog.com/build-agentic-full-stack-apps-with-genkit/)


## 🎨 DESIGN & UI/UX
- **Figma Make: Properties Panel & Annotations**
  Figma Make kini dilengkapi panel properti bergaya desain untuk mengubah parameter UI (seperti spasi, warna, dan tipografi) pada kode secara visual. Fitur anotasi memungkinkan desainer memberikan instruksi kontekstual kepada agent untuk penyesuaian spesifik, mempercepat transisi dari desain ke kode fungsional.
  [Referensi: Figma Blog](https://www.figma.com/blog/properties-panel-and-annotations-now-in-figma-make/)
  
- **Figma Motion**
  Animasi kini menjadi material bawaan (native) di kanvas Figma. Fitur *Motion* menghadirkan *timeline* penuh, kurva kecepatan (easing), dan keyframe, menjadikan pengaturan gerak dapat dimasukkan langsung dalam komponen dan variabel sistem desain tanpa bergantung pada aplikasi eksternal.
  [Referensi: Figma Blog](https://www.figma.com/blog/introducing-figma-motion/)
  
- **Code Layers di Figma**
  Dalam perombakan alur kerja desain-ke-kode (design-to-code), *Code Layers* mengubah kode menjadi lapisan interaktif yang dapat diperlakukan selayaknya komponen desain. Pengguna dapat mengimpor repositori GitHub langsung ke kanvas, mengeksplorasi prototipe, dan memodifikasi interaksi kode tanpa batas pemisah antara mode *design* dan *develop*.
  [Referensi: Beryl Design](https://www.beryldesign.fr/en/post/figma-config-2026)