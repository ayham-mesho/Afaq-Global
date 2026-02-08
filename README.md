# Afaq Global Corporate Website

A bilingual (Arabic/English) corporate website built with Next.js 13 and Strapi CMS, featuring dynamic content management, responsive design, and comprehensive business solutions showcase.

🔗 **Client:** [Afaq Global](https://www.facebook.com/profile.php?id=100063934360230) | 🌐 **Stack:** Next.js 13, Strapi CMS, React 18

---

## 📋 Overview

Corporate website solution for Afaq Global, integrating a modern Next.js frontend with a headless Strapi CMS backend. The project delivers a fully bilingual experience with dynamic content management capabilities, enabling the client to update content without developer intervention.

### Key Achievements

- **Full-Stack Integration:** Seamlessly connected Next.js frontend with Strapi headless CMS
- **Bilingual Platform:** Complete Arabic/English support with RTL layouts
- **Dynamic Content Management:** Client can manage all content through Strapi admin panel
- **70+ Custom Components:** Modular, reusable React components
- **Performance Optimized:** ISR (Incremental Static Regeneration) for fast page loads
- **SEO Ready:** Dynamic meta tags, sitemap generation, and structured data
- **Responsive Design:** Mobile-first approach with Bootstrap 5 and Tailwind CSS

---

## ✨ Features

### Content Management
- **Dynamic Pages:** All pages powered by Strapi CMS
- **Blog System:** Full-featured blog with categories and pagination
- **Product Catalog:** Filterable products with category management
- **Media Library:** Centralized asset management through Strapi
- **SEO Controls:** Per-page meta tags, Open Graph, and Twitter Cards

### User Experience
- **Hero Sliders:** Touch-enabled Swiper carousels with fade effects
- **Interactive Animations:** GSAP-powered scroll animations
- **Team Showcase:** Dynamic team member profiles
- **FAQ Section:** Collapsible accordion-style Q&A
- **Timeline Display:** Company milestones and history visualization
- **Gallery:** Lightbox-enabled image galleries
- **Contact Forms:** Validated forms with React Hook Form
- **WhatsApp Integration:** Floating WhatsApp chat button

### Multilingual Support
- **Arabic & English:** Complete UI translation
- **RTL Layouts:** Proper right-to-left support for Arabic
- **Locale-based Routing:** Clean URLs with language prefixes (/en/, /ar/)
- **Content Localization:** All CMS content available in both languages

---

## 🛠️ Tech Stack

### Frontend
- **Next.js 13.4** - React framework with App Router
- **React 18** - Latest React with concurrent features
- **next-intl 3.0** - Internationalization
- **Bootstrap 5** - UI framework
- **Tailwind CSS 3** - Utility-first CSS
- **GSAP** - Animation library

### CMS & Data
- **Strapi CMS** - Headless content management system
- **@strapi/blocks-react-renderer** - Rich text rendering
- **qs** - Query string parsing for complex API queries

### UI Components & Libraries
- **Swiper 8** - Modern touch slider
- **React Slick** - Carousel component
- **React Hook Form** - Form validation and handling
- **React CountUp** - Animated number counters
- **React Modal Video** - Video lightbox
- **Yet Another React Lightbox** - Image lightbox
- **React Share** - Social sharing buttons
- **React Phone Number Input** - International phone input
- **React Floating WhatsApp** - WhatsApp chat widget

### Icons & Assets
- **Font Awesome** - Icon library (solid, regular, brands)
- **Animate.css** - CSS animations
- **jQuery** - For legacy plugins integration

### Development Tools
- **TypeScript Types** - Type definitions for Node and React
- **Autoprefixer** - CSS vendor prefixing
- **PostCSS** - CSS processing

---

## 📁 Project Architecture

```
madeira/
├── public/
│   ├── assets/
│   │   ├── css/           # Global stylesheets (1.3MB)
│   │   ├── fonts/         # Custom web fonts (2.1MB)
│   │   ├── img/           # Images and graphics (8.8MB)
│   │   └── js/            # Utility scripts (606KB)
│   ├── next.svg
│   └── vercel.svg
│
├── src/
│   ├── app/
│   │   ├── [locale]/      # Internationalized routes
│   │   │   ├── (pages)/   # Page routes
│   │   │   │   ├── about-us/
│   │   │   │   ├── contact/
│   │   │   │   ├── news/
│   │   │   │   ├── products/
│   │   │   │   └── privacy-policy/
│   │   │   ├── page.jsx           # Homepage
│   │   │   ├── layout.jsx         # Root layout
│   │   │   ├── loading.jsx        # Loading state
│   │   │   ├── not-found.jsx      # 404 page
│   │   │   ├── providers.jsx      # Context providers
│   │   │   └── globals.css        # Global styles
│   │   │
│   │   ├── api/
│   │   │   └── backend.js         # Strapi API integration
│   │   │
│   │   ├── libs/
│   │   │   └── getData.js         # Data fetching utilities
│   │   │
│   │   ├── favicon.ico
│   │   ├── robots.txt
│   │   └── sitemap.js             # Dynamic sitemap
│   │
│   ├── components/
│   │   ├── Home/              # Homepage sections
│   │   │   ├── Banner/        # Hero slider
│   │   │   ├── Features/      # Features grid
│   │   │   ├── ChooseUs/      # Why choose us section
│   │   │   ├── Services/      # Services showcase
│   │   │   ├── Timeline/      # Company timeline
│   │   │   ├── Team/          # Team members
│   │   │   ├── faq/           # FAQ accordion
│   │   │   ├── Gallery/       # Image gallery
│   │   │   ├── CallToAction/  # CTA section
│   │   │   ├── Blog/          # Blog posts preview
│   │   │   ├── Brand.jsx      # Brand logos
│   │   │   ├── Header.jsx     # Page header
│   │   │   └── Modals.jsx     # Modal dialogs
│   │   │
│   │   ├── Header/            # Site header/navigation
│   │   ├── Footer/            # Site footer
│   │   ├── About Us/          # About page sections
│   │   ├── Contact us/        # Contact page components
│   │   ├── News/              # Blog/news components
│   │   ├── Shop/              # Product listing
│   │   ├── Part Details/      # Product details
│   │   ├── Single Brand/      # Brand showcase
│   │   ├── Breadcrumb/        # Navigation breadcrumbs
│   │   ├── common/            # Shared components
│   │   └── hooks/             # Custom React hooks
│   │
│   ├── data/                  # Static data files
│   ├── utils/                 # Utility functions
│   ├── i18n.js                # i18n configuration
│   └── middleware.js          # Next.js middleware
│
├── messages/
│   ├── en.json                # English translations
│   └── ar.json                # Arabic translations
│
├── styles/
│   ├── globals.css            # Global styles
│   ├── Home.module.css        # Homepage styles
│   └── custom.css             # Custom overrides
│
├── next.config.js             # Next.js configuration
├── postcss.config.js          # PostCSS configuration
├── jsconfig.json              # JavaScript configuration
└── package.json
```

---

## 🚀 Getting Started

### Prerequisites

- Node.js 16.0 or higher
- npm or yarn
- Strapi CMS backend (separate deployment)

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/madeira-afaq-global
cd madeira-afaq-global
```

2. **Install dependencies**
```bash
npm install
# or
yarn install
```

3. **Configure environment variables**

Create `.env.local` file:

```env
# API Configuration
NEXT_PUBLIC_API_URL=https://your-strapi-backend.com/api
NEXT_PUBLIC_MEDIA_URL=https://your-strapi-backend.com

# Site Configuration
NEXT_PUBLIC_SITE_URL=https://yourdomain.com

# Analytics (optional)
NEXT_PUBLIC_GA_ID=G-XXXXXXXXXX
```

4. **Run development server**
```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) to view the application.

