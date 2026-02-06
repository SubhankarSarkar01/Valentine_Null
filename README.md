# 💌 Valentine's Day Gift - Interactive Proposal App

An interactive and playful Valentine's Day web application designed to help you confess your feelings with style, humor, and a touch of magic!

## ✨ Features

- **Interactive Yes/No Buttons** - The cheeky "No" button runs away when you try to click it! 👀
- **Animated Floating Hearts** - Beautiful floating heart animations in the background
- **Confetti Celebration** - When you click "Yes", celebrate with a burst of colorful confetti
- **Dynamic Messages** - Randomly generated romantic messages to set the mood
- **Dark & Light Themes** - Toggle between pink romance and dark mysterious themes
- **Fully Responsive** - Works perfectly on desktop, tablet, and mobile devices
- **Smooth Animations** - Custom CSS animations and transitions for a polished experience

## 🚀 Quick Start

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/SubhankarSarkar01/Valentine_Null.git
cd valentine_Gift-main
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

## 🛠 Available Commands

- `npm run dev` - Start development server with hot module replacement
- `npm run build` - Build for production
- `npm run preview` - Preview the production build locally
- `npm run deploy` - Build and deploy to GitHub Pages
- `npm run lint` - Run ESLint to check code quality

## 🎨 Tech Stack

- **React 19** - UI library
- **Vite** - Lightning-fast build tool and dev server
- **Tailwind CSS** - Utility-first CSS framework
- **Canvas Confetti** - Celebration animations
- **ESLint** - Code quality and consistency
- **Babel/React Compiler** - JavaScript transformation and optimization

## 📂 Project Structure

```
src/
├── App.jsx                 # Main application component
├── main.jsx               # Entry point
├── index.css              # Global styles
├── components/
│   └── Valentine.jsx      # Main Valentine proposal component
├── styles/
│   └── animations.css     # Custom CSS animations
└── assets/               # Static assets
```

## 🎭 How It Works

1. User visits the page and sees a romantic message
2. Two buttons appear: "Yes" and "No"
3. When clicking "Yes" - Confetti celebration! 🎉
4. When clicking "No" - The button playfully evades the cursor with humorous messages
5. Toggle between dark and bright themes for different moods

## 🌐 Deployment

This project is configured for easy deployment to GitHub Pages:

```bash
npm run deploy
```

The deployment script will automatically build your project and push it to the `gh-pages` branch.

## 📝 Customization

You can customize the app by editing:
- **Messages**: Modify the message generators in [Valentine.jsx](src/components/Valentine.jsx)
- **Colors**: Adjust Tailwind config in `tailwind.config.js`
- **Animations**: Edit animations in [animations.css](src/styles/animations.css)

## 👨‍💻 Author

Original concept by [SubhankarSarkar01](https://github.com/SubhankarSarkar01)

## 📄 License

This project is open source and available under the MIT License.

## 💝 Pro Tips

- Customize the `name` variable in Valentine.jsx to personalize the message
- Adjust animation speeds in animations.css for different moods
- Switch themes to match your aesthetic preferences
- Deploy it and share the link with your crush! 💕

---

**Made with ❤️ for Valentine's Day 2026**
