# 🎓 Cloud Institution LMS Portal

A comprehensive Learning Management System (LMS) built with Next.js, featuring course management, student tracking, assessments, programming environments, and more.

## 🌟 Recent Updates - Homepage Redesign (Issue #28)

✨ **Complete homepage overhaul** with modern design, infinite carousels, and modular architecture
📄 **New pages added**: About and Contact pages
🏗️ **Modular components**: Split into reusable React components
📱 **Responsive design**: Optimized for all devices with dark mode support

👉 **[View Complete Homepage Improvements Documentation](./HOMEPAGE_IMPROVEMENTS.md)**

## 🚀 Features

### 📚 Course Management
- **Course Creation & Management**: Full CRUD operations for courses
- **Content Management**: Rich text editor for course materials
- **Video Integration**: Embedded video lessons
- **Progress Tracking**: Student progress monitoring

### 👥 User Management
- **Multi-Role System**: Admin, Teacher, Student roles
- **Authentication**: Secure login with Firebase Auth
- **Profile Management**: User profiles and settings

### 📊 Assessment System
- **Quiz Creation**: Dynamic quiz builder
- **Programming Challenges**: Code execution environment
- **Auto-Grading**: Automated assessment scoring
- **Results Analytics**: Detailed performance reports

### 💻 Programming Environment
- **Code Editor**: Monaco-based code editor
- **Multi-Language Support**: Python, JavaScript, Java, C++, and more
- **Judge0 Integration**: Secure code execution
- **Real-time Feedback**: Instant code compilation and testing

### 📈 Attendance & Analytics
- **QR Code Attendance**: Mobile-friendly attendance system
- **Analytics Dashboard**: Comprehensive reporting
- **Export Features**: Excel/CSV export capabilities
- **Real-time Tracking**: Live attendance monitoring

### 🎨 Modern UI/UX
- **Dark Mode Support**: System-wide dark/light theme
- **Responsive Design**: Mobile-first approach
- **Infinite Carousels**: Smooth animations and transitions
- **Interactive Components**: Engaging user interface

## 🛠️ Tech Stack

- **Frontend**: Next.js 14, React 18, TypeScript
- **Styling**: Tailwind CSS, Framer Motion
- **UI Components**: Radix UI, Lucide Icons
- **Backend**: Next.js API Routes
- **Database**: Firebase Firestore
- **Authentication**: Firebase Auth
- **Code Execution**: Judge0 API
- **File Processing**: ExcelJS, XLSX
- **Deployment**: Vercel

## 🏗️ Project Structure

```
lmsportal/
├── app/                    # Next.js App Router
# Cloud Institution — LMS (portfolio)

Live product: https://www.cloudinstitution.in/

Overview
- This is the Learning Management System (LMS) I built with a teammate during a 2‑month internship at Cloud Institution. The system is production-ready and used by teachers and students for course delivery, attendance management, assessments (including auto-graded programming challenges), and reporting.

My role & contributions
- Frontend lead (Next.js + TypeScript): majority of UI, layouts, responsive design, and theme system.
- Implemented the Monaco-based programming editor, integrated Judge0 for secure code execution, and built the auto-grading flow.
- Built the QR-based attendance flow (scanner, mobile view, and Excel export pipelines).
- Created core reusable components and layout system (`components/`), and coordinated integration with Firebase (`lib/firebase.ts`, `lib/firebase-admin-client.ts`).
- Improvements: homepage redesign (infinite carousels, modular sections) and performance optimizations.

Key highlights (what makes this project notable)
- Production usage: real teachers and students use the product for day-to-day classes and assessments.
- Programming assessment: live code execution with Judge0, multi-language support, and instant feedback.
- Attendance: mobile-first QR scanning and exportable reports (Excel/XLSX).
- Reusable architecture: component-driven UI, App Router structure, and clear separation of services in `lib/`.

Selected screenshots (placeholders)
- `docs/screenshots/home.png` — Homepage (hero & course showcase)
- `docs/screenshots/admin-dashboard.png` — Admin dashboard with analytics
- `docs/screenshots/student-dashboard.png` — Student dashboard and progress
- `docs/screenshots/programming-editor.png` — Monaco editor with Judge0 results
- `docs/screenshots/attendance-qr.png` — QR attendance flow (mobile)

Architecture & notable files
- Frontend: `app/` (Next.js App Router), `components/` (layouts & UI primitives)
- Services: `lib/` (Firebase clients, Judge0 wrapper, domain services)
- API: `api/` route handlers for secure server-side operations
- Hooks: `hooks/` (attendance polling, toasts, mobile helpers)

Technical stack (short)
- Next.js (App Router), React, TypeScript, Tailwind CSS
- Firebase (Auth, Firestore, Admin SDK)
- Judge0 for code execution, Monaco editor for in-browser editing
- Excel/XLSX for exports, Framer Motion, Radix UI

Metrics and impact (if available)
- Used by 100s of students and teachers (internal counts) — include any concrete numbers you have here (user counts, courses created, assessments graded) to strengthen the narrative.

Challenges & what I learned
- Securely integrating remote code execution (Judge0) without exposing secrets.
- Designing a performant, responsive editor experience with Monaco inside Next.js.
- Producing reliable attendance exports and ensuring offline/mobile scanning resilience.

How to present this project in an interview/portfolio
1. Start with the live URL and a 45–60s walkthrough video or screenshots.
2. Describe your responsibilities and show 2–3 concrete contributions (e.g., Monaco integration, QR attendance, export pipeline).
3. Discuss a technical challenge and your solution (security, scaling, data consistency).
4. Mention metrics and user feedback (adoption, time saved, or other impact).

Pointers for reviewers (where to look in the code)
- UI & layouts: `components/` and `app/` (layout files)
- Code execution: `lib/judge0.ts`, `lib/judge0-wrapper.ts`, `components/monaco-editor.tsx`
- Attendance: `lib/attendance-service.ts`, `lib/attendance-export.ts`, `components/student-qr-code.tsx`

Permissions & notes
- This project was built during an internship at Cloud Institution. Before publishing or reusing code publicly, confirm permissions with Cloud Institution.

If you want, I can now:
- Update each per-folder README with curated examples of files I worked on (I can mark the most important files and add short explanations).
- Generate a compact one-page portfolio blurb (suitable for LinkedIn/GitHub projects) and a small set of captions for each screenshot.

---