---

## 🎨 Key Implementations

### 1. Strapi CMS Integration

Complete API integration layer with reusable fetch functions:

```javascript
// backend.js - API utility functions

// Simple data fetching
export async function fetchData(lang, endpoint) {
  const url = `${process.env.NEXT_PUBLIC_API_URL}/${endpoint}?locale=${lang}`;
  const res = await fetch(url, { next: { revalidate: 10 } });
  return await res.json();
}

// Fetch with populated relationships
export async function fetchDataWithPopulate(lang, endpoint, populateArray = "*") {
  const query = qs.stringify({
    locale: [lang],
    populate: populateArray,
  }, {
    encodeValuesOnly: true,
  });
  
  const url = `${process.env.NEXT_PUBLIC_API_URL}/${endpoint}?${query}`;
  const res = await fetch(url, { next: { revalidate: 10 } });
  return await res.json();
}

// Paginated data fetching
export async function fetchDataWithPagination(lang, endpoint, pageIndex, pageSize) {
  const url = `${process.env.NEXT_PUBLIC_API_URL}/${endpoint}?populate=*&locale=${lang}&pagination[page]=${pageIndex}&pagination[pageSize]=${pageSize}`;
  const res = await fetch(url, { next: { revalidate: 10 } });
  return await res.json();
}

// Filtered queries with pagination
export async function fetchDataWithPaginationAndFiltering(lang, endpoint, pageIndex, pageSize, category) {
  const query = qs.stringify({
    locale: [lang],
    populate: "*",
    pagination: { page: pageIndex, pageSize: pageSize },
    filters: {
      category_of_product: {
        CategoryTitle: { $contains: category }
      }
    }
  }, {
    encodeValuesOnly: true,
  });
  
  const url = `${process.env.NEXT_PUBLIC_API_URL}/${endpoint}?${query}`;
  const res = await fetch(url, { next: { revalidate: 10 } });
  return await res.json();
}
```

