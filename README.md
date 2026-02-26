# AM Wall Studios - Premium Wallpaper Solutions

A modern, responsive website for AM Wall Studios - Pune's trusted name for premium wallpaper solutions and professional installation services.

## 🌟 Features

- **Responsive Design** - Mobile-first approach, works perfectly on all devices
- **Modern UI** - Built with React and Tailwind CSS
- **Image Carousel** - Hero section with automatic image rotation
- **Gallery** - Showcase of before/after transformations
- **Contact Form** - Collect customer inquiries
- **WhatsApp Integration** - Direct messaging button
- **Fast Performance** - Optimized for speed and SEO

## 🛠️ Tech Stack

- **React 18** - UI Framework
- **Tailwind CSS** - Styling
- **Lucide React** - Icons
- **Sonner** - Toast notifications
- **Vercel** - Hosting

## 📋 Prerequisites

- Node.js (v14 or higher)
- npm or yarn

## 🚀 Getting Started

### Installation

1. Clone the repository:
```bash
git clone https://github.com/vijayambekar0102-pixel/am-wall-studios.git
cd am-wall-studios
```

2. Install dependencies:
```bash
npm install
```

3. Create .env file:
```bash
cp .env.example .env
```

4. Start development server:
```bash
npm start
```

The app will open at [http://localhost:3000](http://localhost:3000)

## 📦 Build for Production

```bash
npm run build
```

This creates an optimized production build in the `build` folder.

## 🌐 Deployment

### Option 1: Deploy with Vercel (Recommended)

1. Go to [vercel.com](https://vercel.com)
2. Click "Import Project"
3. Connect your GitHub account
4. Select this repository
5. Click "Deploy"

Your site will be live in seconds!

### Option 2: Deploy with GitHub Pages

1. Add to `package.json`:
```json
"homepage": "https://vijayambekar0102-pixel.github.io/am-wall-studios"
```

2. Install gh-pages:
```bash
npm install --save-dev gh-pages
```

3. Add deploy scripts:
```json
"predeploy": "npm run build",
"deploy": "gh-pages -d build"
```

4. Deploy:
```bash
npm run deploy
```

### Option 3: Deploy with Netlify

1. Go to [netlify.com](https://netlify.com)
2. Connect your GitHub repository
3. Set build command: `npm run build`
4. Set publish directory: `build`
5. Deploy

## 📂 Project Structure

```
am-wall-studios/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   ├── Header.jsx
│   │   ├── Hero.jsx
│   │   ├── About.jsx
│   │   ├── Services.jsx
│   │   ├── Gallery.jsx
│   │   ├── Contact.jsx
│   │   ├── Footer.jsx
│   │   └── WhatsAppButton.jsx
│   ├── App.js
│   ├── App.css
│   ├── index.css
│   └── mockData.js
├── package.json
├── tailwind.config.js
├── postcss.config.js
└── README.md
```

## 🎨 Customization

### Update Business Information

Edit `src/mockData.js`:
```javascript
export const businessInfo = {
  name: "AM Wall Studios",
  tagline: "Transform Your Space with Premium Wallpaper",
  phone: "+91 87675 18914",
  whatsapp: "+91 87675 18914",
  email: "akshaymanyre@gmail.com",
  location: "Pune, Maharashtra",
  logo: "your-logo-url"
};
```

### Change Colors

Edit `tailwind.config.js` to customize the amber color scheme to your preference.

## 📞 Contact

- **Phone**: +91 87675 18914
- **Email**: akshaymanyre@gmail.com
- **Location**: Pune, Maharashtra

## 📄 License

This project is private and proprietary to AM Wall Studios.

## 🙏 Support

For issues or questions, contact us via WhatsApp or email.

---

**Built with ❤️ for AM Wall Studios**
