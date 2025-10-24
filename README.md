# FitFrame

A comprehensive fitness tracking application built with Next.js, featuring AI-powered pose detection, workout tracking, and personalized diet recommendations.

## Features

- **AI-Powered Exercise Detection**: Real-time pose detection for accurate exercise form analysis
- **Workout Tracking**: Track your workouts with detailed statistics and progress monitoring
- **Diet Management**: Personalized diet recommendations and meal planning
- **User Authentication**: Secure user registration and login system
- **Responsive Design**: Modern UI built with Tailwind CSS and Radix UI components

## Tech Stack

- **Frontend**: Next.js 15, React 19, TypeScript
- **Styling**: Tailwind CSS, Radix UI
- **Database**: Prisma ORM
- **Authentication**: NextAuth.js
- **AI/ML**: TensorFlow.js, MediaPipe Pose
- **Deployment**: Vercel

## Getting Started

### Prerequisites

- Node.js 18+ 
- npm or yarn
- Database (PostgreSQL recommended)

### Installation

1. Clone the repository:
```bash
git clone <your-repo-url>
cd fitframe
```

2. Install dependencies:
```bash
npm install
```

3. Set up environment variables:
```bash
cp .env.example .env.local
```

4. Set up the database:
```bash
npx prisma generate
npx prisma db push
```

5. Run the development server:
```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Project Structure

```
├── app/                    # Next.js app directory
│   ├── api/               # API routes
│   ├── components/        # React components
│   ├── dashboard/         # Dashboard pages
│   └── lib/              # Utility functions
├── components/            # Shared UI components
├── prisma/               # Database schema and migrations
└── public/               # Static assets
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.