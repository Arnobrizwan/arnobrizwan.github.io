# Cowork Prompt — Update Arnob's LinkedIn Profile

Copy everything below the line into Claude Cowork (or any agent with authenticated browser access to LinkedIn). It contains all the content ready to paste — the agent only needs to navigate the LinkedIn UI and fill the fields.

---

You have authenticated browser access to my LinkedIn profile: **https://www.linkedin.com/in/arnob-rizwan-033704239/**

Update my profile section by section using the exact content below. For each section: open the editor (pencil / "Add" button), paste the content, and save. Do NOT invent or embellish anything — use only what's written here. If a field has a character limit, trim from the end while keeping the most impressive facts. Work top to bottom and tell me what you changed after each section.

## 1) HEADLINE (max 220 chars)

```
AI/ML Engineer • Full-Stack & Mobile | Production PyTorch & LLM Agents | React Native · Flutter · FastAPI · AWS | SWE @ UTM (Grad July 2026) | Open to AI Engineering roles
```

## 2) ABOUT / SUMMARY

```
Final-year Software Engineering student at Universiti Teknologi Malaysia (graduating July 2026) who ships production software for clients in 4 countries while studying full-time.

Right now I'm an Application Developer for a Luxembourg delivery startup, Founding Backend Engineer at an AI storage startup, and recently finished a contract as an ML Engineer (via Mercor) building production PyTorch models for a US news-intelligence platform.

What I do:
• AI/ML — production PyTorch, LLM agents on AWS Bedrock, RAG (FAISS/pgvector), local LLMs (Ollama/Llama 3), evaluation pipelines, XGBoost/Optuna/SHAP
• Full-Stack — FastAPI, Django, Node.js, Nuxt.js, Next.js, ASP.NET Core, React 19
• Mobile — React Native and Flutter (apps shipped to real users, incl. a school system used by 40 schools)

I like building things that reach production: multi-agent systems, LLM tooling with real evals, and apps people actually use.

Open to junior/graduate roles in AI engineering, LLM agents & automation, full-stack, or mobile.

📫 arnobrizwan23@gmail.com  |  🌐 Portfolio: https://arnobrizwan.github.io  |  GitHub: https://github.com/Arnobrizwan
```

## 3) EXPERIENCE — add/update these 5 roles

