# HousePhysio - Mobile Physiotherapy Website

A modern, responsive static website for a mobile physiotherapist who provides in-home therapy services.

## Features

- Clean, responsive design that works on mobile and desktop devices
- Single-page layout with smooth scrolling navigation
- Appointment booking form integrated with Formspree
- Mobile-friendly navigation
- Interactive FAQ section
- Testimonials section
- Service details with visual elements
- Contact information

## Technologies Used

- HTML5
- Tailwind CSS (via CDN)
- Vanilla JavaScript
- Font Awesome icons
- Formspree for form submissions

## Setup Instructions

### 1. Formspree Setup

Before deploying the website, you need to set up Formspree to handle form submissions:

1. Go to [Formspree](https://formspree.io/) and create an account
2. Create a new form
3. Replace the placeholder in the HTML form action attribute (`https://formspree.io/f/your-form-id`) with your actual Formspree endpoint
4. Update the `_next` hidden input value with your actual thank you page URL or remove it to use Formspree's default success page

### 2. Customize Content

- Update the therapist's information, services, and contact details in `index.html`
- Replace placeholder images with actual images
- Customize testimonials with real client feedback

### 3. Deployment Options

#### Option 1: Deploy with Netlify

1. Create a free [Netlify](https://www.netlify.com/) account
2. Click "New site from Git" and connect to your repository
3. Configure build settings (not required for static HTML)
4. Deploy the site

#### Option 2: Deploy with GitHub Pages

1. Push your code to a GitHub repository
2. Go to repository settings > Pages
3. Select the main branch and save
4. Your site will be available at `https://yourusername.github.io/repository-name/`

#### Option 3: Any Static Web Hosting

Upload the files to any static web hosting service like:
- Amazon S3
- Firebase Hosting
- Vercel
- DigitalOcean App Platform

## Customization Tips

### Colors and Branding

To customize the color scheme:
1. Edit the classes in `index.html` to use different Tailwind colors
2. For more extensive customization, create a custom Tailwind configuration

### Adding New Sections

To add new sections:
1. Copy the structure of an existing section
2. Add a new nav link pointing to the new section
3. Update the content as needed

### Image Optimization

For better performance:
1. Compress all images before adding them to the site
2. Use appropriate image dimensions
3. Consider using WebP format with fallbacks

## Browser Compatibility

Tested and works on:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Android Chrome)

## License

Feel free to use and modify this template for your personal or commercial projects.

## Support

For questions or support, please open an issue in the repository or contact the developer. 
