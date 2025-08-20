# Paradise Club Hotel - Tropical Paradise Website

A modern, responsive landing page for Paradise Club Hotel featuring a tropical paradise theme with beach, palm trees, turquoise, coral, sandy beige, and tropical green color scheme.

## 🌴 Features

- **Responsive Design**: Works seamlessly on both desktop and mobile devices
- **Tropical Paradise Theme**: Beautiful beach-inspired design with modern aesthetics
- **Clean Layout**: Uncluttered and user-friendly interface
- **Hero Section**: Stunning background imagery with strong call-to-action
- **Hotel Selection**: Showcases Tropics Beach and Malibu Hotel options
- **Modern UI**: Built with React, TypeScript, and Tailwind CSS
- **Fast Loading**: Optimized for performance with minimal dependencies

## 🚀 Getting Started

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn package manager

### Installation

1. Clone the repository:
```bash
git clone [your-repository-url]
cd Hotel-website-master
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Start the development server:
```bash
npm run dev
# or
yarn dev
```

4. Open your browser and navigate to `http://localhost:5173`

## 🏗️ Build for Production

To create a production build:

```bash
npm run build
# or
yarn build
```

The built files will be in the `dist` folder, ready for deployment.

## 🌐 Deployment

### Option 1: Netlify (Recommended)

1. Push your code to GitHub
2. Connect your repository to Netlify
3. Set build command: `npm run build`
4. Set publish directory: `dist`
5. Deploy!

### Option 2: Vercel

1. Push your code to GitHub
2. Import your repository to Vercel
3. Vercel will automatically detect it's a Vite project
4. Deploy with one click

### Option 3: Traditional Web Hosting

1. Run `npm run build`
2. Upload the contents of the `dist` folder to your web server
3. Ensure your server is configured to serve single-page applications

### Option 4: GitHub Pages

1. Add this to your `package.json`:
```json
"homepage": "https://yourusername.github.io/your-repo-name",
"scripts": {
  "predeploy": "npm run build",
  "deploy": "gh-pages -d dist"
}
```

2. Install gh-pages: `npm install --save-dev gh-pages`
3. Deploy: `npm run deploy`

## 🎨 Customization

### Changing Hotel Names

To update the hotel selection options, edit `src/data/roomsList.ts`:

```typescript
export const rooms = [
  {
    name: "Your Hotel Name",
    desc: "Your hotel description...",
    // ... other properties
  }
];
```

### Updating Colors

The tropical theme colors are defined in `tailwind.config.js`. You can customize:

- **Turquoise**: Primary accent color
- **Coral**: Secondary accent color  
- **Sandy Beige**: Background tones
- **Tropical Green**: Primary brand color

### Modifying Content

All text content is located in the component files under `src/sections/` and `src/components/`. Simply edit the text content to match your hotel's information.

## 📱 Responsive Design

The website is fully responsive and includes:

- Mobile-first design approach
- Breakpoints for various screen sizes
- Touch-friendly navigation
- Optimized images for different devices

## 🛠️ Technology Stack

- **Frontend**: React 18 + TypeScript
- **Styling**: Tailwind CSS
- **Build Tool**: Vite
- **Icons**: React Icons
- **Smooth Scrolling**: React Scroll
- **Routing**: React Router DOM

## 📁 Project Structure

```
src/
├── components/          # Reusable UI components
├── sections/           # Main page sections
├── data/              # Static data and content
├── assets/            # Images, icons, and media
├── context/           # Global state management
├── fonts/             # Custom font files
└── main.tsx          # Application entry point
```

## 🔧 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 📞 Support

For customization help or deployment issues:

1. Check the component files for commented code
2. Review the Tailwind CSS classes for styling
3. Ensure all dependencies are properly installed
4. Verify your build output in the `dist` folder

## 🌟 Features Overview

- **Hero Section**: Eye-catching tropical imagery with booking CTAs
- **About Section**: Hotel story and tropical paradise description
- **Rooms**: Showcase of tropical-themed accommodations
- **Facilities**: Beach restaurant, conference center, and sunset bar
- **Gallery**: Visual showcase of paradise experiences
- **Contact**: Easy booking and communication options

---

**Paradise Club Hotel** - Where tropical dreams become reality 🌺
