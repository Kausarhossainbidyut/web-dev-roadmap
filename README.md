# 🌐 Full-Stack Web Developer Roadmap (2025)

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#-contributing)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](#-license)

এটি এমন একটি ওপেন-সোর্স রোডম্যাপ যা আপনাকে **Web Developer → Full-Stack Developer** হতে ধাপে ধাপে গাইড করবে। প্রতিটি ধাপের নিচে **official docs, টিউটোরিয়াল, টুলস** ও **রেফারেন্স লিংক** দেওয়া আছে—শুরু থেকে ডিপ্লয়মেন্ট পর্যন্ত।


---

## 📑 Table of Contents

* [🗺️ Learning Path at a Glance](#%EF%B8%8F-learning-path-at-a-glance)
* [🌱 Fundamentals](#-fundamentals)
* [🎨 Frontend Core](#-frontend-core)
* [⚛️ Frontend Frameworks](#%EF%B8%8F-frontend-frameworks)
* [🧩 Styling & UI](#-styling--ui)
* [🖥️ Backend](#%EF%B8%8F-backend)
* [🗄️ Databases & ORM](#%EF%B8%8F-databases--orm)
* [🔐 Auth & Security](#-auth--security)
* [📦 Tooling](#-tooling)
* [🧪 Testing](#-testing)
* [🔄 Data Fetching & Real-Time](#-data-fetching--realtime)
* [☁️ Deploy, DevOps & Monitoring](#%EF%B8%8F-deploy-devops--monitoring)
* [📈 Performance, SEO & A11y](#-performance-seo--a11y)
* [🌍 Internationalization (i18n)](#-internationalization-i18n)
* [🧠 CS Fundamentals & System Design](#-cs-fundamentals--system-design)
* [🎯 Project Ideas](#-project-ideas)
* [📚 Resource Directory (All-in-One)](#-resource-directory-all-in-one)
* [🧭 How to Use](#-how-to-use)
* [🤝 Contributing](#-contributing)
* [🪪 License](#-license)

---

## 🗺️ Learning Path at a Glance

**0–3 মাস**: HTML, CSS, JS বেসিক, Git, Responsive Design  
**4–6 মাস**: React + Next.js, API consumption, State management, Simple backend (Node/Express)  
**7–12 মাস**: Database + Auth + Testing + CI/CD + Docker + Production deploy  

> টার্গেট: ৩–৪টি প্রজেক্ট end-to-end (Frontend + Backend + DB + Deploy)

---

## 🌱 Fundamentals

* **HTML** – Structure of webpages
* **CSS** – Styling with Flexbox/Grid
* **JavaScript (ES6+)** – Core syntax, DOM, async/await
* **Git & GitHub** – Version control
* **DevTools** – Debugging with Chrome/Edge DevTools

🔗 **Resources:**
- [MDN HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)  
- [MDN CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)  
- [JavaScript.info](https://javascript.info/)  
- [Git Docs](https://git-scm.com/doc)  
- [DevTools](https://developer.chrome.com/docs/devtools/)

---

## 🎨 Frontend Core

* Responsive Design (Mobile-first, Flexbox, Grid)
* Modern JS (modules, fetch, promises)
* Accessibility basics (semantic HTML, ARIA)
* Package managers (npm/yarn/pnpm)

🔗 **Resources:**
- [FreeCodeCamp Responsive Web Design](https://www.freecodecamp.org/learn/responsive-web-design/)  
- [MDN JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)  
- [npm Docs](https://docs.npmjs.com/)  
- [pnpm](https://pnpm.io/)  
- [Yarn](https://yarnpkg.com/)

---

## ⚛️ Frontend Frameworks

* **React** – Components, hooks, context
* **Next.js** – SSR/SSG, routing, API routes, image optimization
* **State** – Redux Toolkit / Zustand / Context
* **Data** – TanStack Query (React Query)
* **Routing** – React Router / Next.js App Router

🔗 **Resources:**
- [React](https://react.dev/)  
- [Next.js](https://nextjs.org/docs)  
- [Redux Toolkit](https://redux-toolkit.js.org/)  
- [TanStack Query](https://tanstack.com/query/latest)  
- [React Router](https://reactrouter.com/)

---

## 🧩 Styling & UI

* **CSS Architecture** – BEM, Utility-first
* **Tailwind CSS** + UI kits
* **Component Libraries** – দ্রুত consistent UI

🔗 **Resources:**
- [Tailwind CSS](https://tailwindcss.com/)  
- [daisyUI](https://daisyui.com/)  
- [shadcn/ui](https://ui.shadcn.com/)  
- [Material UI](https://mui.com/)  
- [Chakra UI](https://chakra-ui.com/)  
- [Ant Design](https://ant.design/)  
- [Bootstrap](https://getbootstrap.com/)  
- [UI Layout tools](https://tools.ui-layouts.com/)  
- [Sera UI components](https://seraui.seraprogrammer.com/)

---

## 🖥️ Backend

* **Node.js + Express.js** – REST API, middleware, error handling
* **Validation** – Zod/Yup, JOI
* **GraphQL (optional)** – Apollo Server
* **API Design** – versioning, rate limiting, pagination
* **OpenAPI/Swagger** & Postman collections

🔗 **Resources:**
- [Node.js](https://nodejs.org/en/docs/)  
- [Express](https://expressjs.com/)  
- [Swagger Spec](https://swagger.io/specification/)  
- [Swagger Editor](https://editor.swagger.io/)  
- [Postman](https://learning.postman.com/)

---

## 🗄️ Databases & ORM

* **Relational (SQL):** PostgreSQL, MySQL
* **NoSQL:** MongoDB
* **ORM/ODM:** Prisma, TypeORM, Mongoose
* Migrations, indexing, transactions, backups

🔗 **Resources:**
- [PostgreSQL](https://www.postgresql.org/docs/)  
- [MySQL](https://dev.mysql.com/doc/)  
- [MongoDB](https://www.mongodb.com/docs/)  
- [Prisma](https://www.prisma.io/docs/)  
- [Mongoose](https://mongoosejs.com/)

---

## 🔐 Auth & Security

* **Auth flows:** Email/password, OAuth2, social login
* **Libraries:** Auth.js, Firebase Auth, Passport
* **Tokens:** JWT, refresh tokens, cookies, CSRF
* **Best practices:** Hashing, CORS, HTTPS/TLS, secrets management
* **Security:** OWASP Top 10

🔗 **Resources:**
- [Auth.js](https://authjs.dev/)  
- [Firebase Auth](https://firebase.google.com/docs/auth)  
- [Passport](https://www.passportjs.org/)  
- [JWT Intro](https://jwt.io/introduction)  
- [OAuth 2.0](https://oauth.net/2/)  
- [OWASP Top 10](https://owasp.org/www-project-top-ten/)

---

## 📦 Tooling

* **Build:** Vite, Webpack, Babel
* **Lint/Format:** ESLint, Prettier
* **Env:** dotenv
* **CLI Tips:** npx, scripts, turbo (optional)

🔗 **Resources:**
- [Vite](https://vitejs.dev/)  
- [Webpack](https://webpack.js.org/)  
- [Babel](https://babeljs.io/)  
- [ESLint](https://eslint.org/)  
- [Prettier](https://prettier.io/)

---

## 🧪 Testing

* **Unit:** Jest, Vitest
* **Component:** React Testing Library
* **E2E:** Cypress / Playwright
* **API:** Supertest, Pact

🔗 **Resources:**
- [Jest](https://jestjs.io/docs/getting-started)  
- [Vitest](https://vitest.dev/)  
- [RTL](https://testing-library.com/docs/react-testing-library/intro/)  
- [Cypress](https://docs.cypress.io/)  
- [Playwright](https://playwright.dev/)  
- [Supertest](https://github.com/ladjs/supertest)

---

## 🔄 Data Fetching & Real-Time

* **HTTP:** Fetch API, Axios
* **Caching/Sync:** TanStack Query
* **Real-time:** WebSocket API, Socket.IO, SSE

🔗 **Resources:**
- [Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)  
- [Axios](https://axios-http.com/)  
- [TanStack Query](https://tanstack.com/query/latest)  
- [WebSocket API](https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API)  
- [Socket.IO](https://socket.io/docs/)

---

## ☁️ Deploy, DevOps & Monitoring

* **Frontend Hosting:** Vercel, Netlify
* **Backend Hosting:** Render, Railway, Fly.io
* **Containers:** Docker basics
* **CI/CD:** GitHub Actions
* **Reverse proxy:** Nginx
* **Monitoring/Logs:** Sentry, Winston/Logtail
* **CDN & Assets:** Image optimization, caching

🔗 **Resources:**
- [Vercel](https://vercel.com/docs)  
- [Netlify](https://docs.netlify.com/)  
- [Render](https://render.com/docs)  
- [Railway](https://docs.railway.app/)  
- [Fly.io](https://fly.io/docs/)  
- [Docker](https://docs.docker.com/)  
- [GitHub Actions](https://docs.github.com/actions)  
- [Nginx](https://nginx.org/en/docs/)  
- [Sentry](https://docs.sentry.io/)

---

## 📈 Performance, SEO & A11y

* **Performance:** Lighthouse, Core Web Vitals
* **SEO:** Sitemaps, meta tags, structured data
* **Accessibility:** WCAG, keyboard nav, color contrast

🔗 **Resources:**
- [web.dev](https://web.dev/vitals/)  
- [Lighthouse](https://developer.chrome.com/docs/lighthouse/overview/)  
- [Google Search Central](https://developers.google.com/search/docs)  
- [WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/)  
- [WebAIM](https://webaim.org/)

---

## 🌍 Internationalization (i18n)

* i18next / react-i18next
* Message formatting & locale data
* RTL support (Arabic/Hebrew)

🔗 **Resources:**
- [i18next](https://www.i18next.com/)  
- [react-i18next](https://react.i18next.com/)

---
## 🧠 CS Fundamentals & System Design

* Big-O, data structures, algorithms
* Caching, queues, pub/sub, rate limiting
* CAP theorem, consistency models
* 12-Factor App

🔗 **Resources:**
- [System Design Primer](https://github.com/donnemartin/system-design-primer)  
- [12-Factor App](https://12factor.net/)

---

## 🎯 Project Ideas

* Blog (MERN) – CRUD, auth, comments
* E-commerce – cart, payments (Stripe/PayPal), orders
* Social app – profiles, follows, feeds
* Chat app – WebSocket/Socket.IO, typing indicators
* SaaS dashboard – charts, filters, role-based access

---

## 📚 Resource Directory (All-in-One)

## English Spokeng Corse
-**English Spokeng Learn** [English Spokeng](https://www.learnvern.com/spoken-english-course/understanding-sentences-in-english?show_calendar_popup=1)
-**MERN Stack** [Mern stack with GP Academy](https://www.grameenphone.academy/courses/full-stack-development-with-mern)


## 🛠 Developer Productivity Tools
- **Editor**: [VS Code](https://code.visualstudio.com/)  
### Extensions: 
- ESLint,
- Prettier,
- GitLens,
- Tailwind IntelliSense ||
- Code Spell Checker,
- Tailwind CSS IntelliSense,
- Search node_modules,
- Reactjs code snippets,
- React Extension Pack,
- Path Intellisense,
- npm Intellisense,
- Material Icon Theme,
- Live Server,
- JavaScript (ES6) code snippets,
- ESLint,
- Error Lens,
- Code Runner,
- CMake Tools....
- CodeRabbit,
  ### API Testing:
  - Postman,
  - Insomnia  
 ### Database GUI: 
 - TablePlus,
 - MongoDB Compass  
  ### Browser Extensions: 
  - React DevTools,
  - Redux DevTools  

---

## 💼 Career & Job Prep
- Build a **portfolio** with 3–5 solid full-stack projects  
- Write **case studies** in project READMEs  
- Apply to jobs/internships/freelance platforms  
- **Interview Prep**:  
  - [LeetCode](https://leetcode.com/problemset/)  
  - [HackerRank](https://www.hackerrank.com/domains/tutorials/10-days-of-javascript)  
  - [System Design Primer](https://github.com/donnemartin/system-design-primer)  

---

## 🌐 Community & Networking
- **Communities**: Reddit (/r/webdev), Dev.to, Hashnode  
- **Q&A**: Stack Overflow  
- **Discord/Slack**: JavaScript/React/MERN communities  

---

## 📚 Resources & References
### 📖 Courses
- [freeCodeCamp](https://www.freecodecamp.org/)  
- [The Odin Project](https://www.theodinproject.com/)  
- [Frontend Mentor](https://www.frontendmentor.io/)  

### 📘 Docs & References
- [MDN Web Docs](https://developer.mozilla.org/)  
- [W3Schools](https://www.w3schools.com/)  
- [React Official Docs](https://react.dev/)  
- [Node.js Docs](https://nodejs.org/en/docs)  
- [Express Docs](https://expressjs.com/)  

### 🎨 UI Libraries
- [TailwindCSS](https://tailwindcss.com/)  
- [Bootstrap](https://getbootstrap.com/)  
- [Material UI](https://mui.com/)
- [material-u](https://mui.com/material-ui/react-autocomplete/)
- [ui.shadcn](https://ui.shadcn.com/docs/installation)

---

## 🤝 Contributing
Contributions are welcome 🎉  

1. Fork this repo  
2. Create your feature branch (`git checkout -b feature/your-feature`)  
3. Commit changes (`git commit -m "Add new resource"`)  
4. Push to branch (`git push origin feature/your-feature`)  
5. Open a Pull Request  

---

## Image Generator AI
- [✔ playground](https://playground.com/)
- [✔ creator.nightcafe](https://creator.nightcafe.studio/)
- [✔ bing](https://www.bing.com/images/create)
- [✔ dream.ai](https://dream.ai/)
- [✔ craiyon](https://www.craiyon.com/en)
- [recraft.ai](https://www.recraft.ai/projects)

## Project set-up
1. [✔ Vite](https://vite.dev/guide/)
2. [✔ React Router](https://reactrouter.com/)
3. [✔ React Icons](https://react-icons.github.io/react-icons/)
4. [✔ Tailwind CSS](https://tailwindcss.com/)
5. [✔ DaisyUI](https://daisyui.com/)
6. [✔ Firebase](https://firebase.google.com/)
7. [✔ Netlify](https://app.netlify.com/)
8. [✔ ImgBB](https://imgbb.com/)
9. [✔ Express.js](https://expressjs.com/)
10. [✔ Nodemon](https://www.npmjs.com/package/nodemon)
11. [✔ MongoDB Node Driver](https://www.mongodb.com/docs/drivers/node/current/)
12. [✔ MongoDB Cloud Login](https://account.mongodb.com/account/login?n=https%3A%2F%2Fcloud.mongodb.com%2Fv2%2F68261c35a5a0cb63c25e9282&nextHash=%23metrics%2FreplicaSet%2F68261da74ce7ee1f14b1a4da%2Fexplorer%2Fusersdb%2Fusers%2Ffind&signedOut=true)

### Design Idea
13. [✔ ThemeForest Templates](https://themeforest.net/?srsltid=AfmBOooT7j1ROKF5NEHrh3I-lxZXxb22tRy6LKgsVTq3sZsSSqLXpFVp)
14. [✔ Hostinger Auth/Login](https://auth.hostinger.com/login?redirectUrl=https%3A%2F%2Fhorizons.hostinger.com%2F73fc2e3f-3100-440c-ac3c-a831f9f59332)

## Animation
1. [✔ LottieFiles](https://lottiefiles.com/)
2. [✔ Lottie React](https://www.npmjs.com/package/lottie-react)
3. [✔ Framer Motion](https://motion.dev/docs/react)

## Free Image Resources
- [✔ Freepik](https://www.freepik.com/)
- [✔ Icons8](https://icons8.com/)

## Ai premium
- [Ai](https://beta.lmarena.ai/?mode=direct)

## TypeScript Note
- **TypeScript** [TypeScript](https://developer-zahir.notion.site/TypeScript-1e5c503b15a98035848bdfc22b66d136?fbclid=IwQ0xDSwMC7HJleHRuA2FlbQIxMAABHmZ_by20NURi-Zq3SeWsDNiVDAjmL-1gu1P8SDeOEaY98r747RD2blX43g2j_aem_PU8HKIt01I3_rUSEe5nVcw )

## JavaScript Note
- **Javascript interview questions** [Javascript interview questions ](https://www.notion.so/Javascript-interview-questions-271e6b9c449a80039c79ca02b785ed72)
  

# Most importent rep all in one React Awesome
- [React-awesome](https://github.com/brillout/awesome-react-components)
- [ওয়েবসাইট ডিজাইন ইন্সপিরেশনের 3000+](https://devmeetsdevs.com/)
- [learn js with animetion](https://staying.fun/en/features/algorithm-visualize)

#Express.js
-[express]-(https://www.simplilearn.com/tutorials/nodejs-tutorial/getting-started-with-nodejs)
#Importent github repo
-[Best-websites-a-programmer-should-visit]-(https://github.com/sdmg15/Best-websites-a-programmer-should-visit)

🚀-[GitHub Year in Review make video website](https://githubunwrapped.com)
