# LinkedIn Career GPS Prototype

A fully functional LinkedIn prototype showcasing the innovative "Career GPS" feature - an AI-powered career guidance system that helps professionals navigate their career journey.

## Overview

This prototype demonstrates a complete user journey for Riya Sharma, a Senior Program Manager with 14 years of experience who is actively seeking new opportunities. The demo automatically cycles through six key pages, showing how Career GPS transforms her career trajectory.

## Features

### 🎯 Auto-Playing Demo
The prototype automatically navigates through the complete journey with 2-second intervals between pages, creating a seamless video-like presentation that loops continuously.

### 📱 Six-Page Journey

1. **LinkedIn Home** - Riya's profile with "Open to Work" status
   - Green ring around profile picture indicating open to work status
   - Professional work update announcing job search
   - Career GPS sidebar with call-to-action

2. **Career GPS Dashboard** - Personalized career insights
   - AI-powered career recommendations
   - Skills gap analysis
   - Learning program suggestions
   - Job market insights

3. **Learning Progress** - In-progress course tracking
   - Strategic Leadership for Senior Managers (30% complete)
   - Advanced Product Strategy & Roadmapping (56% complete)
   - Learning statistics and insights
   - Career GPS recommendations

4. **Learning Plan** - Completed courses and certifications
   - Finished executive programs
   - Achievement tracking
   - Skill development roadmap

5. **Recruiter View** - How recruiters see Riya
   - Enhanced profile visibility
   - Top candidate positioning
   - Skills and experience highlights

6. **Success Story** - Career advancement outcome
   - Updated profile showing new role as Strategy Director
   - 14 years of experience highlighted
   - Career progression visualization
   - Achievement celebration

### 🎨 Authentic LinkedIn Design
- Pixel-perfect LinkedIn UI/UX replication
- Official LinkedIn color scheme (#0a66c2 blue, #10a37f green for open to work)
- Responsive layout matching real LinkedIn experience
- Interactive components and hover states

### ⚡ Technologies Used
- **React** with TypeScript
- **React Router** for navigation
- **Tailwind CSS** for styling
- **Lucide React** for icons
- **Radix UI** for accessible components

## Getting Started

### Prerequisites
- Node.js (v18 or higher)
- npm or pnpm package manager

### Installation

```bash
# Clone the repository
git clone [your-repo-url]

# Navigate to project directory
cd linkedin-career-gps

# Install dependencies
npm install
# or
pnpm install

# Start development server
npm run dev
# or
pnpm dev
```

### Building for Production

```bash
npm run build
# or
pnpm build
```

## Usage

Simply open the application in your browser. The demo will automatically start from Riya's LinkedIn home page and cycle through all six pages, looping continuously.

### Navigation Flow
```
LinkedIn Home (Riya Open to Work) 
    ↓ (2 seconds)
Career GPS Dashboard
    ↓ (2 seconds)
Learning Progress (30% & 56% completion)
    ↓ (2 seconds)
Learning Plan (Completed courses)
    ↓ (2 seconds)
Recruiter View
    ↓ (2 seconds)
Success Story (14 years experience)
    ↓ (2 seconds)
[Loops back to LinkedIn Home]
```

## Project Structure

```
/src
  /app
    /components
      - LinkedInHome.tsx         # Initial home page with open to work status
      - CareerGPS.tsx           # Career GPS dashboard
      - LearningProgress.tsx    # In-progress courses (30% & 56%)
      - LearningPlan.tsx        # Completed course tracking
      - RecruiterView.tsx       # Recruiter perspective
      - UpdatedLinkedInHome.tsx # Success story page (14 years)
      - AutoNavigate.tsx        # Auto-navigation logic
      /ui                       # Reusable UI components
    - App.tsx                   # Main application entry
    - routes.tsx               # Route configuration
  /styles
    - tailwind.css             # Tailwind configuration
    - theme.css                # Custom theme styles
```

## Key Components

### AutoNavigate
Handles automatic page transitions every 2 seconds, creating a seamless demo experience.

### Learning Progress (NEW)
Showcases active learning with:
- Strategic Leadership course at 30% completion
- Product Strategy course at 56% completion
- Learning statistics and time invested
- Career GPS insights on profile visibility boost

### Career GPS Feature
The core innovation showcasing:
- Personalized career roadmaps
- Skills gap analysis
- Job market insights
- Learning recommendations
- Networking opportunities

## Customization

### Adjusting Auto-Navigation Speed
Edit `/src/app/components/AutoNavigate.tsx`:
```typescript
const timer = setTimeout(() => {
  navigate(nextPath);
}, 2000); // Change this value (in milliseconds)
```

### Modifying Profile Information
Edit the respective component files to customize:
- Riya's profile details
- Work experience (currently 14 years)
- Skills and certifications
- Career progression
- Learning course completion percentages

## Use Cases

- **Product Demonstrations**: Showcase LinkedIn Career GPS concept to stakeholders
- **User Research**: Gather feedback on career guidance features
- **Presentations**: Auto-playing demo perfect for conferences and pitches
- **Portfolio**: Demonstrate UI/UX and full-stack development skills

## Contributing

This is a prototype for demonstration purposes. If you'd like to contribute improvements or report issues, please feel free to open an issue or submit a pull request.

## License

This project is a prototype and demonstration of a concept. LinkedIn is a registered trademark of LinkedIn Corporation and its affiliates.

## Acknowledgments

- Design inspired by LinkedIn's authentic user interface
- Built for demonstration and educational purposes
- Profile character "Riya Sharma" is fictional

## Contact

For questions or feedback about this prototype, please reach out or open an issue.

---

**Note**: This is a prototype demonstration and is not affiliated with or endorsed by LinkedIn Corporation.