# 🎓 Rumi — Personal Learning Dashboard & Recommendation Engine

Rumi is a modern, interactive, and AI-enhanced learning platform designed to streamline student progress and curate personalized academic paths. Built on top of **Next.js 14**, it delivers a seamless user experience, pairing a beautiful landing page with an analytical student dashboard and automated career roadmap guidance.

---

## 🚀 Features

### 1. **Personalized Career Recommender**
*   **Assessment Quiz:** A 7-step interactive diagnostic questionnaire evaluating student interest (AI, Data Science, Frontend, Backend), expertise level, weekly commitment, and learning style.
*   **Dynamic Roadmaps:** Recommends and embeds high-fidelity curated learning path roadmaps (PDF view) tailored to the student's primary area of interest.

### 2. **Analytical Student Dashboard**
*   **Performance Metrics:** Real-time visualization of student scores, grades, and progress metrics using customized **Recharts** visualizations.
*   **Course Progress Tracking:** Granular progress bars tracking current coursework, schedule, and assignments.
*   **Detailed Analytics:** Overview panels highlighting learning stats, recent activities, and upcoming calendar items.

### 3. **AI Chat Assistant**
*   **Botpress Integration:** Integrated virtual chatbot assistant to support students on their learning journey, answering queries and guiding them through their curriculum.

### 4. **Engaging Landing Page**
*   **Hero & Feature Showcase:** Sleek visual components showcasing key courses, trending career options, and client testimonials.
*   **Interactive Tech Cloud:** An animated, floating interactive icon cloud (powered by Magic UI) displaying modern web/AI technologies.

---

## 🛠️ Tech Stack

*   **Framework:** [Next.js 14 (App Router)](https://nextjs.org/)
*   **Language:** [TypeScript](https://www.typescriptlang.org/)
*   **Styling & UI Components:** 
    *   [Tailwind CSS](https://tailwindcss.com/)
    *   [Shadcn UI](https://ui.shadcn.com/) / [Radix UI](https://www.radix-ui.com/)
    *   [Magic UI](https://magicui.design/) (interactive icon cloud)
*   **Animations:** [Framer Motion](https://www.framer.com/motion/)
*   **Charts & Visualization:** [Recharts](https://recharts.org/)
*   **Forms & Validation:** [React Hook Form](https://react-hook-form.com/) & [Zod](https://zod.dev/)

---

## 📁 Key File Map & Links

Click on any of the core files below to navigate to it directly:

*   [app/layout.tsx](file:///c:/Users/vempa/Downloads/rumi1/app/layout.tsx) — Configures global font styles, CSS styling, and SEO metadata.
*   [app/page.tsx](file:///c:/Users/vempa/Downloads/rumi1/app/page.tsx) — Main landing page featuring interactive components, testimonials, and courses list.
*   [app/questions/page.tsx](file:///c:/Users/vempa/Downloads/rumi1/app/questions/page.tsx) — Interactive 7-step career recommender and PDF-based roadmap generator.
*   [app/(user)/dashboard/page.tsx](file:///c:/Users/vempa/Downloads/rumi1/app/(user)/dashboard/page.tsx) — Student workspace featuring progress cards, scores overview, charts, and chatbot panel.
*   [constants/index.ts](file:///c:/Users/vempa/Downloads/rumi1/constants/index.ts) — Key constant maps of courses, resources, and credentials.
*   [lib/utils.ts](file:///c:/Users/vempa/Downloads/rumi1/lib/utils.ts) — Tailwind CSS class name merging helper.
*   [LICENSE](file:///c:/Users/vempa/Downloads/rumi1/LICENSE) — MIT License.

---

## ⚙️ Getting Started

Follow these steps to run the project locally on your machine.

### Prerequisites
Make sure you have [Node.js](https://nodejs.org/) (v18.x or later) and `npm` installed.

### 1. Clone the repository
```bash
git clone https://github.com/sundaresanv2004/rumi.git
cd rumi
```

### 2. Install dependencies
```bash
npm install
```

### 3. Run the development server
```bash
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

### 4. Build for Production
To build a production-optimized version:
```bash
npm run build
npm run start
```

---

## 🎨 Design Systems & Typography
Rumi uses **Ubuntu Open Sans** typography combined with a polished, minimalist CSS color palette managed through Tailwind. Subtly animated using Framer Motion to provide high-quality feedback micro-animations.
