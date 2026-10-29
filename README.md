<h1 align="center">Saad Waseem</h1>
<h3 align="center">Backend and Cloud Engineer | Lahore, Pakistan</h3>

<p align="center">
  <a href="https://saadops.site"><img src="https://img.shields.io/badge/Portfolio-saadops.site-2ea44f?style=for-the-badge&logo=googlechrome&logoColor=white"></a>
  <a href="https://linkedin.com/in/saadwaseemcloud"><img src="https://img.shields.io/badge/LinkedIn-saadwaseemcloud-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
</p>

---

## About me

I am a backend and cloud engineer who builds REST APIs with Django and Django REST Framework, and then takes them all the way to production on AWS. I care about the full path of a project: clean backend code, containerized builds, automated deployments, and infrastructure that can be recreated from code instead of clicked together by hand.

For the past couple of years I have worked with international clients in the United States and Portugal, delivering websites, backends, and deployments remotely. I am currently interning as a Backend AI Engineer at FlyRank AI, finishing my final-year project (openVault), and building the frontend of a learning platform for a freelance client.

I am looking for a junior Backend (Django/DRF) or junior-to-mid DevOps/Cloud role where I can work inside a real team, get code reviews, and keep growing.

---

## Tech stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/DRF-ff1709?style=flat-square&logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

**Backend:** Python, Django, Django REST Framework, JWT authentication, role-based access control, PostgreSQL, Swagger/OpenAPI documentation

**Cloud and infrastructure:** AWS (EC2, RDS, S3, ECR, CloudFront, Route 53, IAM), Terraform, Docker, Nginx, Gunicorn, Linux server administration, DNS and SSL/TLS

**Delivery:** GitHub Actions CI/CD, Docker image builds, automated deployments

**Frontend (when a project needs it):** Next.js, TypeScript, Tailwind CSS

---

## Professional experience

**Backend AI Engineer Intern, FlyRank AI** (August 2026 to present)
Remote, team-based work on backend and AI-related features.

**DevOps Engineer, thinkwell** (June 2026 to August 2026)
Deployed and managed a production Node.js backend on AWS EC2 using Docker, PM2, Nginx, and Redis. Handled DNS and SSL/TLS configuration, AMI creation, and a server migration, and debugged issues in a live production codebase as part of a remote team.

---

## Freelance experience

I have delivered paid projects for clients in the United States and Portugal, working remotely across time zones. In each engagement I handled everything from requirements to deployment: talking to the client directly, building the solution, setting up hosting and domains, and handing over something that runs live.

- **CP MI learning platform** (frontend, ongoing): see the project below.
- **Game publisher website** (Portugal-based client): a themed website with a Renaissance-meets-modern art direction. See Leo below.
- **Church organization website** (United States, November 2025 to March 2026): a custom multi-page site and a WordPress CMS, including domain registration, DNS, and deployment, with regular coordination across a time-zone gap. See Church Triple C below.
- **Themed web platform** (frontend, April 2026): a gaming-themed website built for a freelance client.
- **2D adventure game in Unity** (Portugal-based client): player mechanics, enemy behavior, UI, and scene management, delivered as a paid product.

---

## Projects

### openVault: private AI knowledge base (final-year project, growing into a startup)

Companies keep their knowledge in scattered documents, and employees waste time searching them or end up pasting sensitive files into public AI tools. openVault gives each organization a private vault. Staff upload documents (PDF, DOCX, PPTX, Markdown, text), ask questions in plain language, and receive streamed answers with cited source passages.

- Multi-tenant design: every company's data is isolated from every other company's
- Role-based access (admin, employee, viewer, public consumer), controlled sharing across companies with revoke, and an optional public library
- Audit trail of access and API activity
- Switchable AI provider (local Ollama, OpenAI, Anthropic, or Gemini), with a keyword-search fallback if embeddings are unavailable
- Stack: Django 5, DRF, SimpleJWT, Next.js, React, TypeScript, Tailwind CSS
- Status: the product is nearly finished and in the testing and bug-fixing phase. Live at [openvault.saadops.site](https://openvault.saadops.site)

### CP MI: learning and certification platform (freelance, in progress)

A platform where an administrator publishes courses, called "seeds," and agencies or companies sign in to assign those seeds to their learners. Learners study the material, answer MCQs, take tests and mock exams, and earn certificates. I am building the frontend; the backend is a separate service that is already live and under testing. The frontend is deployed on Vercel.

- Stack: Next.js, TypeScript, Vercel
- My role: the full user-facing frontend and its integration with the existing backend API

### Full-stack portfolio with cloud infrastructure

My portfolio at [saadops.site](https://saadops.site) is also a working example of my DevOps skills. The infrastructure is defined in Terraform, and every push to GitHub triggers an automated build and deployment.

- Frontend: Next.js
- Backend: Django REST API, containerized with Docker and served through Nginx and Gunicorn
- Infrastructure: AWS with Terraform, container images in ECR, a managed PostgreSQL database on RDS, and media storage on S3
- Delivery: GitHub Actions CI/CD, custom domain through Route 53 with HTTPS

### Showroom API: vehicle catalog backend

A Django REST backend for a car and vehicle catalog. Admins add vehicles with detailed information, and users can search, filter, and sort them. I built it to practice production-style API design.

- PostgreSQL full-text search, filtering, sorting, and pagination
- JWT authentication with role-based permissions
- Image processing and S3 media storage
- Wishlists, price-drop notifications, and soft delete
- A financing calculator with real amortization math
- Swagger documentation and a Docker setup

### Apothecary: full-stack application

A full-stack project built as separate frontend and backend repositories.

### Church CCC miracle parish: website for a church in Minnesota, USA

A freelance website that lets the congregation see upcoming events and which prayers and services take place at what time, and gives the church a clear place to present its information. Built for a US-based client and deployed live, including domain and DNS setup.

### Leo: game publisher website (freelance)

A website for a game publisher with a distinctive medieval-modern look inspired by Leonardo da Vinci's style. Delivered as a paid freelance project and deployed live at [leo-clone-five.vercel.app](https://leo-clone-five.vercel.app).

- Stack: Next.js, TypeScript, Vercel

### Smaller projects

- **Tab Wallpaper:** a Chrome extension for video and animated backgrounds on the new tab page
- **My first portfolio:** my original portfolio site, kept as a record of where I started

---

## How I work

- **Plan in small pieces.** I break a project into milestones that can each be deployed and shown, so clients and teammates see progress early and problems surface early.
- **Ship it, don't just write it.** I treat deployment as part of the job: Docker from the start, CI/CD for every project, and infrastructure kept in code wherever I can.
- **Communicate clearly.** Working with clients in different time zones taught me to write short status updates, state blockers early, and keep decisions written down.
- **Keep things documented.** Each project gets a README that explains what it is, how to run it, and how it is deployed.
- **Keep improving.** I am currently strengthening my automated testing with pytest and CI test stages, and my data structures and algorithms practice.

---

## What I am looking for

- A junior Backend role (Django/DRF) or a junior-to-mid DevOps/Cloud Engineer role
- A team where I can learn from code reviews and work alongside experienced engineers
- On-site in Lahore or remote
- Part-time freelance work on backend, API, and AWS deployment projects is also welcome

---

## Education

**BSc in Computer Science**, University of South Asia, Lahore (2023 to 2027)

---

## Get in touch

- Portfolio: [saadops.site](https://saadops.site)
- LinkedIn: [saadwaseemcloud](https://linkedin.com/in/saadwaseemcloud)
