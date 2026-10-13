<p align="center">
<img src="https://readme-typing-svg.demolab.com/?lines=Moi%21+&font=Fira+Code&weight=500&size=16&color=768390&width=720&height=30&vCenter=true&multiline=false&duration=1524&pause=0&repeat=false" alt="Moi!" /><br/>
<img src="https://readme-typing-svg.demolab.com/?lines=%C2%A0;%24+whoami&font=Fira+Code&weight=500&size=18&color=EC4899&width=720&height=32&vCenter=true&multiline=false&duration=800&pause=0&repeat=false" alt="$ whoami" /><br/>
<img src="https://readme-typing-svg.demolab.com/?lines=%C2%A0;Jainil+Dadhaniya&font=Fira+Code&weight=700&size=44&color=A855F7&width=720&height=62&vCenter=true&multiline=false&duration=1300&pause=0&repeat=false" alt="Jainil Dadhaniya" /><br/>
<img src="https://readme-typing-svg.demolab.com/?lines=%C2%A0;AI%2FML+developer+%C2%B7+MSc+Data+Science+%40+Tampere+University&font=Fira+Code&weight=500&size=18&color=3B82F6&width=720&height=32&vCenter=true&multiline=false&duration=1182&pause=1118&repeat=false" alt="AI/ML developer · MSc Data Science @ Tampere University" /><br/>
<img src="https://readme-typing-svg.demolab.com/?lines=%C2%A0;%24+.%2Fhire_me+--role+%22AI%2FML+Engineer%22+--city+Tampere&font=Fira+Code&weight=500&size=18&color=EC4899&width=720&height=32&vCenter=true&multiline=false&duration=1788&pause=1712&repeat=false" alt="$ ./hire_me --role &quot;AI/ML Engineer&quot; --city Tampere" /><br/>
<img src="https://readme-typing-svg.demolab.com/?lines=%C2%A0;%C2%A0;%C2%A0;%C2%A0;%E2%9C%93+open+to+work%3A+entry-level+AI%2FML+roles+in+Tampere+or+Helsinki&font=Fira+Code&weight=700&size=18&color=16A34A&width=720&height=32&vCenter=true&multiline=false&duration=1180&pause=70&repeat=false" alt="✓ open to work: entry-level AI/ML roles in Tampere or Helsinki" />
</p>

## 👋 About me

- 🎓 **Studying:** MSc Data Science at Tampere University (Computing Science & Electrical Engineering, GPA 4.5/5)
- 🧑‍🏫 **Teaching:** TA on Data-Intensive Programming (COMP.CS.320) and Deep Learning (DATA.ML.200)
- 🤖 **How I got here:** full-stack first, ML second — which is why my projects tend to end up deployed instead of stopping at a notebook
- 🎯 **Looking for:** entry-level AI/ML engineering work in Finland
- 🗣️ **Languages:** English (C1), Hindi (C2), Finnish (A1, studying)
- ⚡ **Fun fact:** I write poetry and love crime thrillers, so right now I'm writing a murder mystery in verse

## 🚀 Projects

<table>
<tr>
<td colspan="2">

### 🧹 [Sift](https://github.com/vibey19/sift) &nbsp;·&nbsp; [Live demo ↗](https://sift-csv.vercel.app/)

Drop in a messy CSV. Sift runs 29 quality, leakage and contamination checks in a single pass, applies the fixes that need no decision, and hands back the rest with row numbers and a reason.

On a churn dataset it found a leaked column that had been inflating reported accuracy by **0.275** — caught by fitting a depth-3 tree on each column alone and comparing it against the majority-class baseline. Mislabelled rows are scored with 5-fold out-of-fold predictions, so no row is ever graded by a model that already saw it, and the auditor's own accuracy is printed beside its flags.

<img src="https://go-skill-icons.vercel.app/api/icons?i=python,fastapi,pandas,scikitlearn,react,vite,vercel&theme=dark" height="40" alt="Python, FastAPI, pandas, scikit-learn, React, Vite, Vercel" />

