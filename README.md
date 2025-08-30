# MysteryMsg Web Application

A lightweight anonymous messaging application built using **Next.js**—crafted as a hands-on project to explore Next.js’s capabilities on the backend.

---

## Table of Contents

- [Overview](#overview)  
- [Features](#features)  
- [Tech Stack](#tech-stack)   
- [Project Structure](#project-structure)
- [Learning Goals](#learning-goals)

---

## Overview

This project was developed as a learning exercise in utilizing **Next.js** not just for frontend rendering, but for building out **backend logic and APIs**. You’ll find components, utilities, and schema definitions that showcase how to structure a robust, full-stack Next.js application.

---

## Features

-  **Next.js backend**: API routes and schema validation powered by TypeScript and Zod  
-  Form handling and validation using `react-hook-form`  
-  Schema definitions ensuring strong typing and validation  
-  Ready for deployment via platforms like **Vercel**

---

## Tech Stack

- **Next.js 15** (backend API and frontend rendering)  
- **TypeScript** for type safety and schema definitions  
- **Zod** for runtime schema validation  
- **React Hook Form** for client-side form state and validation  
- **Tailwind CSS** (with animation utilities) for styling and UI  
- Optional libraries: `next-auth`, `mongoose`, `openai`, `resend`, etc., depending on additional features  

---

## Project Structure

```
mysterymsg/
├── src/
│   ├── schemas/
│   │   └── acceptMessageSchema.ts  ← Zod schema for message validation
│   ├── pages/ or app/
│   │   ├── api/
│   │   │   └── …                 ← Backend API routes
│   │   └── …                     ← Frontend components/pages
├── package.json
└── README.md
```

---

## Learning Goals

I embarked on this project to explore how Next.js can be used beyond frontend rendering—to build backend APIs, integrate TypeScript, and ensure data integrity via schemas. It’s a great learning exercise in full-stack TypeScript development.

Huge THANKS to CHAI aur CODE for this amazing tutorial (https://youtube.com/playlist?list=PLu71SKxNbfoBAaWGtn9GA2PTw0HO0tXzq&si=9IKoH87rFwf6uID1).