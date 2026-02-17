# Pioneers - Tech Startup Website

A modern, minimalist tech startup website built with React, TypeScript, and Tailwind CSS. Featuring a striking design with electric cyan accents and geometric patterns.

## 🚀 Features

- **Modern Design**: Minimalist aesthetic with kinetic energy and smooth animations
- **Responsive Layout**: Mobile-first design that works on all devices
- **Company Profile**: Comprehensive company information and mission statement
- **Product Showcase**: Three flagship products with detailed descriptions
- **Team Section**: Meet the team with social media integration
- **Call-to-Action**: Strategic CTAs throughout the site

## 📋 Sections

1. **Navigation** - Fixed header with smooth scrolling
2. **Hero** - Eye-catching hero section with geometric background
3. **About** - Company story and key metrics
4. **Products** - CloudSync, DevFlow, and TeamHub with hover effects
5. **Team** - Team member profiles with social links
6. **Footer** - Comprehensive footer with links and social media

## 🎨 Design System

- **Color Scheme**: Deep charcoal (#0F172A) with electric cyan (#00D9FF) accents
- **Typography**: Space Mono for headlines, Inter for body text
- **Layout**: Asymmetric, modern layouts with diagonal dividers
- **Animations**: Smooth scroll-triggered animations and hover effects

## 🛠️ Tech Stack

- **Frontend**: React 19 + TypeScript
- **Styling**: Tailwind CSS 4
- **Components**: shadcn/ui
- **Icons**: Lucide React
- **Build Tool**: Vite

## 📦 Installation

```bash
# Install dependencies
pnpm install

# Start development server
pnpm run dev

# Build for production
pnpm run build

# Preview production build
pnpm run preview
```

## 🚀 Deployment

This project is configured for Vercel deployment:

1. Push to your GitHub repository
2. Connect your repo to Vercel
3. Vercel will automatically build and deploy on each push

### Environment Variables

No environment variables are required for this static site.

## 📝 Project Structure

```
client/
  public/          # Static assets
  src/
    pages/         # Page components
    components/    # Reusable UI components
    index.css      # Global styles and design tokens
    App.tsx        # Main app component
    main.tsx       # Entry point
server/            # Server configuration (static deployment)
```

## 🔧 Customization

### Update Company Information

Edit `client/src/pages/Home.tsx` to customize:
- Company name and tagline
- Product descriptions
- Team members
- Contact information

### Modify Colors

Update the CSS variables in `client/src/index.css`:
- `--primary`: Main accent color
- `--background`: Background color
- `--foreground`: Text color

### Add New Sections

Create new components in `client/src/components/` and import them into `Home.tsx`.

## 📄 License

MIT License - feel free to use this project as a template for your own startup website.

## 👥 Support

For questions or issues, please create an issue in the repository.

---

Built with ❤️ by Pioneers
