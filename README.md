# Sweet Treats Bakery Website 🧁

A modern, responsive bakery website built with Next.js 15, featuring an elegant design, interactive shopping cart, comprehensive admin dashboard, and full e-commerce functionality.

## ✨ Features

### Customer-Facing Features
- **Modern Homepage** with hero section, featured products, testimonials, and contact form
- **Product Catalog** with search functionality and category filtering
- **Interactive Shopping Cart** with localStorage persistence
- **About Page** showcasing bakery story, values, and team
- **Menu Page** with detailed product categories and pricing
- **Location Page** with business hours, contact info, and directions
- **Customer Testimonials** with interactive carousel
- **Responsive Design** optimized for all devices

### Admin Features
- **Professional Dashboard** with overview statistics
- **Order Management** with status tracking and filtering
- **Product Management** with CRUD operations
- **Inventory Control** with stock management
- **Real-time Updates** and interactive UI

### Technical Features
- **Next.js 15** with Turbopack for fast development
- **TypeScript** for type safety
- **Tailwind CSS** for modern styling
- **Custom CSS Variables** for consistent theming
- **Image Optimization** with Next.js Image component
- **SEO Optimized** with comprehensive meta tags
- **Accessibility** with proper alt texts and semantic HTML

## 🎨 Design

The website features an elegant bakery theme with:
- **Warm Color Palette**: Gold (#D4AF37), brown (#8B4513), and cream tones
- **Premium Typography**: Playfair Display for headings, Inter for body text
- **Full Viewport Layouts** with immersive sections
- **Smooth Animations** and hover effects
- **Professional UI Components** with consistent spacing

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ 
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd bakery-website
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

## 📁 Project Structure

```
src/
├── app/
│   ├── components/          # Reusable UI components
│   │   ├── Header.tsx       # Navigation header
│   │   ├── Hero.tsx         # Homepage hero section
│   │   ├── Products.tsx     # Product showcase
│   │   ├── ProductCard.tsx  # Individual product card
│   │   ├── Testimonials.tsx # Customer reviews
│   │   ├── Footer.tsx       # Site footer
│   │   └── Dashboard/       # Admin dashboard components
│   ├── about/              # About page
│   ├── products/           # Products catalog page
│   ├── menu/               # Menu/services page
│   ├── location/           # Location and hours page
│   ├── dashboard/          # Admin dashboard
│   ├── layout.tsx          # Root layout with SEO
│   └── page.tsx            # Homepage
├── styles/
│   ├── main.css            # Global styles and layout
│   └── theme.css           # Color palette and fonts
```

## 🛠️ Key Components

### ProductCard
Interactive product cards with:
- Quantity selector
- Add to cart functionality
- Price display
- Hover animations

### Dashboard
Comprehensive admin interface with:
- Statistics overview
- Order management table
- Product CRUD operations
- Sidebar navigation

### Shopping Cart
Persistent cart system with:
- localStorage integration
- Real-time price calculation
- Item quantity management
- Visual notifications

## 🎯 Pages

- **/** - Homepage with hero, products, testimonials, contact
- **/about** - Bakery story, values, and team information
- **/products** - Full product catalog with search and filtering
- **/menu** - Detailed menu with categories and pricing
- **/location** - Business location, hours, and contact details
- **/dashboard** - Admin panel for order and product management

## 🔧 Configuration

### Image Optimization
External images are configured in `next.config.ts`:
```typescript
images: {
  remotePatterns: [
    {
      protocol: 'https',
      hostname: 'images.unsplash.com',
    },
  ],
}
```

### Styling
Custom CSS variables in `styles/theme.css`:
- Color palette
- Typography (Google Fonts)
- Responsive breakpoints

## 📱 Responsive Design

The website is fully responsive with:
- Mobile-first approach
- Flexible grid layouts
- Optimized images
- Touch-friendly interactions

## 🔍 SEO & Accessibility

- Comprehensive meta tags
- Open Graph and Twitter Card support
- Semantic HTML structure
- Alt text for all images
- Keyboard navigation support

## 🚀 Deployment

### Vercel (Recommended)
1. Connect your repository to Vercel
2. Deploy automatically on push to main branch

### Other Platforms
Build the project:
```bash
npm run build
```

The static files will be generated in the `.next` folder.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License.

## 🙏 Acknowledgments

- Images from [Unsplash](https://unsplash.com)
- Icons and emojis for visual elements
- Next.js team for the excellent framework
- Tailwind CSS for utility-first styling
