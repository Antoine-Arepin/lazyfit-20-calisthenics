# Lazy Calisthenics App - AutoCoder Project Documentation

## Project Overview

**App Name:** Lazy Calisthenics  
**Platform:** AutoCoder  
**Live URL:** https://lazycalisthenics.autocoder.cc  
**Backend Admin:** https://lazycalisthenics.autocoder.cc/BackendDashboardPage  
**Project ID:** PROJ_c920fff5  

## Description

A comprehensive calisthenics fitness application designed to help users build healthy habits through bodyweight exercises. Features 1500+ exercises, daily motivation, streak tracking, and an admin dashboard for content management.

---

## Frontend Pages & Components

### 1. Home Page
**URL:** `/`

**Components:**
- HeroSection
- MotivationalSection  
- StreakSummarySection
- FeaturedExercisesSection
- CTASection

**Features:**
- Badge: "1500+ Exercises"
- Headline: "Start Your Calisthenics Journey Today"
- Taglines: "No equipment needed. Just you and motivation." / "Build strength, stay consistent."
- CTAs: "Get Started Free", "Browse Exercises"
- Stats: 1500+ Exercises, No Equipment, Daily Motivation
- Today's Focus card with exercise progress (e.g., Push-Up Variations 4/12)
- Daily Motivation quotes section
- Progress at a Glance (Day Streak, Total Workouts, Available Exercises)
- Featured Exercises grid

### 2. Exercise Library Page
**URL:** `/exerciselibrarypage`

**Features:**
- Search bar: "Quick search exercises..."
- Filters sidebar:
  - Category: Chest, Back, Legs, Core, Shoulders
  - Difficulty: Beginner, Intermediate, Advanced
  - Equipment: No equipment, Pull-up bar, Rings, Parallettes
- Sort: Name (A-Z)
- Exercise cards with image, name, category, difficulty

### 3. Exercise Details Page
**URL:** `/exercisedetailspage/:id`

**Features:**
- Hero image with exercise photo
- Back navigation
- Bookmark/save button
- Title with tags (Difficulty, Body Part, Equipment type)
- Tabbed content: Instructions, Tips, Common Mistakes
- "How to Perform" section with numbered steps
- Exercise Stats: Calories, Sets, Reps
- Target Muscles: Primary, Secondary
- Equipment info
- "Start Exercise" CTA
- Related exercises section

**Sample Exercise Data:**
- Classic Push-ups: Chest, Beginner, Bodyweight, 50-80 cal, 2-3 sets, 8-12 reps
- Pull-ups: Back, Advanced
- Bodyweight Squats: Legs, Beginner
- Mountain Climbers: Core, Intermediate
- Handstand Push-ups: Shoulders, Advanced

### 4. Streak Tracker Page
**URL:** `/streaktrackerpage`
- Requires authentication

### 5. Motivational Wall Page
**URL:** `/motivationalwallpage`
- Requires authentication
- Daily quotes and inspiration

### 6. Ads Info Page
**URL:** `/adsinfopage`

**Features:**
- "Supporting This App" header
- "Why Ads?" section with 3 cards:
  - Free Access
  - Support Development
  - Ad-Free Option
- Pricing comparison table:
  - FREE: $0 forever - 1500+ exercises, daily motivation, basic streak tracking, ads between exercises, limited filters
  - PREMIUM: $4.99/month - All free features + ad-free, advanced streak tracking with rewards, advanced filters, personalized workout plans, priority support
- CTA: "Ready to Go Ad-Free?" with upgrade buttons
- Trust badges: Secure Payment, Cancel Anytime, Money Back Guarantee

### 7. Login Page
**URL:** `/frontendloginpage`

**Features:**
- App logo
- "Welcome Back" header
- "Log in to track your progress" subheader
- Email input
- Password input with visibility toggle
- "Remember me" checkbox
- "Forgot password?" link
- "Log In" button
- Social login options (Google, Apple, Facebook)
- "Don't have an account? Register" link

### 8. Register Page
**URL:** `/frontendregisterpage`

---

## Backend Admin System

### Admin Login
**URL:** `/backendloginpage`
- Email: admin@example.com (placeholder)
- Password input
- "Remember me" checkbox
- "Sign In" button

### Dashboard
**URL:** `/BackendDashboardPage`

**Components:**
- PageHeader
- KPICards (key metrics)
- Analytics
- ExerciseStats
- AdPerformance
- QuickActions

### CRUD Operations

1. **Exercise CRUD** - Manage 1500+ exercises
2. **Motivational Message CRUD** - Manage daily quotes
3. **User CRUD** - User management
4. **Ad Management** - Advertisement management

---

## Tech Stack (Inferred from AutoCoder)

- **Frontend:** React-based (likely React + Tailwind CSS)
- **Backend:** Node.js/API-based
- **Database:** Managed by AutoCoder
- **Hosting:** AutoCoder subdomain (*.autocoder.cc)
- **Design:** Green/white color scheme, modern card-based UI

---

## Color Scheme

- **Primary Green:** #16a34a (buttons, accents)
- **Light Green:** #dcfce7 (badges, backgrounds)
- **White:** #ffffff (backgrounds)
- **Dark:** #1a1a1a (text)
- **Gray:** Various shades for borders/secondary text

---

## Key Features Summary

1. 1500+ bodyweight exercises
2. Exercise filtering by category, difficulty, equipment
3. Detailed exercise instructions with images
4. Daily motivational quotes
5. Streak tracking system
6. User authentication (login/register)
7. Freemium model with premium upgrade
8. Admin dashboard for content management
9. Responsive web design
10. Social login options

---

## Navigation Structure

```
Header Navigation:
- Lazy Calisthenics (logo/home)
- Home
- Exercise Library
- Streak Tracker (auth required)
- Motivational Wall (auth required)
- Ads Info
- Login

Footer:
- Quick Links
- Privacy Policy
- Terms of Service
- Copyright 2025
```

---

## To Recreate This App

1. Set up React project with routing
2. Implement components following the structure above
3. Create exercise database (JSON/API)
4. Implement authentication system
5. Build admin dashboard
6. Add streak tracking logic
7. Implement premium features
8. Deploy to hosting platform

---

## Original AutoCoder Project

- **AutoCoder Project URL:** https://www.autocoder.cc/platform/generate/3374383093?PROJECTID=PROJ_c920fff5
- **Deployed URL:** https://lazycalisthenics.autocoder.cc
- **Created:** November 27, 2025

---

*This documentation was extracted from the AutoCoder platform to facilitate recreation of the app in a custom codebase.*
