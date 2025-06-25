# Kiran G V - Portfolio Website

A modern, responsive portfolio website built with Next.js, showcasing full-stack development skills, AI/ML projects, and IoT solutions.

## 🚀 Features

- **Modern Design**: Dark theme with vibrant cyan/blue accents
- **Responsive**: Optimized for desktop, tablet, and mobile devices
- **Smooth Animations**: CSS transitions and hover effects throughout
- **Performance Optimized**: Built with Next.js for fast loading
- **SEO Friendly**: Optimized meta tags and structure

## 🛠️ Tech Stack

- **Framework**: Next.js 14
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Deployment**: Vercel/Netlify ready

## 📦 Installation

1. Clone the repository:
\`\`\`bash
git clone <your-repo-url>
cd kirana-portfolio
\`\`\`

2. Install dependencies:
\`\`\`bash
npm install
# or
yarn install
# or
pnpm install
\`\`\`

3. Run the development server:
\`\`\`bash
npm run dev
# or
yarn dev
# or
pnpm dev
\`\`\`

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## 🚀 Deployment

### Vercel (Recommended)
1. Push your code to GitHub
2. Connect your repository to Vercel
3. Deploy automatically

### Netlify
1. Build the project: `npm run build`
2. Deploy the `out` folder to Netlify

### Manual Deployment
1. Build the project: `npm run build`
2. The static files will be in the `out` folder
3. Upload to any static hosting service

## 📁 Project Structure

\`\`\`
├── app/
│   ├── globals.css
│   ├── layout.tsx
│   └── page.jsx
├── components/
│   ├── About.jsx
│   ├── Achievements.jsx
│   ├── Contact.jsx
│   ├── Experience.jsx
│   ├── Hero.jsx
│   ├── Navigation.jsx
│   ├── Projects.jsx
│   └── Skills.jsx
├── public/
│   └── images/
│       └── kirana-photo.jpg
├── next.config.mjs
├── tailwind.config.js
└── package.json
\`\`\`

## 🎨 Customization

### Colors
Update the color scheme in `tailwind.config.js` and `globals.css`.

### Content
Modify the content in each component file:
- Personal info: `components/Hero.jsx` and `components/About.jsx`
- Projects: `components/Projects.jsx`
- Skills: `components/Skills.jsx`
- Experience: `components/Experience.jsx`

### Images
Replace `public/images/kirana-photo.jpg` with your own photo.

## 📧 Contact Form

The contact form opens the user's default email client with pre-filled information. No backend required.

## 🔧 Environment Variables

No environment variables required for basic functionality.

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## 📞 Support

If you have any questions or need help with deployment, feel free to reach out.
\`\`\`

```vercel file=".vercelignore"
README.md
.env*.local
.git
node_modules