**Features:**
- Incremental Static Regeneration (10-second revalidation)
- Complex query string building with `qs`
- Relationship population
- Pagination support
- Filtering capabilities
- Locale-based content fetching

### 2. Bilingual Architecture

Implemented comprehensive internationalization:

```javascript
// middleware.js - Locale detection and routing
import createMiddleware from 'next-intl/middleware';

export default createMiddleware({
  locales: ['en', 'ar'],
  defaultLocale: 'en'
});

export const config = {
  matcher: ['/((?!api|_next|.*\\..*).*)']
};

// Usage in components
import { useTranslations } from 'next-intl';

const Component = () => {
  const t = useTranslations('default');
  return <h1>{t('welcome')}</h1>;
};
```

**Translation Structure:**
```json
// messages/en.json
{
  "default": {
    "welcome": "Welcome to Afaq Global",
    "about": "About Us",
    "services": "Our Services"
  }
}

// messages/ar.json
{
  "default": {
    "welcome": "مرحباً بكم في أفاق العالمية",
    "about": "من نحن",
    "services": "خدماتنا"
  }
}
```

### 3. Hero Slider Implementation

Custom Swiper carousel with advanced features:

```javascript
// Banner/index.jsx
import { Swiper, SwiperSlide } from 'swiper/react';
import { Autoplay, EffectFade, Navigation, Pagination } from 'swiper';

const BannerSlider = ({ heroData, lang }) => {
  const settings = {
    direction: 'horizontal',
    loop: true,
    autoplay: true,
    effect: 'fade',
    fadeEffect: { crossFade: true },
    pagination: {
      el: '.banner-pagination',
      type: 'bullets',
      clickable: true,
    },
    navigation: {
      nextEl: '.swiper-button-next',
      prevEl: '.swiper-button-prev',
    },
  };

  return (
    <Swiper {...settings}>
      {heroData.map((slide) => (
        <SwiperSlide key={slide.id}>
          <div className="hero-slide" style={{ backgroundImage: `url(${slide.image})` }}>
            <h1>{slide.title}</h1>
            <p>{slide.description}</p>
            <Link href={slide.link}>{slide.buttonText}</Link>
          </div>
        </SwiperSlide>
      ))}
    </Swiper>
  );
};
```

**Features:**
- Touch-enabled mobile navigation
- Fade transition effects
- Autoplay with custom timing
- Bullet pagination
- Arrow navigation
- Responsive breakpoints

### 4. Dynamic Sitemap Generation

SEO-optimized sitemap with dynamic routes:

