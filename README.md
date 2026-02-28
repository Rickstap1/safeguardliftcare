# Setup and Deployment Instructions for GitHub Pages

## Prerequisites
Make sure you have the following:
- A GitHub account
- Node.js and npm installed
- Basic understanding of Git and version control

## 1. Setting Up Your Repository
1. Go to [GitHub](https://github.com/) and create a new repository named `safeguardliftcare`.
2. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/Rickstap1/safeguardliftcare.git
   ```
3. Navigate into your repository:
   ```bash
   cd safeguardliftcare
   ```

## 2. Configuring for GitHub Pages
1. Create a new branch named `gh-pages` (this will host your website):  
   ```bash
   git checkout -b gh-pages
   ```
2. Commit your HTML, CSS, and JS files to the `gh-pages` branch.
3. Push your changes:
   ```bash
   git push origin gh-pages
   ```
4. Go to your repository settings on GitHub, scroll down to the "GitHub Pages" section, and select `gh-pages` as the source.

## 3. Configuring the Contact Form with Formspree
1. Go to [Formspree](https://formspree.io/) and create an account.
2. Set up a new form following the instructions on Formspree. You'll get a unique endpoint URL for your form.
3. Update your contact form HTML to include the Formspree endpoint. Example:
   ```html
   <form action="https://formspree.io/f/YOUR_ENDPOINT" method="POST">
       <input type="text" name="name" placeholder="Your Name" required>
       <input type="email" name="email" placeholder="Your Email" required>
       <textarea name="message" placeholder="Your Message"></textarea>
       <button type="submit">Send</button>
   </form>
   ```

## 4. Publishing Your Site
1. Once you have your `gh-pages` branch pushed, your site will be live at `https://Rickstap1.github.io/safeguardliftcare/`. 
2. Check your site and make sure everything is working correctly.

## Additional Notes
- Make sure to update your repository and push changes as needed.
- Check Formspree for any submissions directly from their dashboard.

---

This README was last updated on 2026-02-28.