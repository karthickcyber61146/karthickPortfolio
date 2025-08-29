# Portfolio Website

A professional portfolio website showcasing expertise in Networking, Cloud Computing, Cybersecurity, and Python Development.

## Features

- Responsive design for all devices
- Project showcase with filtering capability
- Skills and certifications display
- Professional background information
- Contact section

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Font Awesome for icons
- Google Fonts
 
## Deployment to GitHub Pages

Follow these steps to deploy this portfolio to GitHub Pages:

1. **Create a GitHub Repository**
   - Sign in to your GitHub account
   - Click the '+' icon in the top right and select 'New repository'
   - Name your repository (e.g., 'portfolio' or 'username.github.io')
   - Make it public
   - Click 'Create repository'

2. **Push Your Code to GitHub**
   - Open a terminal/command prompt
   - Navigate to your project folder
   - Initialize Git (if not already done):
     ```
     git init
     ```
   - Add all files to staging:
     ```
     git add .
     ```
   - Commit the files:
     ```
     git commit -m "Initial commit"
     ```
   - Add your GitHub repository as remote:
     ```
     git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME.git
     ```
   - Push to GitHub:
     ```
     git push -u origin main
     ```

3. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Click on 'Settings'
   - Scroll down to the 'GitHub Pages' section
   - Under 'Source', select 'GitHub Actions'
   - The GitHub workflow will automatically deploy your site

4. **Access Your Website**
   - Your site will be published at `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY-NAME/`
   - If you used the username.github.io format for your repository, it will be available at `https://YOUR-USERNAME.github.io/`

## Local Development

To run this website locally:

```
python -m http.server 8000
```

Then open your browser to `http://localhost:8000`

## Custom Domain (Optional)

To use a custom domain with your GitHub Pages site:

1. Purchase a domain from a domain registrar
2. In your repository, edit the CNAME file to contain only your domain name (e.g., `portfolio.example.com`)
3. Configure your domain's DNS settings according to GitHub's documentation:
   - Add an A record pointing to GitHub Pages IP addresses
   - Add a CNAME record for the www subdomain
4. In your repository settings, add your custom domain in the GitHub Pages section
5. Check the "Enforce HTTPS" option for added security