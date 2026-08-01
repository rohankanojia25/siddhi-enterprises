# Siddhi Enterprises

The official website for Siddhi Enterprises, a computerized embroidery and hand printing job work unit based in Shanti Mohalla, Gandhi Nagar, Delhi. The business runs high-speed 12-head embroidery machines and takes on bulk job work for sarees, suits, kurtis, lehengas, denim, uniforms, logos, and hand printing, serving wholesalers, boutiques, exporters, and garment manufacturers across Delhi.

**Live at:** https://siddhi-enterprises.vercel.app/

## About this project

This is a small, fast marketing site built to give the business a professional presence online and to help local buyers find it through Google search and Google Maps. The goal was simple: a page that loads instantly, works well on a phone (most buyers browse on mobile), and clearly tells a wholesaler what we do and how to reach us, with a strong push toward a call or WhatsApp message, since that is how orders actually start in this trade.

The design takes its cue from the craft itself. The whole page is styled to feel like embroidery on cloth: a woven linen background, a headline treated like stitched thread, and running-stitch detailing in gold throughout. The idea was to let the site show the work rather than just describe it.

## How it's built

It is a single static HTML file with the CSS and JavaScript inline, no frameworks and no build step. That was a deliberate choice. A plain static page loads faster than a framework-based one, is read cleanly by Google on the first pass (which helps a local business rank), and is simple to host for free. The only JavaScript is a small scroll animation that fades sections in.

The site is search-optimized out of the box: page title and description, keywords, social-share (Open Graph) tags, and LocalBusiness structured data so Google understands the business type, location, hours, and services. A `sitemap.xml` and `robots.txt` are included for search engines.

## Files

- `index.html` — the complete website
- `favicon.svg` — the browser-tab icon
- `robots.txt` — search engine crawl rules
- `sitemap.xml` — page map for search engines

## Tech

Plain HTML, CSS, and vanilla JavaScript. Hosted on Vercel.
