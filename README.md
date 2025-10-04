# 🎓 Cloud Institution LMS Portal

A comprehensive Learning Management System (LMS) built with Next.js, featuring course management, student tracking, assessments, programming environments, and more.

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
```


# Cloud Institution — LMS (portfolio)

[![Live Site](https://img.shields.io/badge/live-cloudinstitution.in-007ACC)](https://www.cloudinstitution.in/) [![Tech: Next.js](https://img.shields.io/badge/Next.js-14-black)](https://nextjs.org/) [![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue)](https://www.typescriptlang.org/) [![License](https://img.shields.io/badge/license-Check%20with%20Cloud%20Institution-lightgrey)](#)

🚀 Live product: https://www.cloudinstitution.in/

One-line summary
- Frontend lead on a production LMS used by teachers and students — Monaco-based programming assessments, Judge0 auto-grading, and QR attendance with Excel exports.

Hero highlights
- Production-ready: real users (teachers & students)
- Programming assessment: in-browser coding + Judge0 auto-grading
- Attendance: mobile-first QR scanning + exportable Excel reports

My role & contributions
- Frontend lead (Next.js + TypeScript): UI, layouts, theme system, and performance tuning.
- Monaco editor integration (`components/monaco-editor.tsx`, `CodeEditor.tsx`) and Judge0 wiring (`lib/judge0.ts`, `lib/judge0-wrapper.ts`).
- QR attendance flow and export pipeline (`components/student-qr-code.tsx`, `lib/attendance-export.ts`, `lib/attendance-excel-export.ts`).
- Reusable components and layout system (`components/main-layout.tsx`, `components/admin-layout.tsx`).

Screenshots (place files under `docs/screenshots/`)

| Preview | Filename |
|--------:|:--------|
| ![home](docs/screenshots/home.png) | `docs/screenshots/home.png` — Homepage (hero & course showcase) |
| ![admin](docs/screenshots/admin-dashboard.png) | `docs/screenshots/admin-dashboard.png` — Admin dashboard with analytics |
| ![student](docs/screenshots/student-dashboard.png) | `docs/screenshots/student-dashboard.png` — Student dashboard and progress |
| ![editor](docs/screenshots/programming-editor.png) | `docs/screenshots/programming-editor.png` — Monaco editor with Judge0 results |
| ![qr](docs/screenshots/attendance-qr.png) | `docs/screenshots/attendance-qr.png` — QR attendance flow (mobile) |

Key features
- 📚 Course management: content CRUD with progress tracking
- 👥 Multi-role system: Admin, Teacher, Student
- 🧪 Programming assessments: Monaco editor + Judge0 + auto-grading
- 📊 Analytics & exports: dashboards and Excel/XLSX export pipelines
- 📱 QR attendance: mobile-friendly scanning and exportable reports

Architecture & where to look
- Frontend: `app/`, `components/` (layouts & UI primitives)
- Services: `lib/` (`firebase.ts`, `firebase-admin-client.ts`, `judge0.ts`)
- API: `api/` route handlers (Judge0 proxy, export endpoints)
- Hooks: `hooks/` (`use-attendance.ts`, `use-toast.ts`)

Notes & permissions
- Built during a 2‑month internship at Cloud Institution. Confirm permissions before publishing or reusing code publicly.

----
