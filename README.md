# Moodify - Mood Tracking App

Moodify is a full-stack mood tracking application built with Next.js 14, Firebase, and TailwindCSS. This project allows users to log their daily emotions, visualize mood trends over time, and gain insights into their emotional well-being.

## Live Demo

Check out the live demo of Moodify: [https://moodify-aj.netlify.app](https://moodify-aj.netlify.app)

## Features

- User Authentication with Firebase
- Daily mood logging
- Data visualization for mood trends
- Real-time updates using Firebase Firestore
- Responsive design with TailwindCSS

## Tech Stack

- **Frontend**: Next.js 14, React
- **Backend**: Firebase (Authentication and Firestore)
- **Styling**: TailwindCSS
- **Deployment**: Netlify

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ajay-cs-tech/moodify.git
   cd moodify
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   Create a `.env.local` file in the root directory and add your Firebase configuration:
   ```
   NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key
   NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_auth_domain
   NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
   NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_storage_bucket
   NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
   NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id
   ```

## Running the Application

To run the app in development mode:

```bash
npm run dev
```

The app will be available at `http://localhost:3000`.

## Deployment

This project is deployed on Netlify. To deploy your own version:

1. Push your code to a GitHub repository.
2. Sign up for a Netlify account and connect your GitHub repository.
3. Configure the build settings:
   - Build command: `npm run build`
   - Publish directory: `.next`
4. Add your environment variables in the Netlify dashboard.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
