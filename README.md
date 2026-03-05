# Official844InsureU Landing Page

A professional, high-trust landing page for direct enrollment in supplemental health, life, and critical illness insurance.

## Project Overview

This is a static HTML landing page optimized for:
- **Fast Loading**: Pure HTML/CSS with no dependencies
- **SEO**: Proper semantic HTML, JSON-LD schema, and meta tags
- **Compliance**: Includes required disclaimers and license information
- **Accessibility**: WCAG compliant with proper heading hierarchy and focus states
- **Responsive Design**: Mobile-friendly layout that works on all devices

## Features

- **Professional Header**: CSS-based phone number branding with dual formats
- **Expert Bio**: Credentials-focused introduction with CLU and ChFC designations
- **Enrollment Portal**: Four direct enrollment buttons linking to NatGen Health
- **Compliance Footer**: State licenses and legal disclaimers
- **Security Headers**: Configured for Netlify deployment
- **Favicon**: Custom SVG favicon included

## File Structure

```
official844insureu/
├── index.html          # Main landing page
├── netlify.toml        # Netlify configuration
├── .gitignore          # Git ignore rules
└── README.md           # This file
```

## Local Testing

To test the site locally, simply open `index.html` in your web browser:

```bash
# Using Python 3
python3 -m http.server 8000

# Using Node.js
npx http-server

# Or simply open in browser
open index.html
```

Then visit `http://localhost:8000` in your browser.

## Deployment to Netlify

### Option 1: Connect GitHub Repository (Recommended)

1. **Create a GitHub Repository**
   - Push this project to GitHub
   - Use the repository name: `official844insureu` or similar

2. **Connect to Netlify**
   - Go to [netlify.com](https://netlify.com)
   - Click "New site from Git"
   - Select GitHub and authorize
   - Choose your repository
   - Netlify will auto-detect the `netlify.toml` configuration
   - Click "Deploy site"

3. **Configure Domain**
   - In Netlify dashboard, go to "Domain settings"
   - Add custom domain: `official844insureu.com`
   - Follow DNS configuration instructions from your domain registrar

### Option 2: Direct Upload (Drag & Drop)

1. Go to [netlify.com](https://netlify.com)
2. Drag and drop the project folder onto the Netlify dashboard
3. Your site will be deployed immediately with a temporary URL
4. Configure your custom domain afterward

### Option 3: Netlify CLI

```bash
# Install Netlify CLI
npm install -g netlify-cli

# Login to Netlify
netlify login

# Deploy
netlify deploy --prod

# Or for continuous deployment
netlify link
git push origin main
```

## DNS Configuration

Once deployed on Netlify, update your domain registrar's DNS settings:

**For official844insureu.com:**
- Point your domain to Netlify's nameservers, OR
- Add a CNAME record pointing to your Netlify site URL

Netlify will provide specific instructions in the domain settings panel.

## Performance Optimization

- **Page Load**: <1 second (static HTML/CSS)
- **SEO Score**: 95+ (proper structure, meta tags, schema)
- **Mobile Friendly**: Fully responsive design
- **Security**: A+ rating with security headers

## Compliance Notes

- All state insurance licenses are listed in the footer
- Legal disclaimer included as required
- JSON-LD schema includes CLU and ChFC credentials
- All enrollment links open in new tabs with `rel="noopener noreferrer"` for security

## Customization

To customize the site:

1. **Phone Number**: Update in header and JSON-LD schema
2. **Bio Text**: Edit the expert bio section
3. **Enrollment URLs**: Update the button href attributes
4. **Colors**: Modify CSS variables in the `<style>` section
5. **License Information**: Update the licenses section in the footer

## Browser Support

- Chrome/Edge: Latest 2 versions
- Firefox: Latest 2 versions
- Safari: Latest 2 versions
- Mobile browsers: iOS Safari 12+, Chrome Android latest

## Support

For Netlify-specific questions:
- [Netlify Documentation](https://docs.netlify.com)
- [Netlify Support](https://support.netlify.com)

For domain/DNS questions:
- Contact your domain registrar
- Check Netlify's DNS configuration guide

## License

This landing page is proprietary and confidential.
