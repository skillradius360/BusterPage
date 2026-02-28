# Buster Frontend

The user interface for Buster, an AI-powered authenticity checker for links and social posts.

## Tech Stack
- Next.js 16
- React 19
- Tailwind CSS 4

## Prerequisites
- Node.js 20+ (recommended)
- npm 10+

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/skillradius360/BusterPage.git
   ```
2. Move into the project:
   ```bash
   cd BusterPage
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. (Optional) Configure backend API base URL in `.env.local`:
   ```bash
   NEXT_PUBLIC_API_BASE_URL=http://localhost:8000
   ```
   If not set, the app defaults to `https://buster-3.onrender.com`.
5. Start the development server:
   ```bash
   npm run dev
   ```

Open `http://localhost:3000`.

## Production Check
```bash
npm run build
npm run start
```
