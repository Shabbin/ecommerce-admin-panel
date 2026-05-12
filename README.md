# E-Commerce Admin Panel

A modern, full-featured admin dashboard for managing e-commerce operations. Built with cutting-edge web technologies for optimal performance and developer experience.

## 🚀 Features

- **Modern Tech Stack**: Next.js 16, React 19, TypeScript
- **Responsive Design**: Mobile-first approach with Tailwind CSS
- **Type-Safe**: Full TypeScript support for robust development
- **Developer Experience**: ESLint, Tailwind CSS v4, and PostCSS configured
- **Dark Mode Support**: Built-in dark mode with CSS variables
- **Optimized Performance**: Next.js App Router with modern optimization techniques

## 📋 Tech Stack

| Technology | Version | Purpose |
|-----------|---------|---------|
| **Next.js** | 16.1.6 | React framework for production |
| **React** | 19.2.3 | UI library |
| **React DOM** | 19.2.3 | DOM rendering |
| **TypeScript** | ^5 | Type safety |
| **Tailwind CSS** | ^4 | Utility-first CSS framework |
| **ESLint** | ^9 | Code quality & linting |

## 📊 Project Statistics

- **Primary Language**: TypeScript (77.9%)
- **Secondary Language**: JavaScript (11.8%)
- **Styling**: CSS (10.3%)
- **Repository Size**: 62 KB

## 🏗️ Project Structure

```
ecommerce-admin-panel/
├── app/
│   ├── layout.tsx          # Root layout with font configuration
│   ├── page.tsx            # Home page component
│   └── globals.css         # Global styles with Tailwind
├── public/                 # Static assets
├── package.json            # Dependencies and scripts
├── tsconfig.json          # TypeScript configuration
├── tailwind.config.ts     # Tailwind CSS configuration
├── postcss.config.mjs     # PostCSS configuration
├── next.config.ts         # Next.js configuration
├── eslint.config.mjs      # ESLint rules
├── postcss.config.mjs     # PostCSS plugins
└── .gitignore             # Git ignore patterns
```

## 🛠️ Installation & Setup

### Prerequisites
- Node.js 18+ or higher
- npm or yarn package manager

### Install Dependencies

```bash
npm install
# or
yarn install
# or
pnpm install
```

### Development Server

Start the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## 📚 Available Scripts

```bash
# Start development server
npm run dev

# Build for production
npm run build

# Start production server
npm start

# Run ESLint to check code quality
npm run lint
```

## 🎨 Styling

The project uses **Tailwind CSS v4** with PostCSS for styling:

- **Global Styles**: `/app/globals.css` with Tailwind imports
- **Color Scheme**: Supports light and dark modes via CSS variables
- **Font**: Geist Sans and Geist Mono from Google Fonts
- **Responsive**: Mobile-first responsive design

### CSS Variables

```css
--background: #ffffff (light) / #0a0a0a (dark)
--foreground: #171717 (light) / #ededed (dark)
```

## ✅ Code Quality

The project includes ESLint configuration for code quality:
- Next.js recommended rules
- TypeScript linting
- Core Web Vitals compliance

Run linting:
```bash
npm run lint
```

## 🔧 Configuration Files

### TypeScript (`tsconfig.json`)
- Target: ES2017
- Module resolution: Bundler
- Path aliases: `@/*` maps to root directory
- Strict mode enabled

### Next.js (`next.config.ts`)
- Base configuration for Next.js 16
- Ready for custom configuration

### Tailwind CSS
- Configured with PostCSS for processing
- Tailwind v4 with modern CSS features

## 🌙 Dark Mode

Dark mode is built-in and automatically responds to system preferences using `prefers-color-scheme` media query.

## 📦 Dependencies Summary

### Production
- `next` - React framework
- `react` - UI library
- `react-dom` - DOM utilities

### Development
- `@types/node`, `@types/react`, `@types/react-dom` - TypeScript definitions
- `tailwindcss` - CSS framework
- `@tailwindcss/postcss` - Tailwind PostCSS plugin
- `eslint` & `eslint-config-next` - Linting
- `typescript` - Language support

## 🚀 Deployment

### Deploy to Vercel (Recommended)

The easiest way to deploy your Next.js admin panel is with [Vercel](https://vercel.com):

1. Push your repository to GitHub
2. Import the project in Vercel
3. Vercel will automatically build and deploy

```bash
npm run build
npm start
```

## 📝 Environment Variables

Create a `.env.local` file for environment-specific variables:

```env
# Example - adjust as needed
# NEXT_PUBLIC_API_URL=http://localhost:3000
# DATABASE_URL=your_database_url
```

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the MIT License.

## 🔗 Useful Resources

- [Next.js Documentation](https://nextjs.org/docs)
- [React Documentation](https://react.dev)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [TypeScript Documentation](https://www.typescriptlang.org/docs)

## 📞 Support

For issues, questions, or suggestions, please open an issue on GitHub or check the documentation links above.

---

**Created**: February 7, 2026  
**Last Updated**: February 8, 2026  
**Author**: [Shabbin](https://github.com/Shabbin)
