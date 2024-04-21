## Messenger Clone
A fully responsive real-time messenger clone made with Next.js 13 (app router), MongoDB, Tailwind CSS, Pusher, Next-Auth and Cloudinary.

## Table of Contents
- **[Tech Stack](#tech-stack)**
- **[Features](#features)**
- **[Setup](#setup)**
- **[Running](#running)**

## Tech Stack

- **[Next.js](https://nextjs.org/)**
- **[React](https://facebook.github.io/react/)**
- **[MongoDB](https://www.mongodb.com/atlas/database)**
- **[Tailwind CSS](https://tailwindcss.com/)**
- **[Pusher](https://pusher.com/)**
- **[Next-Auth](https://next-auth.js.org/)**
- **[Typescript](https://www.typescriptlang.org/)**

## Features

- Real-time chat update with Pusher
- Group chat
- Delete chat history
- Image hosting with Cloudinary
- Dynamic Theme support (Light and Dark mode)
- Support for both Desktop and Mobile screens

## Setup

1. **Clone the Repository:**
```
git clone https://github.com/AayushGupta69/Messenger-Clone
cd Messenger-Clone
```

2. **Create a ```.env``` file:**

Create a .env file based on the .env.example file provided. Replace the placeholder values with your actual Google Authentication, GitHub Authentication, Cloudinary, Pusher and MongoDB values.
```
DATABASE_URL=
NEXTAUTH_SECRET=type-anything-or-generate-a-guid-online-and-use-that
NEXTAUTH_URL=http://localhost:3020/

NEXT_PUBLIC_PUSHER_APP_KEY=
NEXT_PUBLIC_PUSHER_CLUSTER=
PUSHER_APP_ID=
PUSHER_SECRET=

NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=
NEXT_PUBLIC_CLOUDINARY_PRESET_NAME=

GITHUB_ID=
GITHUB_SECRET=

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
```

3. **Installing Dependencies:**

Install dependencies by running ``` yarn install ``` in the terminal. If you don't have yarn installed, install it from [Install Yarn](https://yarnpkg.com/getting-started/install).

4. **Creating Database Collections:**

Run ``` yarn prisma db push ``` in the terminal to create the database collections using Prisma.

## Running the app

- Run ```yarn dev``` to run the app locally with Hot Module Replacement (HMR) enabled. 

- The app will be running on ```http://localhost:3020/```.