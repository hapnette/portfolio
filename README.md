# Paige Nguyen Portfolio Website

A modern, responsive portfolio website built from Figma design specifications with exact fonts, colors, spacing, and components.

## 🎨 Design System

### Colors
- **Black**: `#000000`
- **White**: `#FFFAFA`
- **Snow**: `#FFFAFA`
- **Dark Red**: `#900A0B`

### Typography
- **Title Font**: Wasted Vindey (Regular, 60px)
- **H1 Font**: Wasted Vindey (Regular, 40px)
- **H3 Font**: Raleway (Light, 24px)
- **Description Font**: Raleway (Light, 14px)
- **Button Font**: Raleway (Light, 10px)

### Spacing System
- **XS**: 6px
- **SM**: 10px
- **MD**: 20px
- **LG**: 40px
- **XL**: 60px
- **XXL**: 80px
- **XXXL**: 100px

## 📁 Project Structure

```
Portfolio/
├── index.html              # Homepage HTML
├── about.html              # About page HTML
├── marimekko.html          # Marimekko project page HTML
├── been-together.html      # Been Together project page HTML
├── frank-app.html          # Frank App project page HTML
├── tierra-finlandia.html   # Tierra Finlandia project page HTML
├── mikaeli.html            # Mikaeli project page HTML
├── styles/
│   ├── homepage.css        # Homepage styles with design system
│   ├── about.css           # About page styles with design system
│   ├── marimekko.css       # Marimekko project page styles
│   ├── been-together.css   # Been Together project page styles
│   ├── frank-app.css       # Frank App project page styles
│   ├── tierra-finlandia.css # Tierra Finlandia project page styles
│   └── mikaeli.css         # Mikaeli project page styles
└── README.md               # This file
```

## 🚀 Features

- **Responsive Design**: Mobile-first approach with breakpoints at 1280px, 768px, and 480px
- **Design System**: CSS variables for consistent colors, fonts, and spacing
- **Semantic HTML**: Proper HTML5 structure with accessibility in mind
- **Modern CSS**: Flexbox and Grid layouts with smooth transitions
- **Portfolio Grid**: Responsive project cards with filtering system
- **Fixed Navigation**: Sticky header and footer for easy navigation

## 🎯 Components

### Navigation
- Fixed top navigation with logo and menu items
- Responsive design that adapts to different screen sizes
- Navigation between Homepage and About page

### Homepage
- **Hero Section**: Large title with custom Wasted Vindey font, subtitle and description with Raleway Light font, call-to-action button with arrow icon
- **Portfolio Section**: Filter buttons for different project categories, responsive grid of project cards with images, titles, descriptions, tags, and durations

### About Page
- **Profile Section**: Profile image with greeting and detailed description
- **Experience Grid**: Three-column layout for Education, Work Experience, and Leadership
- **Skills Section**: Skill Stack and Tool Stack headers with decorative line separator
- **Skills Grid**: 3x2 grid of skill cards covering UX/UI, Service Design, Research, and more
- **Personal Note**: Fun personal touch at the bottom

### Marimekko Project Page
- **Hero Section**: Full-screen background with project title and subtitle overlay
- **What is Marimekko**: Brand introduction and project focus
- **Project Background**: Problem statement, role, and challenge
- **Research Section**: Brand analysis, quote, and audience research
- **Tone and Voice Guidelines**: Brand personality and voice pillars
- **Conversation Mining**: User research and word lists
- **Copy Audit**: Before/after comparisons of UX writing improvements
- **Reflection**: Research effectiveness and testing methods

### Been Together Project Page
- **Hero Section**: Full-screen background with project title and subtitle overlay
- **What is Been Together**: App introduction and target audience
- **Project Background**: Problem statement, role, and challenge
- **Research Section**: User interviews, competitive analysis, and insights
- **User Journey Mapping**: Pain points and user experience flow
- **Strategize Section**: Solution ideation and feature planning
- **Design Section**: Color palette and typography decisions
- **Wireframe Section**: Design iterations and mockups
- **Test Section**: Usability testing and feedback
- **Reflection**: Testing improvements and optimization strategies

