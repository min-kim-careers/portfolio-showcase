> [!NOTE]  
> ## The previous website is no longer operational because of unnecessary hosting expenses. It has been replaced with an updated version.

# Portfolio Website Showcase

This repository contains the code for my personal portfolio website, showcasing my projects, skills, and contact information. The project is divided into two main parts: the backend and the frontend.

## Table of Contents

- [Backend](#backend)
  - [Technologies Used](#technologies-used)
  - [Project Structure](#project-structure)
- [Frontend](#frontend)
  - [Technologies Used](#technologies-used-1)
  - [Project Structure](#project-structure-1)
- [Deployment](#deployment)

## Backend

The backend is built using Python and FastAPI, and it handles the server-side logic and API routes, with MongoDB as the database.

### Technologies Used

- **Python**: Main programming language.
- **FastAPI**: Web framework for building APIs.
- **MongoDB**: Database hosted on Atlas.

### Project Structure

```
portfolio
├── credentials
│ ├── google_credentials_web_app.json
│ └── google_token.json
├── main.py
├── requirements.txt
├── res
│ └── resume.json
└── routes
├── pycache
├── about.py
├── chat.py
├── contact.py
├── project.py
└── resume.py
```


## Frontend

The frontend is built using React and TypeScript, with Vite as the build tool. It provides an interactive and responsive user interface for the portfolio website.

Technologies Used

- **React**: JavaScript library for building user interfaces.
- **TypeScript**: Typed superset of JavaScript.
- **Vite**: Frontend build tool.

### Project Structure

```
portfolio-app
├── README.md
├── index.html
├── package.json
├── public
│   └── _redirects
├── src
│   ├── App.tsx
│   ├── assets
│   │   ├── FastAPI.svg
│   │   ├── MongoDB.svg
│   │   |
│   │   ├── TypeScript.svg
│   │   ├── Vite.svg
│   │   └── profile_photo.png
│   ├── components
│   │   ├── ChatMessage.tsx
│   │   ├── ChatWindow.tsx
│   │   ├── DescriptionPopup.tsx
│   │   ├── FadeAlert.tsx
│   │   ├── LoadingBackdrop.tsx
│   │   ├── NavBar.tsx
│   │   ├── ReadmeDialog.tsx
│   │   ├── SpinningButtonIcon.tsx
│   │   ├── TypingText.css
│   │   ├── TypingText.tsx
│   │   └── WiggleAnimation.css
│   ├── config.ts
│   ├── index.css
│   ├── main.tsx
│   ├── pages
│   │   ├── AboutPage.tsx
│   │   ├── ContactPage.tsx
│   │   ├── HomePage.tsx
│   │   ├── ProjectPage.tsx
│   │   └── ResumePage.tsx
│   └── vite-env.d.ts
├── tsconfig.json
├── tsconfig.node.json
└── vite.config.ts
```
## Deployment

- **Frontend**: Deployed on Netlify.
- **Backend**: Deployed on AWS EC2.
- **Database**: Hosted on MongoDB Atlas.
