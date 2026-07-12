# SADEEPA-TECH-landing-page
A modern, responsive, and interactive landing page designed for the **SADEEPA TECH** YouTube channel. This single-page website acts as a central hub for your content, displaying dynamic video feeds, live subscriber counts, social media links, and structured channel information.

- **Dynamic Video Feed**: Automatically fetches and renders the latest videos from your YouTube channel using the YouTube RSS feed (via the RSS2JSON API) with a fallback mechanism.
- **Live Subscriber Count**: Integrated embedding from SocialCounts to preview channel growth in real-time.
- **Glassmorphic UI Design**: Features a premium dark-themed interface built with Tailwind CSS, custom glow effects, interactive hover states, and smooth animations.
- **Interactive Popup**: A subtle call-to-action slide-in popup to encourage new visitors to subscribe.
- **Responsive Layout**: Designed to work across different screen sizes, from mobile phones to desktop monitors, with a toggleable navigation drawer for mobile screens.
- **Optimized Performance**: Lazy-loading for images and iframes, reduced-motion media query support for accessibility, and clean vanilla JavaScript.

## Technologies Used

- **HTML5 & CSS3**
- **Tailwind CSS** (via CDN for styling and layout)
- **Vanilla JavaScript** (for dynamic rendering, fetch requests, scroll animations, and interactive elements)
- **Google API platform.js** (for the official YouTube subscribe widget)
- **RSS2JSON API** (to convert the YouTube XML feed into a JSON object)

## Getting Started

To run this project locally or host it online, follow these steps:

### Prerequisites

You only need a web browser. No compilation or server setup is required.

### Local Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/sadeepa-tech-landing-page.git
   ```
2. **Navigate to the directory:**
   ```bash
   cd sadeepa-tech-landing-page
   ```
3. **Place your assets:**
   Make sure you have the following image files in the root folder (or update the paths in the HTML file):
   - `sadeepa-tech-logo.png` (Logo icon)
   - `sadeepa-tech-banner.png` (Horizontal channel banner background)

4. **Open the page:**
   Double-click the `index.html` file to open it in your default web browser.

## Customization Guide

If you wish to use this template for another YouTube channel, you can make the following updates in `index.html`:

1. **Update Channel IDs & Info:**
   Find the JavaScript constants near the bottom of the file and replace the channel ID:
   ```javascript
   const channelId = 'YOUR_YOUTUBE_CHANNEL_ID'; // Replace with your actual channel ID
   ```

2. **Update the YouTube Subscribe Button:**
   Find the HTML element for the official subscribe button and change the `data-channelid` attribute:
   ```html
   <div class="g-ytsubscribe" data-channelid="YOUR_YOUTUBE_CHANNEL_ID" data-layout="full" data-count="default"></div>
   ```

3. **Update Social Media and Contact Links:**
   Modify the anchor tags (`<a>`) in the `#contact` section and the footer to point to your respective GitHub, LinkedIn, Telegram, WhatsApp, and email addresses.

4. **SEO & Metadata:**
   Update the `<meta>` descriptions, `<title>`, and keywords in the `<head>` section to match your brand's niche.

## Deployment

This website is ready for static deployment. You can easily host it for free using:
- **GitHub Pages**: Go to your repository settings -> Pages -> Deploy from a branch (select `main` or `master`).
- **Vercel**: Import your repository and deploy.
- **Netlify**: Drag and drop the folder into the Netlify dashboard.

## License

This project is open-source and available under the [MIT License](LICENSE). Feel free to modify and use it for your own personal or commercial projects.
```