**Role A**
- Title: `Application Developer`
- Company: `Moien Delivery`
- Employment type: `Full-time` (or Contract — set to Contract if it isn't a permanent role)
- Location: `Luxembourg` · Remote
- Start: `March 2026` · End: `Present`
- Description:
```
Hybrid logistics platform serving customers, restaurants, and drivers.
• Building a cross-platform mobile app with React Native and a Nuxt.js backend, delivering features for three distinct user roles.
• Implementing real-time order tracking, driver dispatch, and delivery workflows over REST APIs and WebSocket event streams.
• Owning features spec → QA → production on weekly release cycles with international stakeholders.
Stack: React Native, Nuxt.js, REST, WebSockets
```

**Role B**
- Title: `Machine Learning Engineer`
- Company: `AI News HUD` (Employment type: `Contract`; note "via Mercor" in description)
- Location: `United States` · Remote
- Start: `October 2025` · End: `March 2026`
- Description:
```
US-based AI-powered news intelligence platform (contract via Mercor).
• Built and evaluated production PyTorch models for real-time news classification, summarization, and personalized recommendations.
• Designed evaluation pipelines and ran iterative experiments improving model accuracy and inference latency on live traffic.
• Took ML components from prototype to deployed feature in the platform's core intelligence layer.
Stack: PyTorch, evaluation pipelines, NLP
```

**Role C**
- Title: `Founding Backend Engineer`
- Company: `Framic`
- Employment type: `Part-time` (adjust if full-time)
- Location: Remote
- Start: `August 2025` · End: `Present`
- Description:
```
• First backend hire on an AI-powered storage application — owning architecture decisions and core API design from scratch.
• Leading development of AI search, real-time indexing, and scalable systems for gallery and drive functionality.
• Working directly with founders to ship features rapidly while keeping the system maintainable as the team scales.
```

**Role D**
- Title: `Software Engineer (Contributor)`
- Company: `MOMS Mobile Oil Change` (if not on LinkedIn, list as Freelance/Self-employed and name MOMS in the description)
- Employment type: `Freelance`
- Location: `United States` · Remote
- Start: `April 2026` · End: `Present` (or May 2026 — use the month of my first commit if known; otherwise 2026)
- Description:
```
Contributor to the production Next.js website for a US mobile oil change & fleet maintenance business (momsoilchange.com).
• Redesigned the site header/navigation — active-route highlighting, hover dropdowns, prominent phone CTA — and rebuilt three product pages.
• Led an SEO overhaul: dynamic sitemap route, 301 redirects for legacy city URLs, and consolidation onto /locations/[city] dynamic routing.
• Ran a site-wide security, dependency, and code-quality audit pass and repaired production-build breakages.
Stack: Next.js, React, TypeScript
```

**Role E**
- Title: `Software Engineering Resident`
- Company: `Headstarter`
- Employment type: `Internship` (or Apprenticeship)
- Location: `United States` · Remote
- Start: `September 2024` · End: `March 2025`
- Description:
```
Selected for a competitive 6-month US-based engineering residency.
• Shipped 14+ ML and full-stack projects in Python and TypeScript.
• Designed and trained 5 neural networks applying LLM chaining, hyperparameter tuning, and model fine-tuning.
• Built LLM-powered agents on AWS Bedrock / OpenAI APIs and optimized Docker CI/CD on GitHub Actions, reducing image size and build times.
```

## 4) PROJECTS — add each as a LinkedIn Project (Profile → Add section → Recommended → Add projects). For ones with a public link, paste the URL.

1. **Autonomous ML Agent** — `https://github.com/Arnobrizwan/Autonomous-ML-Agent`
```
LLM-planned AutoML pipeline: an LLM planner proposes modeling strategies under a time budget, Optuna tunes XGBoost/LightGBM/scikit-learn models, ensembles are built, and SHAP explains the winner. Ships a FastAPI inference service, model cards, 5 pytest suites, and CI/CD pushing to Docker Hub. Python · Optuna · SHAP · FastAPI · Docker.
```

2. **ZeroWaste Hub** — `https://github.com/Arnobrizwan/ZeroWaste-Hub`
```
Cross-platform Flutter food-rescue app for Malaysia connecting donors, recipients, and volunteer riders. Gemini Vision grades dish quality and halal status, an on-device TensorFlow Lite classifier caches its own model, with Checkout.com/TNG eWallet payments and 4-language support. Release APK published. Flutter · Gemini · TFLite · Firebase.
```

3. **CrisisCohort** — `https://github.com/Arnobrizwan/-CrisisCohort`
```
Multi-agent AI climate-resilience platform for smallholder farmers — 10+ specialized AWS Bedrock agents (water optimization, climate migration, grant matching, disease diagnostics) over 15,000+ lines of Lambda, plus an on-chain water-rights trading contract in Solidity. AWS Bedrock · Lambda · DynamoDB · Solidity.
```

4. **EcoSphere AI Farming Simulator** — `https://github.com/Arnobrizwan/ecosphere-ai-farming-simulator`
```
React Native farming simulator running on live NASA satellite data — SMAP soil moisture, MODIS NDVI, and IMERG rainfall feed a RandomForest forecaster, with Gemini-powered NPC tutors that generate and grade farming questions. Campaign and sandbox game modes. React Native · NASA APIs · Gemini · TensorFlow.
```

5. **Terminal Coding Agent** — `https://github.com/Arnobrizwan/Terminal-Based-Coding-Agent`
```
Pip-installable CLI coding agent that plans edits via OpenAI/Anthropic, applies them through a diff manager, and executes inside E2B Firecracker microVMs. Includes guardrails that scan for six secret types (AWS, GitHub, Slack keys) and 5 pytest suites. Python · E2B · OpenAI/Anthropic.
```

6. **Self-Improving Prompt Optimization API** — `https://github.com/Arnobrizwan/Self-Improving-Prompt-Optimization-Api`
```
CI/CD for prompts — a semver-versioned prompt registry where each improvement cycle runs failure analysis, generates candidates, A/B-evaluates them with a blinded LLM judge, and auto-promotes winners per YAML rules. Multi-dimensional scoring across OpenAI/Anthropic. FastAPI · Postgres · Redis.
```

7. **School Care App** (no public link — private client work)
```
Full-stack school management system adopted by 40 schools across Sylhet, Bangladesh (in closed testing ahead of Google Play launch). React admin dashboard + React Native app for parents and teachers, with Cloud Functions fanning out role-targeted FCM push by school, role, and class. React Native · Firebase · FCM.
```

8. **PhotoniX Research** — `https://photonixresearch.com`
```
Production website + admin CMS for a photonics research group. Eight public pages and a 9-screen JWT-protected admin panel managing publications, projects, team, news, and recruitment applications with CV uploads. Live in production. React · Express · MySQL.
```

9. **MentorMind** (no public link — private)
```
ML-powered EdTech platform built as a system-design showcase — nginx load-balancing two Django APIs, Postgres streaming read-replica with a custom DB router, Redis leaderboards, Celery queues, and a DVC-tracked MLOps loop with OpenCV proctoring, k6 load tests, and Kubernetes manifests with autoscaling. Django · Kubernetes · DVC.
```

10. **Savora RMS** (no public link — private)
```
Restaurant management system on ASP.NET Core (.NET 10) + React 19 — POS with modifier-aware cart logic, kitchen display, inventory, and reservations across 12 pages, with every KPI (revenue, food/labor cost, channel mix) computed server-side from SQL Server. .NET 10 · React 19 · SQL Server.
```

(Optional extras if I want more depth: ScholarMind — local Llama 3 RAG research assistant; Qawel — WhatsApp-style construction PM with EN/AR/UR auto-translation; Sushthotha — bilingual mental-wellness platform; Agritech — Bangladesh rice supply chain with XGBoost yield prediction.)

## 5) SKILLS — add these (LinkedIn → Add skills). Aim to pin the top 3 as the featured ones.

Pin as top 3: `Machine Learning`, `Large Language Models (LLM)`, `Full-Stack Development`

Add the rest:
```
PyTorch, Python, TypeScript, React Native, Flutter, FastAPI, Next.js, Node.js, Django, AWS, AWS Bedrock, Amazon Web Services (AWS), Retrieval-Augmented Generation (RAG), Prompt Engineering, Multi-Agent Systems, XGBoost, scikit-learn, Docker, Kubernetes, Firebase, PostgreSQL, REST APIs, WebSockets, Git, CI/CD, Computer Vision, Natural Language Processing (NLP)
```

## 6) EDUCATION

```
Universiti Teknologi Malaysia (UTM)
Bachelor of Software Engineering
Expected July 2026
Johor Bahru, Malaysia
```

## 7) LICENSES & CERTIFICATIONS — add both

```
AWS — Amazon SageMaker, Large Language Models, Prompt Engineering | Amazon Web Services | Issued Mar 2025
Microsoft Azure AI — Azure OpenAI Service, NLP, Document Intelligence | Microsoft | Issued Jun 2024
```

## 8) FEATURED — add my portfolio as a featured link

```
Link: https://arnobrizwan.github.io
Title: My Portfolio — AI/ML × Full-Stack × Mobile
Description: 20 code-audited projects, experience across 4 countries, and my resume.
```

## 9) CONTACT INFO

- Add website: `https://arnobrizwan.github.io` (type: Portfolio)
- Add GitHub: `https://github.com/Arnobrizwan`
- Email: `arnobrizwan23@gmail.com`

---

When done, give me a checklist of what you updated vs. anything you couldn't (e.g. a company page that doesn't exist on LinkedIn, a field with a character limit you had to trim). Do not change my profile photo, banner, name, or connections.
```

---

# 📱 Mobile App Version (LinkedIn iOS / Android)

The LinkedIn mobile app's editor is laid out differently from the web — use this version if you're driving the **LinkedIn app** instead of the browser. Same content as above; only the navigation differs.

Copy everything below the line into a Cowork agent that controls my phone / the LinkedIn mobile app.

---

You are editing my LinkedIn profile **in the LinkedIn mobile app** (already logged in as Arnob Rizwan Ahmad). Navigation differs from the web — follow these app-specific paths. All content to enter is in the "CONTENT" blocks; do not invent anything. After each section, tell me what changed. Do not touch my photo, banner, name, or connections.

**Navigation map (mobile app):**
- To reach my profile: tap my **profile photo** (top-left) → **View Profile**.
- To edit a section: tap the **pencil icon** next to that section, or scroll to it and tap **Edit**.
- To add a new section: tap **Add section** (button under the headline) → choose the category (Core / Recommended / Additional).
- Headline & name live under the pencil on the top **intro** card.
- Save with the **checkmark** (top-right) or **Save** button after each edit.

**Do the sections in this order:**

### 1. Headline
Profile → pencil on intro card → **Headline** field. Replace with:
```
AI/ML Engineer • Full-Stack & Mobile | Production PyTorch & LLM Agents | React Native · Flutter · FastAPI · AWS | SWE @ UTM (Grad July 2026) | Open to AI Engineering roles
```
(If it exceeds the limit, trim from the end but keep "AI/ML Engineer" and "Open to AI Engineering roles".)

### 2. About
Add section → **Core → About** (or pencil the existing About). Paste the ABOUT block from the web version above (Section 2). On mobile the field scrolls — paste the whole thing; it accepts line breaks.

### 3. Experience (Add position)
Add section → **Core → Add position**, once per role. Enter all 5 roles from Section 3 above (Moien Delivery, AI News HUD, Framic, MOMS, Headstarter) using the same Title / Company / Type / Location / Dates / Description. On mobile: toggle **"I am currently working in this role"** for Present roles; the End-date picker hides when that toggle is on.

### 4. Projects
Add section → **Recommended → Add projects** (if not visible, tap **Additional → Projects**). Add each of the 10 projects from Section 4 above. On mobile the link field is **"Project URL"** — paste the GitHub/live link for ones that have it; leave blank for private ones. Associate each with the matching Experience/role if the app prompts.

### 5. Skills
Add section → **Core → Add skills**. Type each skill from Section 5 and tap it from the dropdown (mobile only adds skills that match its autocomplete — if one doesn't appear, skip it and tell me which). Then go to the **Skills** section → **Reorder/Show top skills** → pin `Machine Learning`, `Large Language Models (LLM)`, `Full-Stack Development` as the top 3.

### 6. Education
Add section → **Core → Add education**. Enter the Education block from Section 6 (UTM, B.Sc. Software Engineering, expected July 2026).

### 7. Licenses & Certifications
Add section → **Recommended → Add licenses & certifications**. Add both certs from Section 7 (AWS Mar 2025, Microsoft Azure AI Jun 2024).

### 8. Featured
Add section → **Recommended → Add featured → Links**. Add `https://arnobrizwan.github.io` with the title and description from Section 8. (On mobile, Featured links pull their own preview image automatically — that's fine.)

### 9. Contact info
Profile → **Contact info** (pencil on the intro card, then "Edit contact info") → add Website `https://arnobrizwan.github.io` (type: Portfolio), and email `arnobrizwan23@gmail.com`.

**Mobile gotchas to watch for:**
- The app sometimes shows a trimmed character counter — if a description gets cut, tell me which role/project and I'll give you a shorter version.
- If "Add projects" isn't offered in your app version, projects can also be added as bullet lines inside the relevant Experience description instead — ask me before doing that.
- Some niche skills (e.g. "AWS Bedrock") may not be in mobile autocomplete; add the closest match ("Amazon Web Services (AWS)") and list the rest in my About.

When done, give me the same checklist: updated vs. couldn't, and any skills/fields the mobile app refused.