### Frank App Project Page
- **Hero Section**: Hot pink background with project title and iPhone mockups
- **What is Frank**: App introduction and user goals
- **Project Background**: Course context and design challenge
- **Research Section**: Student interviews and user persona creation
- **User Persona**: Detailed profile of Emilia Bellow (21, Helsinki student)
- **Pain Points Analysis**: Visual chart of user experience issues
- **Ideation Section**: App flow diagram and user journey mapping
- **Wireframe Section**: Design iterations and mockups
- **Test Section**: User testing results and refinement strategies
- **Design Section**: Color palette (#FD1E6E, #caaa77, #000000) and typography system
- **Final Prototype**: Placeholder for completed design
- **Key Takeaways**: Testing, User Persona, Pitching, Story-telling

### Tierra Finlandia Project Page
- **Hero Section**: Full-screen background with project title and subtitle overlay
- **What is Tierra Finlandia**: Service introduction and project focus
- **Project Background**: Problem statement and design challenge
- **Research Section**: Interactive dropdowns for research methods (Desk Research, Workshop, Interview)
- **Concept Ideas Section**: Interactive dropdowns for concept exploration
- **Design Section**: Visual concept representations and gallery
- **Key Takeaways**: Service Design, Business Strategy, Workshop Facilitation

### Mikaeli Project Page
- **Hero Section**: Full-screen background with project title and subtitle overlay
- **What is Mikaeli**: Concert hall introduction and target audience
- **Project Background**: Problem statement and design challenge
- **Audit Section**: Current website analysis and competitor research
- **Research Section**: User interviews and key insights
- **Ideation Section**: App flow and wireframe designs
- **Design Section**: Color palette (#F5EEDC, #B17F2E, #173C4E) and typography system
- **Logo Section**: Primary and secondary logo variations
- **Test Section**: Usability testing and refinement strategies
- **Final Prototype**: Interactive Figma prototype
- **Key Takeaways**: Testing, User Interview, Branding Design

### Footer
- Fixed bottom footer with contact information
- Social media links

## 🛠️ Setup Instructions

1. **Clone or download** the project files
2. **Open `index.html`** in your web browser
3. **View the website** - no build process required!

## 📱 Responsive Breakpoints

- **Desktop**: 1280px and above
- **Tablet**: 768px to 1279px
- **Mobile**: 480px to 767px
- **Small Mobile**: Below 480px

## 🎨 Customization

### Colors
Update the CSS variables in `:root` to change the color scheme:

```css
:root {
    --color-black: #000000;
    --color-white: #FFFAFA;
    --color-snow: #FFFAFA;
    --color-dark-red: #900A0B;
}
```

### Typography
Modify font sizes and families in the CSS variables:

```css
:root {
    --font-size-title: 60px;
    --font-size-h1: 40px;
    --font-size-h3: 24px;
    --font-size-description: 14px;
    --font-size-button: 10px;
}
```

### Spacing
Adjust the spacing system by updating the spacing variables:

```css
:root {
    --spacing-xs: 6px;
    --spacing-sm: 10px;
    --spacing-md: 20px;
    --spacing-lg: 40px;
    --spacing-xl: 60px;
    --spacing-xxl: 80px;
    --spacing-xxxl: 100px;
}
```

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📝 Notes

- The website uses localhost image URLs from the Figma design
- Custom fonts are loaded from Google Fonts (Raleway) and a custom source (Wasted Vindey)
- All measurements and spacing match the original Figma design exactly
- The design system is built with CSS custom properties for easy maintenance

## 🎯 Next Steps

To expand this portfolio website, consider adding:
- Additional pages (About, Resume, Contact)
- Project detail pages
- Contact form functionality
- Blog section
- Dark/light theme toggle
- Smooth scrolling and animations
- SEO optimization
- Performance optimization

---

Built with ❤️ from Figma design specifications
