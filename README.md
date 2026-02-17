# CSS Frameworks CA

## Description

This project is a small social media prototype built as part of the CSS Frameworks assignment.
The goal was to create a multi-page application using Tailwind CSS installed with npm (no CDN).

The app simulates a simple user flow:

Authentication → Feed → Profile → Log out

All content is static and pre-made, as JavaScript functionality was not required for this assignment.

# Pages

## Authentication page — /index.html

Users can sign in using a form with HTML validation.

After signing in, the user is redirected to a pre-made profile page.

Features:

- Email validation

- assword minimum length (8 characters)

- Responsive centered auth card

## Feed page — /feed/index.html

A simulated social feed with pre-made content.

Features:

- Recent / Popular sorting tabs (UI only)

- Search bar with icon

- Create post input (UI only)

- Multiple pre-made posts

- Post thumbnails

- Like / Comment / Share UI

- Clickable usernames and avatars linking to a profile

- Avatar dropdown menu with logout

## Profile page — /profile/index.html

A pre-made user profile page.

Features:

- Profile image and username

- Bio section

- Follow button (UI only)

- Followers / Following / Posts stats

- List of user posts

- Logout option via avatar dropdown

The profile page is also accessible by clicking the Emma Johansson avatar or name in the feed.

## Technologies used

- HTML

- Tailwind CSS (installed via npm)

- Prettier

Available commands

- npm run dev
- npm run build

## AI usage

Tool used: ChatGPT
Date: 12. February 2026

Purpose: Generating placeholder content, Fake users, Example posts, Placeholder avatars.

Outcome: This helped visualize the UI, test layout consistency, and simulate a social media experience without implementing a backend or real user data.
