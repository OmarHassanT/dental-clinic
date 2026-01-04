# Dental Clinic Landing Page

A modern, responsive landing page for a dental clinic website built with HTML, CSS, and JavaScript.

## Features

- **Responsive Design**: Fully responsive layout that works on all devices (desktop, tablet, mobile)
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Smooth scrolling, mobile menu, scroll-to-top button
- **Multiple Sections**:
  - Hero section with call-to-action
  - Services showcase
  - About section
  - Team members
  - Patient testimonials
  - Appointment booking form
  - Contact information with map
  - Footer with newsletter signup

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript (ES6+)
- Font Awesome Icons
- Google Fonts (Poppins)

## Structure

```
dental-clinic/
├── index.html          # Main HTML file
├── css/
│   └── style.css      # Stylesheet
├── js/
│   └── script.js      # JavaScript functionality
├── images/            # Image assets folder
└── README.md          # Documentation
```

## Sections Overview

### 1. Header & Navigation
- Sticky navigation bar
- Mobile-responsive hamburger menu
- Smooth scroll to sections
- Active section highlighting

### 2. Hero Section
- Eye-catching background with overlay
- Clear call-to-action buttons
- Key features display (24/7 Emergency, Expert Dentists, Award Winning)

### 3. Services
- 6 dental service cards:
  - General Dentistry
  - Cosmetic Dentistry
  - Dental Implants
  - Orthodontics
  - Root Canal
  - Pediatric Dentistry

### 4. About Section
- Information about the clinic
- Experience badge
- Key features with icons
- Professional clinic image

### 5. Team Section
- 3 team member cards with:
  - Professional photos
  - Name and specialization
  - Social media links

### 6. Testimonials
- Patient reviews with:
  - 5-star ratings
  - Review text
  - Patient photo and name

### 7. Appointment Section
- Contact information
- Appointment booking form with:
  - Name, email, phone
  - Preferred date
  - Service selection
  - Additional message

### 8. Contact
- Embedded Google Map

### 9. Footer
- About information
- Quick links
- Services list
- Newsletter subscription
- Social media links

## Features & Functionality

### JavaScript Features
- **Smooth Scrolling**: Navigate smoothly between sections
- **Mobile Menu**: Hamburger menu for mobile devices
- **Active Navigation**: Highlights current section in navigation
- **Scroll to Top**: Button appears when scrolling down
- **Form Validation**: Client-side validation for appointment form
- **Notifications**: Success/error messages for form submissions
- **Animate on Scroll**: Cards fade in when scrolling into view
- **Date Validation**: Prevents booking appointments in the past

### CSS Features
- **CSS Variables**: Easy customization of colors and styles
- **Flexbox & Grid**: Modern layout techniques
- **Animations**: Smooth transitions and hover effects
- **Responsive Breakpoints**:
  - Desktop: 992px and above
  - Tablet: 768px - 991px
  - Mobile: Below 768px

## Color Scheme

- Primary Color: #00b4d8 (Bright Blue)
- Secondary Color: #0077b6 (Deep Blue)
- Accent Color: #48cae4 (Light Blue)
- Dark Color: #03045e (Navy Blue)
- Light Color: #caf0f8 (Pale Blue)

## How to Use

1. **Open the website**: Simply open `index.html` in a web browser
2. **Navigate**: Use the navigation menu to explore different sections
3. **Book an Appointment**: Fill out the appointment form
4. **Subscribe**: Enter your email in the newsletter form

## Customization

### Change Colors
Edit the CSS variables in `css/style.css`:
```css
:root {
    --primary-color: #00b4d8;
    --secondary-color: #0077b6;
    /* ... other colors */
}
```

### Add Images
Replace the placeholder image URLs in `index.html` with your own images:
- Team member photos
- Patient testimonials
- About section image
- Update the hero background image URL in `css/style.css`

### Modify Content
Update text content directly in `index.html`:
- Service descriptions
- Team member information
- Testimonials
- Contact details

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Future Enhancements

- Backend integration for form submissions
- Admin panel for managing content
- Blog section
- Online payment integration
- Live chat support
- Multiple language support
- Gallery section

## License

This project is open source and available for personal and commercial use.

## Contact

For questions or support, please contact:
- Email: info@dentalcare.com
- Phone: +1 (555) 123-4567

---

Built with care for dental professionals who care about their patients.
