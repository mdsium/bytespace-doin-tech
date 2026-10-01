# ByteSpace New — Frontend Assessment

Frontend assessment project for **Doin Tech Limited**  
**Position:** Jr. Software Engineer (Frontend)  
**Project:** ByteSpace New Website

A high-performance, production-ready React landing page faithfully matching the Figma design specifications.

---



## 🛠️ Tech Stack

- **React 19** — Functional components, custom hooks, and modern reactive state
- **TypeScript** — Strict type safety for courses, categories, testimonials, and brand assets
- **Vite** — Blazing fast development server and optimized production bundler
- **Tailwind CSS v4** — Design system styling with custom typography and electric color palette
- **Framer Motion (`motion`)** — Smooth continuous 3D ornament animations, layout transitions, and mobile drawer
- **Lucide React** — Modern, lightweight interface iconography

---


## 📦 Project Structure

```text
src/
├── assets/                  # Brand vectors & graphical assets
├── components/
│   ├── home/
│   │   ├── CourseCard.tsx           # Reusable course card with avatars & meta tags
│   │   ├── CourseDiscovery.tsx      # Category pill filter & responsive course grid
│   │   ├── CreatorCTA.tsx           # Full-width royal blue creator callout
│   │   ├── CreatorFeatures.tsx      # Educator dashboard metrics & checklist
│   │   ├── Hero.tsx                 # Hero section with search & parallax tracking
│   │   ├── HeroStudentVisual.tsx    # Central student visual with lime halo & floating cards
│   │   ├── LearningPathCard.tsx     # Reusable learning path circular badge card
│   │   ├── LearningPaths.tsx        # 6-category learning paths grid
│   │   ├── ProfessionalGrowth.tsx   # Statistics & career growth layout
│   │   ├── TestimonialCard.tsx      # Community feedback card
│   │   ├── Testimonials.tsx         # Testimonials section with lime highlight block
│   │   └── TrustedBrands.tsx        # 5 Logoipsum partner brand logos
│   │
│   ├── layout/
│   │   ├── Footer.tsx               # Footer with newsletter form & directory links
│   │   └── Navbar.tsx               # Transparent/glass sticky header with mobile menu
│   │
│   └── ui/
│       ├── Button.tsx               # Reusable button variants (lime, blue, outline)
│       ├── Ornament3D.tsx           # Vector 3D shaded ornaments with motion
│       └── SectionHeading.tsx       # Standardized section headings
│
├── data/
│   ├── brands.ts                    # Partner brand metadata
│   ├── categories.ts                # Course categories list
│   ├── courses.ts                   # Courses dataset with instructors, pricing, metrics
│   ├── learningPaths.ts             # Learning paths configuration
│   └── testimonials.ts              # Learner & creator testimonials
│
├── pages/
│   ├── Home.tsx                     # Landing page composed in exact Figma order
│   ├── Login.tsx                    # Bonus login page
│   └── Signup.tsx                   # Bonus signup page
|   └── NotFound.tsx                 # NotFound page (url/404)
│
├── App.tsx                          # App routing setup
├── index.css                        # Tailwind imports & custom utility layers
└── main.tsx                         # React entry point
## Live link: https://bytespace-doin-tech-ten.vercel.app/
```
