# Joshua Adante - Professional Portfolio

A modern, professional blue neon themed portfolio website for Joshua Adante, Web Developer & Graphic Designer. Built with React.js and featuring futuristic design elements, smooth animations, and responsive layouts.

## 🎨 Design Features

- **Blue Neon Theme**: Primary colors: Neon Blue (#00E5FF) and Dark Navy (#0A0F1C)
- **Glassmorphism Cards**: Blurred, transparent cards with neon borders
- **Smooth Animations**: Powered by Framer Motion
- **Dark Mode Default**: Professional dark aesthetic with glowing accents
- **Fully Responsive**: Optimized for mobile, tablet, and desktop
- **Clean Typography**: Professional fonts with text glowing effects

## 📋 Sections

### Hero
Centered landing section with glowing hero text and CTA buttons:
- "View Projects" button
- "Contact Me" button
- Animated background glows

### About Me
Professional background showcasing:
- Technical expertise
- Design philosophy
- Core skills and values

### Projects
"The Big Three" featured projects:
1. **What I Know** - Current Skills project showcasing React & UI design
2. **What I Learned** - Growth project with React hooks and state management
3. **What I Aspire To** - Future project vision with advanced concepts

Each project includes:
- Description
- Tech stack tags
- GitHub link
- Live demo button
- Neon hover effects

### Learning
Growth mindset showcase displaying currently learning:
- Advanced React patterns
- UI/UX principles
- Framer Motion animations
- Backend fundamentals
- CI/CD using GitHub & Vercel
- Web performance optimization

### Tech Stack
Visual display of technologies and tools:
- React.js
- JavaScript & TypeScript
- HTML5 & CSS3
- Framer Motion
- Git & GitHub
- Figma & Design tools

### Contact
Professional contact section featuring:
- Contact form with validation
- Social media links
- Quick navigation links
- Email subscription

### Footer
- Navigation links
- Social connections
- Copyright & credits

### Navigation
Fixed header with:
- Smooth scroll navigation
- Mobile hamburger menu
- Active link indicators
- Logo with neon glow

## 🚀 Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/joshuaadante/portfolio.git
cd portfolio
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open [http://localhost:5173](http://localhost:5173) in your browser

### Build for Production

```bash
npm run build
```

This creates an optimized production build in the `dist` folder.

### Preview Production Build

```bash
npm run preview
```

## 📦 Tech Stack

- **Framework**: React.js 18
- **Build Tool**: Vite
- **Styling**: CSS3 with custom properties
- **Animations**: Framer Motion
- **Language**: TypeScript
- **Package Manager**: npm

## 🎯 Project Structure

```
src/
├── components/
│   ├── Navigation.tsx
│   ├── Hero.tsx
│   ├── About.tsx
│   ├── Projects.tsx
│   ├── Growth.tsx
│   ├── TechStack.tsx
│   ├── Contact.tsx
│   ├── Footer.tsx
│   └── [component].css files
├── App.tsx
├── main.tsx
└── index.css
```

## 🔧 Customization

### Colors
Edit the CSS custom properties in `src/index.css`:
```css
:root {
  --primary-blue: #00E5FF;
  --primary-blue-2: #1DA1F2;
  --dark-navy: #0A0F1C;
  --dark-black: #050B14;
  /* ... other colors ... */
}
```

### Content
Update component files to customize:
- Hero text in `Hero.tsx`
- Projects in `Projects.tsx`
- Technologies in `TechStack.tsx`
- Social links in `Contact.tsx`

### Animations
Framer Motion animations can be customized in each component's motion properties.

## 🚢 Deployment

### Vercel (Recommended)

1. Push your code to GitHub
2. Connect repository to Vercel
3. Vercel automatically deploys on every push
4. Configure domain in Vercel dashboard

### Manual Deployment

1. Build the project: `npm run build`
2. Deploy the `dist` folder to your hosting provider
3. Ensure SPA routing is configured (route all requests to `index.html`)

## 📱 Responsive Breakpoints

- **Desktop**: 1024px and above
- **Tablet**: 768px to 1023px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

All components are fully responsive with optimized layouts for each breakpoint.

## ✨ Features

- ✅ Neon glow effects on buttons and headings
- ✅ Smooth scroll animations
- ✅ Mobile-friendly hamburger menu
- ✅ Optimized performance with Vite
- ✅ TypeScript for type safety
- ✅ Accessible HTML structure
- ✅ SEO-friendly markup
- ✅ Dark mode default
- ✅ Form validation
- ✅ Social media integration

## 🎬 Performance Optimizations

- Code splitting with Vite
- Lazy loading for animations
- Optimized CSS with custom properties
- Efficient re-renders with React
- Static export ready

## 📝 License

This project is personal and not licensed for commercial use without permission.

## 🤝 Support

For questions or suggestions, feel free to reach out through the contact form or social media links.

---

**Built with ❤️ and ✨ by Joshua Adante**
