# Research Repository System

A fully functional React + Supabase Research Repository System with:

- User Login
- User Sign Up
- Research Upload
- Research Search
- PDF Storage using Supabase Storage
- Supabase Ready Configuration

---

## REQUIREMENTS

Install:

- Node.js
- npm

---

## STEP 1 — CREATE SUPABASE PROJECT

Go to Supabase:

https://supabase.com

Create a new project.

---

## STEP 2 — CREATE DATABASE TABLE

Open SQL Editor in Supabase.

Copy and run the content from:

supabase-schema.sql

---

## STEP 3 — CREATE STORAGE BUCKET

Go to:

Storage → Create Bucket

Bucket Name:

research-files

Make it PUBLIC.

---

## STEP 4 — GET SUPABASE KEYS

Go to:

Project Settings → API

Copy:

- Project URL
- anon public key

---

## STEP 5 — CONFIGURE ENV FILE

Rename:

.env.example

to:

.env

Then add:

VITE_SUPABASE_URL=YOUR_URL
VITE_SUPABASE_ANON_KEY=YOUR_KEY

---

## STEP 6 — INSTALL DEPENDENCIES

Open terminal inside the project folder.

Run:

npm install

---

## STEP 7 — START THE PROJECT

Run:

npm run dev

Open the URL shown in terminal.

---

## FEATURES

✅ Login & Sign Up

✅ Upload Research PDF

✅ Search Research

✅ View Uploaded Research

✅ Supabase Authentication

✅ Supabase Storage