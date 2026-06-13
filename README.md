# 📚 Omniscientia

*A free, ad-free knowledge hub built with nothing but HTML, CSS & JavaScript — powered by ~20 open APIs.*

---

## What is this?

Omniscientia is a single-file encyclopedia that lives in your browser. No frameworks, no builds, no sign-ups. Just open `index.html` and start exploring.

It stitches together live data, research papers, discussions, and encyclopedia entries across five fields:

-  **Space** — NASA, SpaceX, ISS tracking, astronomy
-  **Energy** — carbon intensity, renewables, grid data
- **Internet & Web** — protocols, open source, trending repos
-  **Artificial Intelligence** — machine learning, LLMs, neural networks
-  **Health & Biotech** — genomics, CRISPR, epidemiology

---

## 🧩 What's inside?

| Section | Source |
|---------|--------|
| Encyclopedia articles | Wikipedia REST API |
| Research papers | arXiv |
| Discussions | Hacker News (Algolia) |
| Books | Open Library |
| Live data panels | NASA, SpaceX, Open Notify, disease.sh, openFDA, GitHub, UK Carbon Intensity, Open-Meteo |
| Quick facts sidebar | Numbers API, Quotable, Unsplash |
| Quizzes | 12 handcrafted questions per field |
| Themes | Light, Dark, Sepia |

---

## How to use

1. **Clone or download**
   ```bash
   git clone https://github.com/your-username/omniscientia.git
Open the file

bash
cd omniscientia
open index.html
Or just double-click index.html. That's it.

Explore

Use the top navigation to switch between fields

Click "↻ Show different" to refresh any section

Try the quiz at the bottom of each page

Search Wikipedia directly from the top bar

Switch themes with the Light/Sepia/Dark buttons

🧰 Tech stack
Layer	Choice
Structure	Semantic HTML5
Styling	Custom CSS with CSS variables
Logic	Vanilla JavaScript (ES6+)
APIs	~20 free, public REST endpoints
Dependencies	Zero
No npm. No webpack. No React. Just a browser.

📡 APIs used
Wikipedia · arXiv · Hacker News (Algolia) · Open Library · NASA APOD · Open Notify (ISS/Astronauts) · SpaceX · disease.sh · openFDA · UK Carbon Intensity · Open-Meteo · GitHub · Numbers API · Quotable · Advice Slip · Unsplash Source

🎨 Themes
Omniscientia comes with three built-in themes:

Light — clean, modern Wikipedia-style

Sepia — warm, paper-like reading experience

Dark — easy on the eyes at night

📸 Screenshots
[Add a few screenshots here showing different fields and themes]

🧠 Why I built this
I wanted a single page that could satisfy random curiosity — a place where you can bounce from a SpaceX launch to a CRISPR explainer to a trending GitHub repo, all without ads, cookies, or distractions. A personal knowledge hub that refreshes with new content every time you visit.

📄 License
MIT — do whatever you want with it. Learn, modify, share.

Credits
All content belongs to their respective sources (Wikipedia, arXiv, NASA, etc.). This project simply aggregates and presents it in a clean, unified interface.
Feel free to contribute.