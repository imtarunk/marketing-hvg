# Hubvestor Landing Page

A modern, responsive landing page for the Hubvestor platform - a startup-investor matching platform.

## 🚀 Features

- **Modern Design**: Built with Next.js 15 and Tailwind CSS
- **Responsive**: Mobile-first design that works on all devices
- **Interactive**: Smooth animations and transitions
- **SEO Optimized**: Built with best practices for search engines
- **Fast Loading**: Optimized for performance

## 🏗️ Structure

```
pointer-landing-template/
├── app/                    # Next.js app directory
├── components/             # React components
│   ├── hero-section.tsx    # Main hero section
│   ├── header.tsx          # Navigation header
│   ├── bento-section.tsx   # Features grid
│   ├── cta-section.tsx     # Call-to-action
│   ├── faq-section.tsx     # FAQ section
│   └── footer-section.tsx  # Footer
├── public/                 # Static assets
└── styles/                 # Global styles
```

## 🛠️ Setup

### Prerequisites

- Node.js 18+
- pnpm (recommended) or npm

### Installation

1. **Clone the repository**

   ```bash
   git clone <your-repo-url>
   cd pointer-landing-template
   ```

2. **Install dependencies**

   ```bash
   pnpm install
   # or
   npm install
   ```

3. **Configure environment variables**

   ```bash
   cp .env.example .env.local
   ```

   Update `.env.local` with your configuration:

   ```env
   NEXT_PUBLIC_HUBVESTOR_PLATFORM_URL=https://your-platform-url.com
   ```

4. **Run the development server**

   ```bash
   pnpm dev
   # or
   npm run dev
   ```

5. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 🔧 Customization

### Updating Platform URLs

All links to the main Hubvestor platform are configured through environment variables. Update the following in `.env.local`:

```env
NEXT_PUBLIC_HUBVESTOR_PLATFORM_URL=https://your-actual-platform-url.com
```

### Modifying Content

- **Hero Section**: Edit `components/hero-section.tsx`
- **Features**: Edit `components/bento-section.tsx`
- **FAQ**: Edit `components/faq-section.tsx`
- **Footer**: Edit `components/footer-section.tsx`

### Styling

The landing page uses Tailwind CSS with a custom design system. Key files:

- `tailwind.config.ts` - Tailwind configuration
- `styles/globals.css` - Global styles
- `components.json` - shadcn/ui configuration

## 🚀 Deployment

### Vercel (Recommended)

1. **Connect your repository to Vercel**
2. **Set environment variables** in Vercel dashboard
3. **Deploy** - Vercel will automatically build and deploy

### Other Platforms

The landing page can be deployed to any platform that supports Next.js:

- **Netlify**: Connect your repository and deploy
- **Railway**: Import your repository and deploy
- **Self-hosted**: Build and serve the static files

## 📱 Integration with Main Platform

The landing page is designed to seamlessly integrate with your main Hubvestor platform:

### Authentication Flow

- **"Get Started"** button → `/auth/sign-up` on main platform
- **"Sign In"** button → `/auth/login` on main platform

### Navigation

- All navigation links point to the main platform
- Smooth transition between landing page and main app

## 🎨 Design System

### Colors

- Primary: Blue gradient (`hsl(var(--primary))`)
- Secondary: Neutral tones
- Background: Light/dark theme support

### Typography

- Headings: Inter font family
- Body: System font stack
- Responsive font sizes

### Components

- Built with shadcn/ui components
- Consistent spacing and sizing
- Accessible design patterns

## 📊 Analytics

To add analytics, update your `.env.local`:

```env
NEXT_PUBLIC_GOOGLE_ANALYTICS_ID=your-ga-id
```

## 🔒 Security

- All external links use `target="_blank"` and `rel="noopener noreferrer"`
- Environment variables for sensitive configuration
- No sensitive data stored in the landing page

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License.

## 🆘 Support

For support or questions:

- Create an issue in the repository
- Contact the development team
- Check the documentation

---

**Hubvestor** - Connect startups with the right investors
# marketing-hvg
