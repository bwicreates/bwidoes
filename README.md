# Booth & Witherspoon Investments — Static Website (HTML + Tailwind)

This repository was updated by an automated scaffold. It contains a lightweight static site scaffold for a business development / real estate / marketing website. It uses plain HTML with Tailwind CSS (via CDN) and is ready to publish on GitHub Pages.

Pages:
- index.html — Home
- about.html — About
- services.html — Services
- properties.html — Properties / listings
- contact.html — Contact (mailto form)

How to publish on GitHub Pages (free)
1. In the repository settings on GitHub go to Settings -> Pages (or Settings -> Code and automation -> Pages).
2. Source: choose branch `main` and folder `/ (root)` then Save.
3. After a minute, your site will be available at `https://bwicreates.github.io/bwidoes/`

Edit content
- Replace placeholder text and images in each HTML file.
- To add or replace images, put files in `assets/images/` and update the <img src=""> paths.
- To change the accent color, edit the color value in the top of each HTML file (tailwind.config `primary`).

Contact form options
- Current contact form uses a mailto action (opens user's email client). To use Formspree or Netlify Forms (no email client required), tell me and I will integrate it.

Next steps I can do (tell me which):
- Replace placeholder images and text with your content.
- Integrate Formspree or Netlify Forms for hosted form submissions.
- Connect a custom domain and create a CNAME file.
- Open a Pull Request instead of pushing straight to main (if preferred).