</td>
</tr>
<tr>
<td colspan="2">

### 📚 [Lectura](https://github.com/vibey19/lectura) &nbsp;·&nbsp; [Live demo ↗](https://lectura-murex.vercel.app)

Photograph handwritten notes, a blackboard or a slide and get back structured, editable notes with the mathematics typeset in LaTeX.

I benchmarked **7 OCR and vision-language backends** against ground truth I transcribed by hand, scoring prose and mathematics separately because classical OCR breaks on notation long before it breaks on text. The backend I shipped reaches **0.124 formula error against 0.159 for a model eight times its size**. Reading a four-page set went from **201 seconds to 23** by moving the model onto a free Hugging Face ZeroGPU Space and caching per page. Reading is kept separate from a deterministic, unit-tested structuring step, which is what stops the vision model quietly rewriting your headings.

<img src="https://go-skill-icons.vercel.app/api/icons?i=python,pytorch,huggingface,react,docker,vercel&theme=dark" height="40" alt="Python, PyTorch, Hugging Face, React, Docker, Vercel" />

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔍 [Crosscheck](https://github.com/vibey19/crosscheck)

A cross-document contradiction engine for scientific literature. Give it related arXiv preprints and it pulls out atomic claims, cross-indexes them, finds pairs that disagree, re-checks every hit with an adversarial second pass, and quotes the exact span from both papers.

A benchmark harness writes its own numbers straight into the README — including the unflattering ones.

<img src="https://go-skill-icons.vercel.app/api/icons?i=typescript,nodejs,gemini,githubactions&theme=dark" height="40" alt="TypeScript, Node.js, Gemini, GitHub Actions" />

</td>
<td width="50%" valign="top">

### 🎬 [CaptionCrafter](https://github.com/vibey19/CaptionCrafter) &nbsp;·&nbsp; [Live ↗](https://caption-crafter-ai.vercel.app/)

Upload a video, caption it, restyle it, burn the captions in. Amazon Transcribe handles speech-to-text; you fix the wording and timings in an editor.

The burn-in runs on ffmpeg.wasm **in the browser**, which removed the server-side video pipeline altogether — no render queue, and the file never leaves your tab.

<img src="https://go-skill-icons.vercel.app/api/icons?i=nextjs,javascript,aws,ffmpeg,tailwindcss,vercel&theme=dark" height="40" alt="Next.js, JavaScript, AWS, FFmpeg, Tailwind, Vercel" />

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🪨 [PebbleDB](https://github.com/vibey19/PebbleDB)

A tiny SQLite clone in pure Python, no dependencies — lexer, parser, B+Tree, pager, query planner. Insert 3,000 rows in random order and the on-disk tree really splits; `EXPLAIN` says whether it took an index seek or a full scan, and why.

<img src="https://go-skill-icons.vercel.app/api/icons?i=python&theme=dark" height="40" alt="Python" />

</td>
<td width="50%" valign="top">

### 🧬 [fedscreen](https://github.com/vibey19/fedscreen) &nbsp;🚧

Federated analysis of colorectal cancer screening indicators. Three sites each keep their own individual-level data, run the same R pipeline locally, suppress small counts, and publish only aggregate tables — the central side never reads a single record. All data simulated. Still in progress.

<img src="https://go-skill-icons.vercel.app/api/icons?i=r,githubactions&theme=dark" height="40" alt="R, GitHub Actions" />

</td>
</tr>
</table>

## 💼 Internship work

### 🍔 MunchKart &nbsp;·&nbsp; [Store ↗](https://munch-kart-store.vercel.app) &nbsp;·&nbsp; [Admin ↗](https://munch-kart-admin.vercel.app)

A multi-store food ordering platform with live order tracking and payments, plus the admin dashboard behind it — my deliverable across a six-month full-stack internship at eSpectra Softweb Solutions. I built the dashboard on my own, covering menus, orders, pricing and analytics, so store owners could change a price themselves instead of filing a ticket with a developer.

Client data and branding are replaced with fixtures in these public repos.

<img src="https://go-skill-icons.vercel.app/api/icons?i=nextjs,typescript,firebase,stripe,clerk,tailwindcss&theme=dark" height="40" alt="Next.js, TypeScript, Firebase, Stripe, Clerk, Tailwind" />

Code: [store](https://github.com/vibey19/MunchKart-Store) &nbsp;·&nbsp; [admin](https://github.com/vibey19/MunchKart-Admin)

## 🧑‍💼 Experience

- 🧑‍🏫 **Teaching Assistant — Data-Intensive Programming (COMP.CS.320)**, Tampere University · Oct 2026 – Jan 2027
  Grading weekly Spark and Databricks work on whether the distributed pipeline is actually correct, by reading how a job gets to its answer rather than just checking the output.
- 🧑‍🏫 **Teaching Assistant — Deep Learning (DATA.ML.200)**, Tampere University
  Running a weekly two-hour session working through the exercises live and debugging students' model code with them, and grading submissions against what the student says their model does — which is how you catch a right answer reached the wrong way.
- 💻 **Full-Stack Developer Intern**, eSpectra Softweb Solutions · Nov 2024 – May 2025
  Shipped the multi-store food delivery platform above in Next.js, TypeScript and Firebase.
- 📊 **Data Analyst Intern**, MedTourEasy · Sep 2023 – Dec 2023
  Looked at whether age at death differs between left- and right-handed people across 1,000+ records, cleaning and analysing in Python and R and reporting in Power BI.

## 🛠️ Tech stack

### 🧠 ML & Data

<img src="https://go-skill-icons.vercel.app/api/icons?i=python,pytorch,tensorflow,scikitlearn,pandas,numpy,opencv,spark&theme=dark" height="40" alt="Python, PyTorch, TensorFlow, scikit-learn, pandas, NumPy, OpenCV, Apache Spark" />

### 💻 Engineering

<img src="https://go-skill-icons.vercel.app/api/icons?i=javascript,typescript,react,nextjs,fastapi,nodejs,java,c,postgresql,r&theme=dark" height="40" alt="JavaScript, TypeScript, React, Next.js, FastAPI, Node.js, Java, C, SQL, R" />

### ☁️ Cloud & Tools

<img src="https://go-skill-icons.vercel.app/api/icons?i=docker,git,githubactions,vercel,aws,huggingface&theme=dark" height="40" alt="Docker, Git, GitHub Actions, Vercel, AWS, Hugging Face Spaces" />

## 🏅 Certifications & activities

- **Google Data Analytics Professional Certificate**
- Student tutor at Tampere University · TREY Election Committee, Halloped election
- Volunteer at Slush 2025 (Helsinki) and Academic Mindtrek 2025 (Tampere) · GoGlobal English speaking clubs

## 📫 Let's connect

Hiring for an entry-level AI/ML role, or have a thesis topic that needs someone? Drop me a message 👇

<a href="mailto:jainil.dadhaniya@tuni.fi"><img src="https://go-skill-icons.vercel.app/api/icons?i=gmail&theme=dark" height="40" alt="Email" /></a>&nbsp;
<a href="https://www.linkedin.com/in/jainil19"><img src="https://go-skill-icons.vercel.app/api/icons?i=linkedin&theme=dark" height="40" alt="LinkedIn" /></a>

<p align="center">
<img src="https://readme-typing-svg.demolab.com/?lines=%24+exit&font=Fira+Code&weight=500&size=18&color=EC4899&width=720&height=32&vCenter=true&multiline=false&duration=4065&pause=0&repeat=false" alt="$ exit" /><br/>
<img src="https://readme-typing-svg.demolab.com/?lines=%C2%A0;Kiitos+for+stopping+by%21+&font=Fira+Code&weight=700&size=18&color=A855F7&width=720&height=32&vCenter=true&multiline=false&duration=700&pause=0&repeat=false" alt="Kiitos for stopping by!" />
</p>