```javascript
// app/sitemap.js
export default async function sitemap() {
  const baseUrl = process.env.NEXT_PUBLIC_SITE_URL;

  // Static pages
  const staticPages = [
    { url: `${baseUrl}/`, lastModified: new Date() },
    { url: `${baseUrl}/about-us`, lastModified: new Date() },
    { url: `${baseUrl}/contact`, lastModified: new Date() },
  ];

  // Dynamic pages from Strapi
  const posts = await fetchData('en', 'blogs-pages');
  const dynamicPages = posts.data.map((post) => ({
    url: `${baseUrl}/news/${post.attributes.slug}`,
    lastModified: post.attributes.updatedAt,
  }));

  return [...staticPages, ...dynamicPages];
}
```

### 5. Form Handling with Validation

Contact form with React Hook Form:

```javascript
import { useForm } from 'react-hook-form';

const ContactForm = () => {
  const { register, handleSubmit, formState: { errors } } = useForm();

  const onSubmit = async (data) => {
    // Submit to Strapi or email service
    await fetch(`${process.env.NEXT_PUBLIC_API_URL}/contact`, {
      method: 'POST',
      headers: { 'Content-Type': 'application/json' },
      body: JSON.stringify(data),
    });
  };

  return (
    <form onSubmit={handleSubmit(onSubmit)}>
      <input
        {...register('name', { required: 'Name is required' })}
        placeholder="Your Name"
      />
      {errors.name && <span>{errors.name.message}</span>}

      <input
        {...register('email', { 
          required: 'Email is required',
          pattern: {
            value: /^[A-Z0-9._%+-]+@[A-Z0-9.-]+\.[A-Z]{2,}$/i,
            message: 'Invalid email address'
          }
        })}
        placeholder="Your Email"
      />
      {errors.email && <span>{errors.email.message}</span>}

      <button type="submit">Send Message</button>
    </form>
  );
};
```

### 6. Performance Optimization

Implemented multiple optimization strategies:

```javascript
// Dynamic imports for heavy components
import dynamic from 'next/dynamic';

const ChooseUs = dynamic(() => import('../../components/Home/ChooseUs'), {
  ssr: false, // Client-side only rendering
  loading: () => <LoadingSpinner />
});

// Image optimization with Next.js Image
import Image from 'next/image';

<Image
  src={imageUrl}
  alt={altText}
  width={800}
  height={600}
  loading="lazy"
  placeholder="blur"
/>

// ISR with 10-second revalidation
const res = await fetch(url, {
  next: { revalidate: 10 }
});
```

---

## 📊 Strapi CMS Architecture

### Content Types Configured

1. **Global Settings**
   - Header logo
   - Footer logo
   - Social links
   - WhatsApp settings
   - SEO defaults

2. **Home Page**
   - Hero section (multiple slides)
   - Features section
   - Services grid
   - Team members
   - FAQ items

3. **Blog/News**
   - Posts with rich text
   - Categories
   - Featured images
   - Author information
   - SEO metadata

4. **Products**
   - Product catalog
   - Categories
   - Specifications
   - Images gallery
   - Pricing

5. **Pages**
   - About Us
   - Contact
   - Privacy Policy
   - Custom pages

### API Integration Pattern

```javascript
// getData.js - High-level data fetching

// Get homepage data with all relationships
export async function getHomePageData(lang) {
  return await fetchDataWithPopulate(lang, 'home-pages', [
    'HeroSection',
    'HeroSection.images',
    'BrandsSection',
    'BrandsSection.images',
    'PartsSection',
    'seo',
    'seo.metaImage',
    'seo.metaSocial',
    'seo.metaSocial.image',
  ]);
}

// Get blog posts with pagination
export async function getBlogPageData(lang, pageIndex, blogsPerPage) {
  return await fetchDataWithPagination(
    lang,
    'blogs-pages',
    pageIndex,
    blogsPerPage
  );
}

// Get products filtered by category
export async function getFilteredProducts(lang, pageIndex, pageSize, category) {
  return await fetchDataWithPaginationAndFiltering(
    lang,
    'products',
    pageIndex,
    pageSize,
    category
  );
}
```

---

