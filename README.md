# Hi, I'm Shahbaz Ali

### Software Engineer | Full-Stack Developer | AI & Cloud

I build web applications, backend systems, cloud infrastructure, and AI-powered products.

My primary focus is **JavaScript/TypeScript, React, Node.js, AWS, and AI/LLM applications**.

[![GitHub](https://img.shields.io/badge/GitHub-AliShahbazzz-181717?style=for-the-badge\&logo=github)](https://github.com/AliShahbazzz)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Syed%20Shahbaz%20Ali-0A66C2?style=for-the-badge\&logo=linkedin)](https://linkedin.com/in/syed-shahbaz-ali)

---

## Tech Stack

### Frontend

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square\&logo=javascript\&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square\&logo=typescript\&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square\&logo=react)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square\&logo=react)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square\&logo=html5\&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square\&logo=css3\&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square\&logo=tailwindcss\&logoColor=white)
![MUI](https://img.shields.io/badge/MUI-007FFF?style=flat-square\&logo=mui\&logoColor=white)

### Backend & APIs

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square\&logo=node.js\&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square\&logo=python\&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square\&logo=fastapi\&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square\&logo=nestjs\&logoColor=white)
![LoopBack](https://img.shields.io/badge/LoopBack-3F5DFF?style=flat-square\&logo=loopback\&logoColor=white)

### AI / LLM

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square\&logo=chainlink\&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square\&logo=openai\&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square\&logo=pytorch\&logoColor=white)
![Hugging Face](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square\&logo=huggingface\&logoColor=black)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B6B?style=flat-square)

### Cloud & Infrastructure

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square\&logo=amazonaws\&logoColor=white)
![AWS Lambda](https://img.shields.io/badge/AWS_Lambda-FF9900?style=flat-square\&logo=awslambda\&logoColor=white)
![S3](https://img.shields.io/badge/Amazon_S3-569A31?style=flat-square\&logo=amazons3\&logoColor=white)
![CloudFront](https://img.shields.io/badge/CloudFront-FF9900?style=flat-square\&logo=amazonaws\&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square\&logo=docker\&logoColor=white)
![Serverless](https://img.shields.io/badge/Serverless-FD5750?style=flat-square\&logo=serverless\&logoColor=white)

### Databases & Data

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square\&logo=mysql\&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square\&logo=mongodb\&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square\&logo=amazondynamodb\&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B6B?style=flat-square)

### Tools

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square\&logo=git\&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square\&logo=githubactions\&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square\&logo=vite\&logoColor=white)
![Webpack](https://img.shields.io/badge/Webpack-8DD6F9?style=flat-square\&logo=webpack\&logoColor=black)
![Nx](https://img.shields.io/badge/Nx-143055?style=flat-square\&logo=nx\&logoColor=white)
![pnpm](https://img.shields.io/badge/pnpm-F69220?style=flat-square\&logo=pnpm\&logoColor=white)

---

# Featured Projects

## 1. meet-shahbaz-ai

**AI chatbot that answers questions about my background in first person, grounded in my resume.**

**Stack**

`React 19` · `TypeScript` · `Vite` · `Assistant UI` · `FastAPI` · `Python` · `LangChain` · `Groq` · `Llama 3.1` · `ChromaDB` · `FastEmbed` · `BM25` · `Cross-Encoder` · `Docker` · `Google Apps Script`

**Architecture**

```text
Resume
   ↓
Markdown Chunking
   ↓
FastEmbed ────────┐
                  ├── ChromaDB
BM25 Retriever ───┘
        ↓
Ensemble Retrieval
        ↓
Cross-Encoder Reranking
        ↓
Groq / Llama 3.1
        ↓
Streaming Response
        ↓
React Chat UI
```

[View Repository](https://github.com/AliShahbazzz/meet-shahbaz-ai)

---

## 2. shahbaz-ai

**An AI/agent experimentation project built around LangGraph and modern LLM tooling.**

**Stack**

`Python 3.11+` · `LangChain` · `LangGraph` · `LangGraph CLI` · `Groq` · `OpenAI` · `Hugging Face` · `Transformers` · `PyTorch` · `Requests` · `uv` · `Poetry`

[View Repository](https://github.com/AliShahbazzz/shahbaz-ai)

---

## 3. acumen-lambda

**Serverless AWS backend experimentation using TypeScript and the Serverless Framework.**

**Stack**

`TypeScript` · `Node.js` · `AWS Lambda` · `Serverless Framework v3` · `Middy` · `MongoDB/Mongoose` · `Google APIs` · `JWT` · `Nodemailer` · `dotenv` · `serverless-offline`

[View Repository](https://github.com/AliShahbazzz/acumen-lambda)

---

## 4. acumen

**React-based web application with animation and scroll-driven interactions.**

**Stack**

`React 18` · `TypeScript` · `Create React App` · `Sass` · `React Lenis` · `React Scroll Parallax` · `Jest/Testing Library` · `AWS S3` · `CloudFront`

[View Repository](https://github.com/AliShahbazzz/acumen)

---

## 5. acros

**React web application with API integration, authentication and rich UI animations.**

**Stack**

`React 18` · `JavaScript` · `Create React App` · `Material UI` · `Axios` · `Firebase` · `GSAP` · `React Router` · `React Icons` · `Tailwind CSS` · `HTML React Parser` · `AWS S3` · `CloudFront`

[View Repository](https://github.com/AliShahbazzz/acros)

---

## 6. ammogrips-soon-2

**A lightweight coming-soon landing page.**

**Stack**

`HTML5` · `CSS3` · `Responsive Web Design`

[View Repository](https://github.com/AliShahbazzz/ammogrips-soon-2)

---

## 7. copilot

**A modern React-based AI/chat interface.**

**Stack**

`React 19` · `TypeScript` · `Vite` · `Assistant UI` · `Tailwind CSS` · `PostCSS` · `ESLint` · `SWC`

[View Repository](https://github.com/AliShahbazzz/copilot)

---

# GitHub Statistics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=AliShahbazzz&show_icons=true&hide_border=true&include_all_commits=true&count_private=true" height="170" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AliShahbazzz&layout=compact&hide_border=true&langs_count=8" height="170" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=AliShahbazzz&hide_border=true" />
</p>

---

# Contribution Activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=AliShahbazzz&hide_border=true&area=true" width="100%" />
</p>

---

# GitHub Overview

<p align="center">

![Repositories](https://img.shields.io/badge/Repositories-25-181717?style=for-the-badge\&logo=github)
![Stars](https://img.shields.io/badge/Stars-3-181717?style=for-the-badge\&logo=github)
![Followers](https://img.shields.io/badge/Followers-1-181717?style=for-the-badge\&logo=github)

</p>

---

<p align="center">
  <a href="https://github.com/AliShahbazzz">
    <img src="https://komarev.com/ghpvc/?username=AliShahbazzz&style=for-the-badge&color=blue" alt="Profile views" />
  </a>
</p>

<p align="center">
  <i>Building things, learning continuously, and exploring what's possible with code.</i>
</p>
