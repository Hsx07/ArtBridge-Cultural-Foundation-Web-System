# ArtBridge Cultural Foundation Web System

A comprehensive web-based information system for managing cultural foundation operations, supporting event management, artist collaboration, grant administration, and community engagement.

## Project Overview
ArtBridge Cultural Foundation is a non-profit organization dedicated to promoting cultural exchange and supporting emerging artists. This web system provides a platform for managing the foundation's operations, from event planning to grant administration.

### Key Features
- Event Management: Create, schedule, and manage cultural events, venues, and attendance.
- Artist Portal: Artist profiles, portfolio management, and direct communication with staff.
- Grant Administration: Create and manage funding opportunities, application processing, and decision tracking.
- Analytics & Reporting: Real-time dashboards, performance metrics, and exportable reports.
- Authentication: Secure login and registration with NextAuth.js.
- Real-time Updates: Live notifications and updates using Socket.IO.

## Technology Stack
- Frontend: Next.js 14, React 18, TypeScript, Tailwind CSS, Shadcn UI
- Backend: Next.js API Routes, Prisma ORM, PostgreSQL
- Authentication: NextAuth.js (JWT)
- Real-time: Socket.IO
- DevOps: Docker, GitHub Actions (CI/CD), Vercel
- Testing: Jest, Playwright, React Testing Library

## Quick Start
1. Clone the repository:
   ```bash
   git clone https://github.com/Hsx07/ArtBridge-Cultural-Foundation-Web-System.git
   cd ArtBridge-Cultural-Foundation-Web-System
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables:
   ```bash
   cp .env.example .env.local
   # Edit .env.local with your configuration
   ```
4. Set up the database:
   ```bash
   npx prisma generate
   npx prisma db push
   # Optionally seed the database
   npx prisma db seed
   ```
5. Start the development server:
   ```bash
   npm run dev
   ```
6. Open your browser:
   http://localhost:3000

## License
This project is licensed under the MIT License.

## Author
El Houceine Katfi  
Student ID: 76833  
Program: Computer Engineering (54 DPH)  
Institution: Menedżerska Akademia Nauk Stosowanych w Warszawie  
GitHub: https://github.com/Hsx07

Built with love for the arts community.