## 🎯 Component Architecture

### Modular Component Structure

**Homepage Components:**
- `Banner` - Hero slider with CMS-driven slides
- `Features` - Icon-based feature grid
- `ChooseUs` - Why choose us section with statistics
- `Services` - Services showcase with hover effects
- `Timeline` - Company history visualization
- `Team` - Team member cards with social links
- `FAQ` - Accordion-style questions and answers
- `Gallery` - Lightbox-enabled image gallery
- `CallToAction` - Conversion-focused CTA section
- `Blog` - Latest blog posts preview

**Shared Components:**
- `Header` - Responsive navigation with language switcher
- `Footer` - Multi-column footer with sitemap
- `Breadcrumb` - Navigation breadcrumbs
- `Loading` - Loading state indicators
- `NotFound` - Custom 404 page

**Page Components:**
- About Us sections
- Contact form and info
- News/Blog listing and single post
- Product catalog and details
- Brand showcase pages

---

## 🌐 Deployment

### Production Build

```bash
# Build for production
npm run build

# Start production server
npm start
```

### Environment Configuration

**Production Variables:**
```env
NODE_ENV=production
NEXT_PUBLIC_API_URL=https://admin.afaqglobal.com/api
NEXT_PUBLIC_MEDIA_URL=https://admin.afaqglobal.com
NEXT_PUBLIC_SITE_URL=https://afaqglobal.com
```

### Deployment Options

**Vercel (Recommended):**
```bash
vercel --prod
```

**Manual Deployment:**
1. Build the application: `npm run build`
2. Upload `.next` folder to server
3. Install production dependencies
4. Run with PM2 or similar process manager

**Docker:**
```dockerfile
FROM node:18-alpine
WORKDIR /app
COPY package*.json ./
RUN npm ci --only=production
COPY . .
RUN npm run build
EXPOSE 3000
CMD ["npm", "start"]
```

---

## 🔧 Customization Guide

### Adding New Page

1. Create page component:
```javascript
// src/app/[locale]/(pages)/new-page/page.jsx
export default function NewPage({ params: { locale } }) {
  return (
    <>
      <Header lang={locale} />
      <YourContent />
      <Footer lang={locale} />
    </>
  );
}
```

2. Add translations:
```json
// messages/en.json
{
  "newPage": {
    "title": "New Page Title"
  }
}
```

3. Configure in Strapi:
   - Create content type
   - Add fields
   - Populate with content

### Adding New Component

```javascript
// src/components/NewSection/index.jsx
"use client";

import { useTranslations } from 'next-intl';

export default function NewSection({ lang }) {
  const t = useTranslations('default');
  
  return (
    <section className="new-section">
      <h2>{t('sectionTitle')}</h2>
      {/* Your content */}
    </section>
  );
}
```

---

## 📝 What This Project Demonstrates

### Technical Skills

✅ **Next.js 13 Expertise** - App Router, ISR, dynamic routing
✅ **Headless CMS Integration** - Strapi API, complex queries
✅ **Full-Stack Development** - Frontend + CMS architecture
✅ **Internationalization** - Complete bilingual implementation
✅ **API Architecture** - Reusable fetch utilities, caching
✅ **React Patterns** - Hooks, dynamic imports, optimization
✅ **Form Handling** - Validation, error handling, submission
✅ **SEO Implementation** - Meta tags, sitemap, structured data
✅ **Performance** - ISR, code splitting, lazy loading
✅ **Responsive Design** - Mobile-first, touch-enabled

### Professional Skills

✅ **CMS Integration** - Connected frontend to headless CMS
✅ **Client Delivery** - Empowered non-technical users
✅ **Content Strategy** - Structured content architecture
✅ **Production Deployment** - Live, serving real users
✅ **Multilingual Support** - Served Arabic and English markets
✅ **Component Architecture** - Modular, reusable system

---

## 🎓 Technical Decisions & Rationale

### Why Next.js + Strapi?

**Chose this stack because:**
- ✅ **Separation of Concerns:** Frontend and backend independently scalable
- ✅ **Client Empowerment:** Non-technical team manages content
- ✅ **Performance:** ISR provides fast page loads with fresh content
- ✅ **Flexibility:** Easy to change design without touching CMS
- ✅ **Developer Experience:** React + modern tooling

