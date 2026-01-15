# Next.js Testing App

A modern Next.js application built with TypeScript, React 19, and Tailwind CSS. This project serves as a testing ground for Next.js features and best practices.

## Tech Stack

- **Next.js** 16.1.1 - React framework for production
- **React** 19.2.3 - Latest React with new features
- **TypeScript** 5 - Type-safe development
- **Tailwind CSS** 4 - Utility-first CSS framework
- **ESLint** 9 - Code quality and consistency

## Quick Start

### Prerequisites

- Node.js (v18 or higher recommended)
- npm, yarn, pnpm, or bun

### Installation

Clone the repository and install dependencies:

```bash
npm install
# or
yarn install
# or
pnpm install
# or
bun install
```

### Development

Start the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

The application will hot-reload as you edit files. Start by modifying `app/page.tsx`.

### Build for Production

```bash
npm run build
npm start
```

### Linting

Check code quality with ESLint:

```bash
npm run lint
```

## Project Structure

```
app/
  ├── page.tsx          # Home page component
  ├── layout.tsx        # Root layout
  ├── globals.css       # Global styles
  └── favicon.ico       # Favicon
public/                 # Static assets
```

## Features

- Modern React 19 with functional components
- Type-safe development with TypeScript
- Responsive design with Tailwind CSS
- Dark mode support
- Font optimization with next/font
- Image optimization with next/image
- ESLint configuration for code quality

## Learning Resources

- [Next.js Documentation](https://nextjs.org/docs) - Official docs
- [Next.js Learn](https://nextjs.org/learn) - Interactive tutorials
- [React Documentation](https://react.dev) - Learn React
- [Tailwind CSS Docs](https://tailwindcss.com/docs) - CSS utilities

## Deployment

Deploy this application to Vercel with one click:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/jerrickhakim/next-js-testing-app)

For detailed deployment instructions, see the [Next.js deployment docs](https://nextjs.org/docs/app/building-your-application/deploying).

## License

This project is open source and available under the MIT License.
