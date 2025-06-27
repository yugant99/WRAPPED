# 🛍️ Shop Mini - Shopping Wrapped Experience

A **React-based Shop Mini application** that provides users with a personalized "Wrapped" experience, showcasing their **shopping statistics** and **patterns** from the past year. Built for **embedding in React Native webviews** using the **Shopify Shop Minis platform**.

---

## ✨ Features

- **Shopping Wrapped Experience**: Interactive slideshow displaying year-end shopping statistics  
- **Personalized Insights**: Shopping personality analysis based on purchase patterns  
- **Visual Analytics**: Charts and graphs showing spending trends and category breakdowns  
- **Product Recommendations**: Personalized suggestions based on shopping history  
- **Mobile-First Design**: Optimized for touch interactions and mobile devices  
- **Animated Statistics**: Smooth counter animations and progress indicators  

---

## 🚀 Quick Start

### Prerequisites

- Node.js (v16 or higher)  
- npm or yarn  
- Shopify Shop Minis CLI  

### Installation

```bash
# Clone the repository
git clone <repository-url>
cd shop-mini

# Install dependencies
npm install
```

### Start the development server

```bash
npm start
# or
npx shop-minis dev
```

The application will be available at the URL provided by the Shop Minis CLI.

---

## 📁 Project Structure

```
src/
├── components/
│   ├── ProductRecommendations.tsx  # Product recommendation screen
│   ├── PurchaseWrapped.tsx         # Main wrapped experience component
│   └── WrappedSlides.tsx           # Individual slides for the wrapped experience
├── types/
│   └── index.ts                    # TypeScript type definitions
├── utils/
│   └── wrappedCalculations.ts      # Logic for calculating shopping statistics
├── App.tsx                         # Main application component with mock data
├── main.tsx                        # Application entry point
├── index.css                       # Global styles
└── manifest.json                   # Shop Mini configuration
```

---

## 🛠️ Technology Stack

- **Framework**: React 18.2.0 + TypeScript  
- **Styling**: Tailwind CSS v4  
- **Platform**: Shopify Shop Minis React SDK  
- **Build Tool**: Vite  
- **Dev CLI**: Shopify Shop Minis CLI  

---

## 📊 Data Structure

Processes shopping data such as:

- **Orders**: Total count, dates, and values  
- **Products**: Categories, brands, and individual items  
- **Spending Patterns**: Monthly breakdowns and trends  
- **User Insights**: Shopping personality and achievements  

---

## 🎨 Components Overview

### \`PurchaseWrapped\`
Main component orchestrating the wrapped experience.  
- Fetches data from Shopify GraphQL API  
- Manages slideshow and product recommendation flow  

### \`WrappedSlides\`
Slideshow component with:
- Auto-advance and manual controls  
- Progress indicators  
- Animated statistics  
- Touch-friendly navigation  

### \`ProductRecommendations\`
Displays tailored product suggestions based on user history and preferences.

---

## 🔧 Configuration

### Environment Setup
- **\`manifest.json\`**: Shop Mini metadata and permissions  
- **\`vite.config.mjs\`**: Tailwind and build configuration  
- **\`tsconfig.json\`**: TypeScript compiler options  

### Styling
- **Tailwind CSS v4**  
- Mobile-first and responsive  
- Touch-optimized UI  
- Modern visual effects: gradients, animations, glassmorphism  

---

## 📱 Mobile Optimization

- Touch navigation  
- Optimized viewport settings  
- Swipe gesture support  
- Responsive layout and typography  

---

## 🎯 Features in Detail

### Wrapped Slides

- **Welcome Screen**  
- **Order Statistics**  
- **Spending Overview**  
- **Category Analysis**  
- **Brand Loyalty**  
- **Shopping Personality**  
- **Final Summary & CTA**

### Analytics & Insights

- Monthly spending trends (interactive charts)  
- Category breakdown (donut charts)  
- Achievements and badges  
- Shopping streaks  
- Average order value  

---

## 🔄 Development Workflow

```bash
# Start development
npm start

# Build for production
npm run build

# Type checking
npm run type-check
```

### Guidelines

- Use **TypeScript**  
- Follow **React functional component** structure  
- Prioritize **mobile-first design**  
- Leverage **Shop Minis React SDK components**  
- Maintain clean and documented code  

---

## 🚀 Deployment

Deployed via **Shopify Shop Minis**. Ensure:

- **\`manifest.json\`** has correct permissions  
- Include **Privacy Policy** and **Terms of Service** URLs  
- Define **features and metadata** clearly  


---

**Built with ❤️ for the Shop platform**

