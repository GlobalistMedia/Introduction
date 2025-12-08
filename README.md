![Auto Assign](https://github.com/GlobalistMedia/demo-repository/actions/workflows/auto-assign.yml/badge.svg)

# 🌍 Welcome to the Globalist LLC

**Globalist Media** is a vertically integrated media technology ecosystem powering digital storytelling, content operations, and modern news consumption. This repository serves as a functional demonstration of our core platform infrastructure and how we leverage GitHub for collaborative development and CI/CD workflows.

---

## 🚀 About Globalist

We build tools for the next generation of media professionals — from solo content creators and nonprofit communicators to full-scale publishing operations.

Our platform is organized into four interdependent systems:

---

## 📰 Globalist Live  
**Purpose**: Social-first, nonpartisan media aggregation with original journalism and curated stories.  
**Highlights**:
- Personalized newsfeeds
- AI-powered summaries & newsletters
- Real-time updates from credible sources
- Syndicated publishing and exclusive content  
**Audience**: General public, casual news consumers, civic readers

🌐 URL: [globalist.live](https://globalist.live)

---

## 🧠 Globalist HQ  
**Purpose**: The official marketing and storytelling gateway of Globalist.  
**Highlights**:
- Central hub for nonprofit storytelling services
- Asynchronous content intake process
- Brand mission, team, and services
- Subscription-based content offerings  

🌐 URL: [hq.globalist.live](https://hq.globalist.live/)

---
## 🧠 Globalist Storytelling  
**Purpose**: A creative hub for mission-driven storytelling and digital narratives.  

**Highlights**:  
- Dedicated space for social impact stories and brand campaigns  
- Seamless content collaboration with clients (intake + review workflows)  
- Showcases projects, team, and creative process  
- Subscription-based storytelling packages (monthly/quarterly)  

🌐 URL: [brands.globalist.live](https://brands.globalist.live/) 

---
## 📊 Globalist Media Suite (Coming Q3 2025)  
**Purpose**: A creator-first SaaS platform for producing, managing, and distributing digital content across channels.  
**Core Modules**:
- ✍️ Content Editor (AI-Enhanced)
- 📅 Editorial Calendar & Workflow Manager
- 📣 Social Media Automation
- 💸 Monetization Tools (donations, subscriptions, gated content)
- 📈 Performance Analytics  
**Target Audience**: Freelancers, editorial teams, nonprofit communications leads

🌐 Early Access: [media.globalist.live](https://media.globalist.live)

---

## ⚙️ Admin Dashboard  
**Purpose**: Internal CMS and operations control panel for the Globalist team.  
**Use Cases**:
- User management & permissions
- Review + moderation queues
- Newsletter workflows
- Syndication + publishing controls
- System health monitoring

Access: Private only (Restricted by role) [admin.globalist.live](https://admin.globalist.live)

---

##  Branching Strategy & Environments

To improve our development workflow and code quality, we are adopting a branching strategy with two main branches:

- **dev**: All new features and updates are pushed here first. This branch is deployed to a staging/QA environment where the team and QA can test and verify changes before production.
- **main** (or **master**): This branch contains production-ready, stable code. Only thoroughly tested and approved changes from `dev` are merged here for production release.

**Branch Protections:**
- Both `main` and `dev` branches are protected to prevent accidental direct merges or force pushes. All changes should go through pull requests and code review.

**Workflow:**
1. Developers create feature branches from `dev`.
2. Once a feature is complete, open a PR into `dev` for review and testing.
3. The `dev` branch is automatically deployed to a staging/QA environment.
4. After successful QA, changes are merged from `dev` into `main` for production deployment.

**Syncing Branches:**
After any PR is merged from `dev` to `main`, we immediately sync `dev` with the latest changes from `main`. This ensures both branches remain up to date and prevents divergence.

This process ensures higher code quality and safer releases.



## 📦 Technologies Used

- **Frontend**: Next.js (Live, HQ, Media Suite)
- **Backend**: Nest.js
- **Database**: MongoDB
- **Auth**: Firebase / Clerk.dev
- **Deployment**:  AWS
- **AI Tools**: OpenAI, custom NLP models

---

## 🧪 Status

We are currently in:
- ✅ **Phase 2** for Globalist Live
- 🛠 **V1 development** of Media Suite
- ✅ **Launched**: Globalist HQ (Marketing & Intake)
- ✅ **Launched**: Globalist storytelling (Marketing & Intake)

---

## 📫 Contributing / Feedback

This demo repository is maintained by the Globalist DevOps team.
If you're contributing or testing pipelines, please follow standard PR and code review procedures.

For feedback, please email: [Team@globalist.live](mailto:Team@globalist.live)

---

## 🔐 License

© 2025 Globalist LLC. All rights reserved.

