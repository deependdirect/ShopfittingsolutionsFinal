# ShopFit Pro - Shop Fitting Solutions Website

A professional, modern website for a shop fitting business targeting Australian retail clients.

## Features

- **Responsive Design** - Works perfectly on desktop, tablet, and mobile
- **Smooth Animations** - Scroll reveal effects and hover animations
- **Portfolio Gallery** - Filterable project showcase
- **Contact Form** - Full-featured quote request form
- **SEO Optimized** - Meta tags and structured content
- **Fast Loading** - Optimized images and minimal dependencies

## Sections

1. **Hero** - Eye-catching banner with stats and CTAs
2. **Services** - 6 core service offerings
3. **Industries** - Specialised solutions for different retail sectors
4. **Process** - 5-step workflow explanation
5. **Portfolio** - Filterable project showcase
6. **Testimonials** - Client reviews and trust stats
7. **CTA** - Strong call-to-action with contact info
8. **Contact Form** - Detailed quote request form
9. **Footer** - Navigation, services, and contact details

## Deployment to Vercel

### Option 1: Direct Upload (Easiest)

1. Go to [vercel.com](https://vercel.com) and sign up/login
2. Click "Add New Project"
3. Select "Import Git Repository" or drag & drop your folder
4. Framework Preset: Select "Other"
5. Click "Deploy"

### Option 2: GitHub + Vercel (Recommended)

1. Create a GitHub repository
2. Push this code to the repository
3. Connect the repo to Vercel
4. Deploy automatically on every push

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/shopfit-pro.git
git push -u origin main
```

### Option 3: Vercel CLI

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel
```

## Customization

### Colors
Edit the Tailwind config in the `<script>` tag in `index.html`:

```javascript
colors: {
    primary: {
        500: '#0ea5e9', // Your brand color
    }
}
```

### Content
- Update business name, phone, email throughout the HTML
- Replace placeholder images with your actual project photos
- Update testimonials with real client feedback
- Modify services and industries as needed

### Images
Replace Unsplash placeholder URLs with your own images:

```html
<img src="YOUR_IMAGE_URL" alt="Description">
```

## Technologies Used

- HTML5
- Tailwind CSS (CDN)
- Lucide Icons
- Vanilla JavaScript

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This template is provided for commercial use. Customize it for your business needs.

## Support

For questions or customizations, contact your web developer.
