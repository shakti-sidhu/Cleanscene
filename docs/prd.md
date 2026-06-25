# CleanScene - Product Requirements Document (PRD)

## 1. Problem Statement

CleanScene is a gamified sustainability platform that connects NGOs, volunteers, and sponsoring brands to organize, participate in, and track environmental cleanup initiatives.

The platform aims to increase volunteer engagement through rewards, community interaction, and measurable impact tracking. By combining social networking, gamification, and environmental action, CleanScene transforms volunteering into an engaging and rewarding experience while helping organizations create a greater positive impact on communities and the environment.

---

# 2. User Roles

## Volunteer

### Capabilities

* Create account
* Login securely
* Join cleanup drives
* Track participation history
* Earn points and rewards
* Unlock badges and achievements
* Maintain participation streaks
* View leaderboard rankings
* Build impact profile
* Share achievements on social media

---

## NGO

### Capabilities

* Register organization
* Create cleanup drives
* Manage volunteers
* Verify volunteer attendance
* Upload event reports
* Upload cleanup photos
* Track event analytics
* View volunteer engagement metrics

---

## Brand

### Capabilities

* Create sponsor account
* Sponsor environmental drives
* Offer rewards and incentives
* Track CSR activities
* Monitor campaign impact
* Access sponsorship analytics

---

## Admin

### Capabilities

* Manage users
* Approve NGOs
* Approve events
* Moderate content
* Handle reports and complaints
* Manage rewards system
* Monitor platform analytics

---

# 3. Core Features (MVP)

## Authentication System

### Features

* User Registration
* User Login
* Forgot Password
* Reset Password
* JWT Authentication
* Role-Based Access Control
* Profile Creation

---

## Volunteer Dashboard

### Features

* Upcoming Drives
* Joined Events
* Impact Statistics
* Points & Rewards
* Badges Collection
* Achievement Tracker
* Activity Feed
* Impact Passport

---

## NGO Dashboard

### Features

* Create Cleanup Drive
* Edit Event Details
* Manage Volunteers
* Verify Attendance
* Upload Reports
* Upload Event Photos
* View Event Analytics

---

## Brand Dashboard

### Features

* Browse Sponsorship Opportunities
* Sponsor Events
* Reward Management
* CSR Analytics Dashboard
* Sponsorship History

---

## Gamification Engine

### Features

* XP Points System
* User Levels
* Achievement Badges
* Leaderboards
* Participation Streaks
* Weekly Challenges
* Monthly Missions
* Reward Redemption

---

## Impact Tracking System

### Metrics

* Total Waste Collected
* Total Trees Planted
* Total Volunteers
* Total Cleanup Drives
* Total Communities Impacted
* Total CSR Contributions

---

## Social Features

### Features

* Activity Feed
* Community Updates
* Event Sharing
* Volunteer Recognition
* Impact Stories

---

# 4. Pages & Routes

## Public Pages

### Landing Page

Route:
/
Purpose:
Platform introduction and CTA

### About Page

Route:
/about

### Impact Page

Route:
/impact

### Contact Page

Route:
/contact

---

## Authentication Pages

### Login

Route:
/login

### Signup

Route:
/signup

### Forgot Password

Route:
/forgot-password

---

## Volunteer Pages

### Dashboard

Route:
/volunteer/dashboard

### Profile

Route:
/volunteer/profile

### Events

Route:
/volunteer/events

### Leaderboard

Route:
/leaderboard

### Impact Passport

Route:
/passport

---

## NGO Pages

### Dashboard

Route:
/ngo/dashboard

### Create Event

Route:
/ngo/create-event

### Manage Event

Route:
/ngo/manage-event

---

## Brand Pages

### Dashboard

Route:
/brand/dashboard

### Sponsorships

Route:
/brand/sponsorships

---

## Admin Pages

### Admin Dashboard

Route:
/admin

### User Management

Route:
/admin/users

### NGO Approvals

Route:
/admin/ngos

### Event Management

Route:
/admin/events

---

# 5. Unique Features (USP)

## EcoDNA System

Every user receives an environmental personality based on their activities.

Examples:

* Ocean Guardian
* Green Warrior
* Earth Architect
* Planet Protector
* Sustainability Champion
* Climate Defender

Purpose:
Increase engagement and personalization.

---

## Impact Passport

A dynamic digital sustainability portfolio.

Displays:

* Events Attended
* Volunteer Hours
* Waste Collected
* Badges Earned
* Impact Score
* Participation Streak

Purpose:
Creates a verified environmental resume.

---

## CleanScene Heatmap

Interactive map displaying:

* Cleanup Locations
* Upcoming Events
* High-Impact Zones
* Volunteer Density

Purpose:
Visualize community impact.

---

## Mission System

Weekly and Monthly Missions.

Examples:

* Attend 2 Cleanups
* Bring 3 Friends
* Collect 10kg Waste
* Complete 5 Volunteer Hours

Purpose:
Improve user retention.

---

## Impact Score

Personal environmental score generated from:

* Volunteer Hours
* Event Participation
* Mission Completion
* Community Contributions

Purpose:
Provide measurable impact tracking.

---

# 6. Tech Stack

## Frontend

* Next.js
* TypeScript
* Tailwind CSS
* Framer Motion
* ShadCN UI

---

## Backend

* Node.js
* Express.js

---

## Database

* PostgreSQL

---

## Authentication

* JWT
* Bcrypt

---

## File Storage

* Cloudinary

---

## Maps

* Leaflet.js
* OpenStreetMap

---

## Charts & Analytics

* Recharts

---

## Deployment

Frontend:

* Vercel

Backend:

* Render

Database:

* Neon PostgreSQL

---

# 7. Design Philosophy

CleanScene should not look like a typical NGO website or government portal.

The experience should feel like a fusion of:

* Spotify
* Strava
* Duolingo
* Discord
* Notion

---

## Design Principles

### Visual Style

* Glassmorphism
* Futuristic Cards
* Dynamic Gradients
* Animated Backgrounds
* Modern Typography
* Dark Theme First

---

### User Experience

* Fast and responsive
* Mobile-first design
* Gamified interactions
* Interactive dashboards
* Smooth animations

---

### Brand Personality

* Youth-focused
* Mission-driven
* Energetic
* Community-centered
* Environmentally conscious

---

# 8. Success Metrics

## User Metrics

* Monthly Active Users
* Volunteer Retention Rate
* Event Participation Rate
* Average User Sessions

---

## NGO Metrics

* Drives Created
* Volunteers Managed
* Events Completed

---

## Brand Metrics

* Sponsorship Revenue
* CSR Engagement
* Reward Redemptions

---

## Environmental Metrics

* Waste Collected
* Trees Planted
* Volunteer Hours
* Communities Impacted

---

# Vision Statement

To become the world's most engaging platform for environmental action by transforming sustainability into a social, rewarding, and measurable experience.
