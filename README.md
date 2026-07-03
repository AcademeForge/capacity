# Capacity

> **The quiet signal that tells the people you love how you really are.**

Capacity is a private, feed-free relationship app that helps close friends, partners, and family understand each other's emotional availability with a single tap.

Instead of asking **"How are you?"**, users share a simple capacity state that communicates how much emotional or mental bandwidth they have at the moment.

The product intentionally removes feeds, likes, followers, streaks, and public social pressure. It is designed as a quiet utility rather than another social network.

---

# Prototype Overview

This repository contains a complete high-fidelity HTML prototype of Capacity, including every major user flow and screen required for an MVP.

The prototype is built using:

- HTML5
- CSS3
- Responsive Flexbox Layout
- No external frameworks
- No JavaScript (UI prototype only)

---

# Features

## Authentication

- Sign In
- Create Account
- Email Verification
- Forgot Password
- Password Reset Confirmation

---

## Onboarding

Three-step onboarding flow:

1. Create your first Circle
2. Invite people
3. Set your first Capacity state

---

## Home

Displays:

- Your current state
- Circle members
- Current status of each member
- Recent updates
- New message indicators

---

## Capacity States

Five predefined emotional bandwidth states:

| State | Meaning |
|--------|----------|
| 🟢 Good | Full capacity |
| 🟡 Okay | Functioning normally |
| 🟠 Stretched | Running low on bandwidth |
| 🔴 Need Space | Please don't initiate conversations |
| ⚪ Off the Grid | Not sharing availability |

---

## State Picker

Users can:

- Update their state
- Add an optional note
- Enable automatic state updates
- Sync with calendar (Premium)

---

## Circle Management

- View members
- Invite new members
- Share invite links
- Leave circle

---

## Private Chat

Each relationship includes a lightweight private conversation.

Features include:

- Status updates
- Messages
- Quick reply chips
- Simple messaging interface

---

## Settings

Includes:

- Profile
- Circle management
- Notification preferences
- Privacy
- Premium
- Support
- Logout

---

## Premium

Premium unlocks:

- Unlimited circles
- Custom states
- Custom colors
- 30-day trends
- Calendar sync
- Automatic status updates

---

# Prototype Screens

## Authentication

1. Sign In
2. Sign Up
3. Email Verification
4. Forgot Password
5. Password Reset Confirmation

---

## Onboarding

6. Create Circle
7. Invite Members
8. Select First State

---

## Core App

9. Home
10. State Picker
11. Circle Details
12. Chat

---

## Settings

13. Settings
14. Premium Upgrade

---

# Design System

## Colors

Primary

```
#3B6D11
```

Background

```
#F7F6F3
```

Surface

```
#FFFFFF
```

Text

```
#1A1916
```

---

## Status Colors

Good

```
#639922
```

Okay

```
#BA7517
```

Stretched

```
#D85A30
```

Need Space

```
#A32D2D
```

Off the Grid

```
#9B9892
```

---

## Typography

Font Family

```
Inter
```

Weights

- 300
- 400
- 500
- 600

---

# Product Philosophy

Capacity is intentionally designed around **less communication, not more**.

It avoids:

- Infinite feeds
- Public profiles
- Likes
- Comments
- Followers
- Engagement algorithms
- Streaks
- Vanity metrics

Instead, it focuses on one question:

> **How much capacity do I have right now?**

---

# User Flow

```
Authentication
        │
        ▼
 Create Account
        │
        ▼
 Email Verification
        │
        ▼
Create First Circle
        │
        ▼
Invite Someone
        │
        ▼
Set Capacity State
        │
        ▼
Home Dashboard
        │
        ├────────► Chat
        │
        ├────────► Circle
        │
        └────────► Settings
                     │
                     ▼
                  Premium
```

---

# Premium Strategy

Free plan is intentionally complete for one relationship.

Premium expands the product rather than unlocking basic functionality.

### Free

- One Circle
- Five states
- Chat
- Notifications

### Premium

- Unlimited circles
- Custom states
- Calendar integration
- Trends
- Automation
- Advanced personalization

---

# Repository Structure

```
capacity/
│
├── index.html
├── README.md
└── assets/
```

---

# Future Development

Possible next features include:

- Dark mode
- Push notifications
- iOS & Android applications
- WebSockets for live updates
- Read receipts (optional)
- Shared journals
- Voice notes
- Widgets
- Apple Health integration
- Google Calendar integration
- Emergency contacts
- AI-powered wellness summaries
- Accessibility improvements

---

# Vision

Capacity is not another messaging app.

It is not another social network.

It is a private emotional availability layer for the people who matter most.

One tap replaces dozens of unnecessary conversations and helps people understand one another before words are needed.

---

# License

This project is provided as a UI/UX prototype and design specification.

All branding, concepts, and visual assets remain the property of their respective creator.

---

## Built With

- HTML5
- CSS3
- Responsive Layout
- Inter Typeface

---

**Capacity**  
*Know someone's capacity before asking for it.*
