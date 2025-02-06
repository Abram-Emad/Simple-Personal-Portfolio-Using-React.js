# Simple Personal Portfolio Using React.js

A modern, responsive, and customizable personal portfolio template built with React.js. Designed to help developers showcase their skills, projects, and professional information effectively.

## Features

- **Responsive Design**: Works seamlessly on mobile, tablet, and desktop
- **Modern UI**: Clean and professional interface with smooth animations
- **Multi-Section Layout**:
  - Hero Section with profile introduction
  - About Me with skills visualization
  - Projects Gallery with case studies
  - Contact Form with email integration
  - Social Media Links
- **Dark/Light Mode**: Built-in theme switcher
- **Performance Optimized**: Code splitting and lazy loading
- **SEO Friendly**: Meta tags and structured data for better search visibility
- **Easy Customization**: Modify content through configuration files

## Technologies Used

- **React.js** - Core framework
- **React Router** - Navigation and routing
- **Framer Motion** - Smooth animations
- **React Icons** - Icon library
- **EmailJS** - Contact form integration
- **CSS Modules** - Component-scoped styling
- **GitHub Pages** - Deployment

## Installation

1. Clone the repository:
   bash
   git clone https://github.com/Abram-Emad/Simple-Personal-Portfolio-Using-React.js.git
   
2. Install dependencies:
   bash
   cd Simple-Personal-Portfolio-Using-React.js
   npm install
   
3. Configure environment variables:
   Create `.env` file with your EmailJS credentials:
   
   REACT_APP_EMAILJS_SERVICE_ID=your_service_id
   REACT_APP_EMAILJS_TEMPLATE_ID=your_template_id
   REACT_APP_EMAILJS_USER_ID=your_user_id
   

## Customization Guide

### Content Configuration
Modify `src/data/config.js` to update:
- Personal information
- Skills list
- Project details
- Social media links
- SEO metadata

javascript
// Example config.js structure
export const personalInfo = {
  name: "John Doe",
  title: "Full Stack Developer",
  bio: "Passionate developer creating web solutions...",
  email: "contact@johndoe.com"
};

export const skills = [
  { name: "React", level: 90 },
  { name: "JavaScript", level: 85 },
  // Add more skills
];


### Styling
1. **Themes**: Modify colors in `src/styles/theme.css`
2. **Component Styles**: Edit corresponding CSS Module files
3. **Animations**: Adjust Framer Motion properties in component files

### Images
1. Replace `src/assets/profile.jpg` with your profile image
2. Update project images in `src/assets/projects/`

## Available Scripts

- `npm start`: Launch development server
- `npm build`: Create production build
- `npm test`: Run test suite
- `npm deploy`: Deploy to GitHub Pages

## Project Structure


- ├── public
- │   ├── index.html
- │   └── manifest.json
- ├── src
- │   ├── assets
- │   ├── components
- │   │   ├── Header
- │   │   ├── Hero
- │   │   ├── About
- │   │   ├── Projects
- │   │   ├── Contact
- │   │   └── Footer
- │   ├── data
- │   │   └── config.js
- │   ├── styles
- │   ├── App.js
- │   └── index.js
- ├── .env.example
- └── package.json


## Deployment

1. **GitHub Pages**:
   bash
   npm run deploy
   
2. **Netlify**:
   - Connect your repository
   - Set build command: `npm run build`
   - Publish directory: `build`

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Acknowledgments

- [React Documentation](https://reactjs.org/)
- [Framer Motion Documentation](https://www.framer.com/motion/)
- [Open Source Community](https://opensource.org/)
