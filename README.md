<div align="center">
  <br />
    <a href="https://youtu.be/lEflo_sc82g" target="_blank">
      <img src="/public/assets/icons/logo-full.svg" alt="Project Banner">
    </a>
  <br />

  <div>
    <img src="https://img.shields.io/badge/-Next_JS-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=000000" alt="nextdotjs" />
    <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="typescript" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
    <img src="https://img.shields.io/badge/-Appwrite-black?style=for-the-badge&logoColor=white&logo=appwrite&color=FD366E" alt="appwrite" />
  </div>

  <h3 align="center">CarePulse - Healthcare Patient Management System</h3>

   <div align="center">
     Built with the modern Next.js ecosystem, helping streamline patient registration, medical records scheduling, and secure access for healthcare providers.
    </div>
</div>

---

## 📋 <a name="table">Table of Contents</a>

1. 🚀 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🕸️ [Snippets](#snippets)

---

## 🚀 <a name="introduction">Introduction</a>

**CarePulse** is a healthcare patient management system designed to streamline patient registration, appointment scheduling, and medical records management. Built with cutting-edge tools to ensure best-in-class user experience, data security, and efficiency for healthcare providers.

## ⚙️ <a name="tech-stack">Tech Stack</a>

- **Framework:** [Next.js](https://nextjs.org/) (React 18)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/) & [shadcn/ui](https://ui.shadcn.com/)
- **Forms & Validation:** [React Hook Form](https://react-hook-form.com/) + [Zod](https://zod.dev/)
- **Backend-as-a-Service:** [Appwrite](https://appwrite.io/) (Database, Auth, Storage)
- **Monitoring & Quality:** [Sentry](https://sentry.io/)
- **Language:** [TypeScript](https://www.typescriptlang.org/)

## 🔋 <a name="features">Features</a>

👉 **Patient Registration System**: Secure and comprehensive onboarding flow for new patients, including capturing medical history and contact details.

👉 **Appointment Scheduling**: Interactive forms to easily schedule and modify doctor appointments.

👉 **Admin Dashboard Flow**: An authorized dashboard for medical staff to view, manage, and process patient appointments efficiently.

👉 **Secure Passkey Authentication**: Streamlined verification utilizing admin passkeys for robust security.

👉 **Responsive & Accessible Design**: Crafted using Tailwind CSS and Radix UI primitives to ensure flawless viewing across all devices.

👉 **File Uploads**: Easily upload health documents or identification via a custom drag-and-drop area.

👉 **Dark Mode Theme**: Modern deep dark theme out of the box using `next-themes` and a custom `bg-dark-300` palette.

👉 **Real-time Error Tracking**: Integrated with Sentry to immediately surface unhandled application exceptions.

## 🤸 <a name="quick-start">Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en) (v18+ recommended)
- [npm](https://www.npmjs.com/)

**Cloning the Repository**

```bash
git clone https://github.com/Ali-Ch-01/careplus.git
cd careplus
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env.local` in the root of your project and add the necessary environment variables:

```env
# APPWRITE
NEXT_PUBLIC_APPWRITE_ENDPOINT="https://cloud.appwrite.io/v1"
NEXT_PUBLIC_APPWRITE_PROJECT_ID="your_project_id"
APPWRITE_API_KEY="your_api_key"

# Additional Keys required for DB, Sentry, etc.
# Refer to the existing .env.local file pattern if needed.
```

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

## 🕸️ <a name="snippets">Snippets</a>

You can review the source code for key implementations:

- `app/page.tsx`: The main landing and Patient onboarding form.
- `components/forms/PatientForm.tsx`: Built with React Hook Form and Zod schemas.
- `lib/appwrite.ts`: Client/Server logic for interacting with Appwrite backend.

<br />
<p align="center">Made by Ali Mohsin (@Ali-Ch-01)</p>
