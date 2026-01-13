# JES Educational Consultants Website

A modern, colorful, and animated website for JES Educational Consultants Ltd, built with HTML and Tailwind CSS.

## 🎨 Features

### Pages
- **Home** (`index.html`) - Main landing page with hero, stats, services, and testimonials
- **About** (`about.html`) - Company information, mission, and vision
- **Services** (`services.html`) - Detailed service offerings
- **Destinations** (`destinations.html`) - Study abroad destinations (Australia, New Zealand, USA, UK, Canada, UAE)
- **Contact** (`contact.html`) - Contact form and information

### 🌟 Animations & Transitions

#### Hero Sections
- **Gradient Animation**: Animated gradient backgrounds that shift colors smoothly
- **Floating Elements**: Multiple floating circular shapes with different animation delays
- **Slide Animations**: Text elements slide in from different directions
- **Word Hover Effects**: Individual words in headings can be hovered for scale effects

#### Service Cards (Homepage & Services Page)
- **Lift & Scale Effect**: Cards lift up and scale on hover
- **Icon Rotation**: Icons rotate and scale when card is hovered
- **Text Color Transitions**: Headings change color smoothly on hover
- **Shadow Effects**: Dynamic shadow growth on hover

#### Stats Section (Homepage)
- **Counter Animation**: Numbers count up from 0 when section comes into view
- **Hover Effects**: Stats scale up and rotate slightly on hover
- **Interactive**: Responds to scroll with Intersection Observer

#### Testimonial Cards
- **Card Hover**: Lift effect with enhanced shadows
- **Star Interactions**: Individual stars can be hovered for rotation
- **Text Color Shifts**: Text colors change on card hover

#### Destination Cards
- **Scale & Rotate**: Cards scale and rotate slightly on hover
- **Button Animations**: Call-to-action buttons have scale effects
- **List Item Animations**: Icons and text have micro-interactions

#### Contact Page
- **Info Card Animations**: Contact information cards lift and rotate on hover
- **Icon Animations**: Icons scale and rotate on card hover
- **Form Input Focus**: Input fields scale slightly when focused
- **Gradient Backgrounds**: Animated gradient shifts on info cards

### 🎭 Animation Types

1. **Slide Animations**
   - `slide-up`: Elements slide up from below
   - `slide-down`: Elements slide down from above
   - `slide-left`: Elements slide from right to left
   - `slide-right`: Elements slide from left to right

2. **Float Animation**
   - Continuous up and down floating motion
   - Used for background decorative elements

3. **Scale Animations**
   - `scale-in`: Elements scale from 80% to 100%
   - Hover scales on cards and buttons

4. **Rotation Effects**
   - Icons rotate on hover
   - Cards rotate slightly for dynamic feel

5. **Glow Effect**
   - Pulsing glow on CTA buttons
   - Creates attention-grabbing effect

6. **Gradient Shift**
   - Background gradients animate smoothly
   - 8-second infinite loop

### 🎨 Color Scheme

- **Primary**: Blue (#3B82F6)
- **Secondary**: Purple (#8B5CF6)
- **Accent**: Amber (#F59E0B)
- **Success**: Green (#10B981)
- **Gradients**: Multiple vibrant gradient combinations (blue→purple→pink, green→blue, etc.)

## 🚀 Technical Details

### Technologies Used
- **HTML5**: Semantic markup
- **Tailwind CSS**: Utility-first CSS framework (via CDN)
- **Font Awesome**: Icon library
- **Vanilla JavaScript**: For animations and interactions

### Key JavaScript Features
- Intersection Observer for scroll-triggered animations
- Counter animation for statistics
- Mobile menu toggle
- Form validation and submission handling

### Performance
- No build process required
- All assets loaded via CDN
- Optimized animations with CSS transforms
- Hardware-accelerated animations

## 📱 Responsive Design

- **Mobile-first approach**
- Responsive navigation with hamburger menu
- Grid layouts that adapt to screen sizes
- Touch-friendly hover effects
- Optimized typography for all devices

## 🎯 Animation Performance Tips

All animations use:
- CSS transforms (translate, scale, rotate) for smooth 60fps performance
- Hardware acceleration
- Cubic-bezier timing functions for natural motion
- Reasonable durations (300-500ms for most interactions)

## 🔧 Customization

To modify animations:
1. Edit the `tailwind.config` in the `<script>` tag
2. Adjust keyframes in the `<style>` section
3. Modify timing functions and durations as needed

## 📞 Contact Information

**Note**: Update the contact information placeholders in all pages:
- Phone numbers: Replace `+234 XXX XXX XXXX`
- Email addresses: Currently set to `info@jeseducational.com`
- Physical address: Update with actual address

## 🎓 Usage

Simply open `index.html` in any modern web browser. No installation or build process required!

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

---

**Built with ❤️ for JES Educational Consultants Ltd**
