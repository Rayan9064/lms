# 🎓 Cloud Institution LMS Portal
[![Live Site](https://img.shields.io/badge/live-cloudinstitution.in-007ACC)](https://www.cloudinstitution.in/) [![Tech: Next.js](https://img.shields.io/badge/Next.js-14-black)](https://nextjs.org/) [![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue)](https://www.typescriptlang.org/) [![License](https://img.shields.io/badge/license-Check%20with%20Cloud%20Institution-lightgrey)](#)

🚀 Live product: https://www.cloudinstitution.in/

A comprehensive Learning Management System (LMS) built with Next.js, featuring course management, student tracking, assessments, programming environments, and more.

<img width="1365" height="628" alt="image" src="https://github.com/user-attachments/assets/f620ba46-c812-4cfc-bd52-a466aceaa0f1" />

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

Hero highlights
- Production-ready: real users (teachers & students)
- Programming assessment: in-browser coding + Judge0 auto-grading
- Attendance: mobile-first QR scanning + exportable Excel reports

My role & contributions
- Frontend lead (Next.js + TypeScript): UI, layouts, theme system, and performance tuning.
- Monaco editor integration (`components/monaco-editor.tsx`, `CodeEditor.tsx`) and Judge0 wiring (`lib/judge0.ts`, `lib/judge0-wrapper.ts`).
- QR attendance flow and export pipeline (`components/student-qr-code.tsx`, `lib/attendance-export.ts`, `lib/attendance-excel-export.ts`).
- Reusable components and layout system (`components/main-layout.tsx`, `components/admin-layout.tsx`).

---

<b>Screenshots</b>

| Login Page |
|:--------|
| <div align="center">Single login page for student, teacher and admin</div> |
| <img width="1365" height="629" alt="image" src="https://github.com/user-attachments/assets/0e052e93-dbe3-4c34-bb10-f0275988f7db" /> |


| Student Management Tab Preview |
|:--------|
| <div align="center">Student Management Page</div> |
| <img width="1365" height="624" alt="image" src="https://github.com/user-attachments/assets/de8f6b81-3663-4fde-a03a-fa1f4bc0c05f" /> |
| <div align="center">Student Filter</div> |
| <img width="1364" height="630" alt="image" src="https://github.com/user-attachments/assets/3b0ca4f4-5028-4b15-b939-05d2ab6347a6" /> |
| <div align="center">Bulk Delete, Status Change and Email Transfer option <br> (The organization has disabled email feature from their side)</div> |
| <img width="1365" height="628" alt="image" src="https://github.com/user-attachments/assets/790f10ab-ebfb-4146-a9ad-e4038ca596a4" /> |
| <div align="center">Individual Student details within student list</div> |
<img width="1365" height="626" alt="image" src="https://github.com/user-attachments/assets/b3c02722-4433-43ef-8753-6610e0a56b2b" /> |

| Student Preview |
|:--------|
| <div align="center">Student Dashboard</div> |
| <img width="1365" height="632" alt="image" src="https://github.com/user-attachments/assets/c1b92a52-94c5-4aa1-b0f7-00e1a781f199" /> |
| <div align="center">Student Course Page</div> |
| <img width="1365" height="629" alt="image" src="https://github.com/user-attachments/assets/a44debd9-84bc-435d-a0c3-a7da66ca1456" /> |
| <div align="center">Student Attendance Page</div> |
| <img width="1365" height="633" alt="image" src="https://github.com/user-attachments/assets/58041e7f-e50a-4505-9d64-a01010450cb1" /> |
| <div align="center">Student Profile Page</div> |
| <img width="1365" height="633" alt="image" src="https://github.com/user-attachments/assets/bda5916f-b042-45f7-9f49-442e4b39deb1" /> |

and many more!

--- 

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
