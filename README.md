# Capacity

> **The quiet signal that tells the people you love how you really are.**

Capacity is a private, feed-free relationship app that helps partners, close friends, and families instantly understand each other's emotional availability.

Instead of asking **"How are you?"**, users simply update their capacity with one tap. Their closest circle immediately knows whether they're available, overwhelmed, or simply need space.

Designed as a quiet utility—not another social network—Capacity removes the pressure of constant communication while improving understanding between people who matter most.

---

# Prototype Overview

This repository contains a complete high-fidelity prototype of **Capacity**, showcasing the complete user journey from authentication to premium features.

The prototype demonstrates every major screen and interaction required for a production-ready MVP.

### Built With

- HTML5
- CSS3
- Responsive Layout
- Flexbox & CSS Grid
- SVG Icons
- Google Fonts (Inter)
- Mobile-first Design

---

# Core Features

## Authentication

Secure authentication flow including:

- Sign In
- Create Account
- Email Verification (OTP)
- Forgot Password
- Password Reset
- New Password Creation

---

## Onboarding

A simple three-step onboarding experience:

1. Create your first Circle
2. Invite members
3. Set your first Capacity state

The onboarding intentionally requires inviting another person because Capacity only becomes valuable once it is shared.

---

## Home Dashboard

The Home screen provides an overview of your private circle.

Features include:

- Your current state
- Circle overview
- Member availability
- Recent updates
- New message indicators
- Quick access to chats

---

## Capacity States

Capacity uses five emotional availability states.

| State | Description |
|--------|-------------|
| 🟢 Good | Full emotional capacity |
| 🟡 Okay | Available, but keep things light |
| 🟠 Stretched | Busy or mentally overloaded |
| 🔴 Need Space | Prefer not to be contacted |
| ⚪ Off the Grid | Temporarily unavailable |

---

## State Updates

Users can update their current state in one tap.

Optional features include:

- Short status note
- Automatic state updates
- Calendar synchronization
- Smart recommendations

---

## Circle Management

Each user can manage one or more private circles.

Available actions:

- Create circles
- Invite members
- Username search
- Share invite links
- Remove members
- Leave circles

---

## Private Chat

Capacity includes lightweight one-to-one conversations.

Features:

- Live status indicator
- Status-aware messaging
- Quick replies
- Private conversations
- Message history

---

## Settings

Manage your account with:

- Profile
- Username
- Circle Management
- Notification Preferences
- Privacy Settings
- Premium Subscription
- Help & Support

---

## Premium

Premium expands Capacity with:

- Unlimited Circles
- Custom Capacity States
- Custom Colors
- 30-Day History
- Calendar Integration
- Automatic Status Updates
- Advanced Personalization

---

# Complete Prototype

### Authentication

1. Welcome Back
2. Create Account
3. Verify Email
4. Forgot Password
5. Enter Reset Code
6. Create New Password

---

### Onboarding

7. Create Circle
8. Invite Members
9. Select First Capacity State

---

### Main Application

10. Home Dashboard
11. Update Capacity
12. Circle Details
13. Private Chat

---

### Account

14. Settings
15. Premium Upgrade

---

# Design System

## Primary Colors

Primary

```css
#3B6D11
```

Background

```css
#F6F5F2
```

Surface

```css
#FFFFFF
```

Text

```css
#1A1916
```

---

## Capacity Colors

Good

```css
#639922
```

Okay

```css
#BA7517
```

Stretched

```css
#D75A2E
```

Need Space

```css
#A12C2C
```

Off the Grid

```css
#9A9793
```

---

## Typography

Font

```text
Inter
```

Weights

- 300
- 400
- 500
- 600
- 700

---

# Product Philosophy

Capacity exists to reduce emotional friction.

Rather than encouraging more conversation, it encourages better timing.

The product intentionally avoids:

- Infinite feeds
- Likes
- Followers
- Public profiles
- Comments
- Engagement algorithms
- Notifications for attention
- Social pressure

Instead, it focuses on one simple question:

> **"How much emotional capacity do I have right now?"**

---

# User Journey

```text
Sign In / Create Account
            │
            ▼
     Email Verification
            │
            ▼
      Create Circle
            │
            ▼
      Invite Members
            │
            ▼
     Select First State
            │
            ▼
      Home Dashboard
            │
    ┌───────┼────────┐
    ▼       ▼        ▼
  Chat   Circles   Settings
                    │
                    ▼
                 Premium
```

---

# Premium Strategy

The free version is intentionally complete for one relationship.

Premium expands Capacity without restricting core functionality.

### Free

- One Circle
- Five Capacity States
- Private Chat
- Notifications

### Premium

- Unlimited Circles
- Custom States
- Calendar Sync
- Mood History
- Automation
- Advanced Personalization

---

# Repository Structure

```text
capacity/
│
├── index.html
├── README.md
├── assets/
│   ├── icons/
│   ├── images/
│   └── fonts/
└── screenshots/
```

---

# Future Roadmap

Potential future enhancements:

- Dark Mode
- Push Notifications
- Native Android App
- Native iOS App
- Progressive Web App
- Apple Health Integration
- Google Calendar Sync
- Widgets
- AI Insights
- Mood Analytics
- Accessibility Improvements

---

# Vision

Capacity is not another messaging app.

It is not another social platform.

It is a private emotional availability layer that helps people understand one another before conversations even begin.

One tap communicates what words often cannot.

---

# License

This project is provided as a UI/UX prototype and design reference.

All branding, concepts, and visual assets remain the property of their respective creator.

---

## Built With

- HTML5
- CSS3
- Responsive Design
- Flexbox
- CSS Grid
- Google Fonts (Inter)

---

**Capacity**

*Know someone's capacity before asking for it.*
