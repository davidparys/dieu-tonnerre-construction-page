# Hôtel-Dieu de Tonnerre - Coming Soon Page

A temporary coming soon landing page for the Hôtel-Dieu de Tonnerre project by Tous au Château.

## Design

The page uses the "tous-au-chateau" theme from the main project's `tailwind.config.ts`:
- **Primary Color**: Golden amber (#e0b768)
- **Background**: Dark blue-gray gradient (#344856, #2f3e4a, #1b2731)
- **Typography**: Playfair Display (headings), Raleway (body)

## Tech Stack

- Plain HTML with Tailwind CSS CDN
- No build process required
- Optimized for Vercel deployment

## Deployment to Vercel

### Option 1: Vercel CLI

```bash
cd hotel-dieu-tonnerre-coming-soon
vercel --prod
```

### Option 2: Vercel Dashboard

1. Go to [vercel.com](https://vercel.com)
2. Click "Add New Project"
3. Import this repository or upload the folder
4. Vercel will automatically detect the static site
5. Deploy!

### Option 3: GitHub Integration

1. Push this folder to a GitHub repository
2. Connect the repository to Vercel
3. Set the root directory to `hotel-dieu-tonnerre-coming-soon`
4. Deploy automatically on push

## Local Development

Simply open `index.html` in a browser, or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000`

## Customization

To modify the content:
- Edit the text directly in `index.html`
- Colors are defined in the `tailwind.config` script tag
- Animations and custom styles are in the `<style>` section

## Features

- ✅ Responsive design
- ✅ Elegant animations
- ✅ Theme-consistent colors
- ✅ SEO-friendly meta tags
- ✅ French language
- ✅ Link to main Tous au Château website
- ✅ Contact email included