### Why Incremental Static Regeneration?

**ISR Benefits:**
- **Fast:** Pages served statically (CDN-cached)
- **Fresh:** Content updates every 10 seconds
- **Scalable:** No database queries on each request
- **SEO:** Fully rendered HTML for crawlers

### Component Architecture

**Modular Structure:**
- **Reusability:** Components used across pages
- **Maintainability:** Changes in one place
- **Testing:** Isolated component testing
- **Scalability:** Easy to add new sections

---

## 🐛 Development Notes

### Known Considerations

**Legacy Dependencies:**
- jQuery included for legacy plugins (Isotope, Magnific Popup)
- Migrating to React-native alternatives recommended

**Asset Size:**
- 13MB of static assets (images, fonts)
- Consider image optimization pipeline
- Implement WebP with fallbacks

**API Caching:**
- 10-second revalidation might be aggressive
- Adjust based on content update frequency
- Consider on-demand revalidation

---

## 🔮 Future Enhancements

Potential improvements for the platform:

- [ ] **Image Optimization Pipeline** - Automatic WebP conversion
- [ ] **Advanced SEO** - Schema.org structured data
- [ ] **E-commerce Features** - Shopping cart, checkout
- [ ] **User Authentication** - Member portal, saved preferences
- [ ] **Search Functionality** - Full-text search across content
- [ ] **Analytics Dashboard** - Content performance metrics
- [ ] **Email Marketing** - Newsletter integration
- [ ] **Live Chat** - Real-time customer support
- [ ] **Mobile App** - React Native companion app
- [ ] **Third Language** - Expand beyond Arabic/English

---

## 👤 Author

**Ayham Mesho**  
Full-Stack Developer | Next.js & Strapi Specialist

- **Portfolio:** [ayhammesho.com](https://www.ayhammesho.com)
- **LinkedIn:** [linkedin.com/in/ayhammesho](https://www.linkedin.com/in/ayhammesho/)
- **GitHub:** [github.com/yourusername](https://github.com/yourusername)
- **Email:** ayham.mesho.dev@gmail.com

---

## 🙏 Acknowledgments

- **Afaq Global** - For trusting me with their digital presence
- **Next.js Team** - For the excellent framework
- **Strapi Team** - For the powerful headless CMS
- **Vercel** - For the deployment platform

---

## 📄 License

This project was developed for Afaq Global. The code is shared for portfolio and reference purposes.

**Next.js** is licensed under the MIT License.  
**Strapi** is licensed under the MIT License.  
**Custom implementation** © 2024 Ayham Mesho

---

## 🌟 Project Impact

**Results Delivered:**

- **Bilingual Platform:** Serving both Arabic and English markets seamlessly
- **Content Autonomy:** Client team manages content without developer help
- **Performance:** Fast page loads with ISR strategy
- **SEO Optimized:** Proper meta tags, sitemap, and structured data
- **Mobile Experience:** Responsive design for all devices
- **Scalability:** Architecture supports unlimited content growth

**Client Value:**
*"The integration of Strapi CMS transformed how we manage our website. We can now update content, add blog posts, and manage products ourselves without waiting for development cycles. The bilingual support has helped us reach both Arabic and English-speaking customers effectively."*

---

**Built With:** Next.js 13, Strapi CMS, React 18, next-intl, Bootstrap 5, Tailwind CSS

**Note:** This project demonstrates full-stack development capabilities, headless CMS integration, and bilingual web application architecture. The implementation showcases modern web development practices with a focus on performance, SEO, and content management flexibility.

---

## 📸 Client Information

**Afaq Global** is a corporate services company serving the Middle East market.

- **Facebook:** [Afaq Global Profile](https://www.facebook.com/profile.php?id=100063934360230)
- **Services:** Corporate solutions and business services
- **Market:** Arabic and English-speaking regions

---

**Project Timeline:** Delivered as part of professional client work  
**Status:** Successfully delivered and deployed (client may have migrated to new platform)
