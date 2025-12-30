# Princess James Portfolio Website

A professional portfolio website for Princess James, Data Analyst, showcasing skills, projects, certifications, and contact information.

## 🚀 Features

- **Responsive Design** - Works perfectly on desktop, tablet, and mobile devices
- **Smooth Scrolling** - Seamless navigation between sections
- **Interactive Sidebar** - Easy-to-use navigation menu
- **Project Showcase** - Display of data analysis projects with links
- **Skills Section** - Highlights technical and soft skills
- **Contact Information** - Easy ways to get in touch
- **Social Media Integration** - Links to LinkedIn, Medium, GitHub, and more

## 📁 File Structure

```
portfolio-website/
├── index.html          # Main HTML file
├── style.css           # Stylesheet
├── script.js           # JavaScript for interactivity
├── images/             # Image folder
│   ├── profile.jpg     # Profile photo
│   ├── certificate.jpg # Afriment certificate
│   ├── project1.jpg    # Sales & Customer Insights project image
│   └── project2.jpg    # Workforce Analytics project image
└── README.md          # This file
```

## 🌐 Deploying to GitHub Pages

Follow these steps to deploy your portfolio website to GitHub Pages:

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and log in
2. Click the "+" icon in the top right and select "New repository"
3. Name your repository: `your-username.github.io` (replace `your-username` with your actual GitHub username)
   - Example: `Princess-Annie.github.io`
4. Make sure the repository is **Public**
5. Click "Create repository"

### Step 2: Upload Your Files

**Option A: Using GitHub Website (Easier)**

1. In your new repository, click "uploading an existing file"
2. Drag and drop ALL files from your portfolio-website folder:
   - index.html
   - style.css
   - script.js
   - The entire `images` folder with all images inside
3. Scroll down and click "Commit changes"

**Option B: Using Git Command Line**

```bash
# Navigate to your portfolio-website folder
cd path/to/portfolio-website

# Initialize git (if not already done)
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit - Portfolio website"

# Add your GitHub repository as remote
git remote add origin https://github.com/Princess-Annie/Princess-Annie.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings" (top menu)
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Under "Branch", select "main" and folder "/ (root)"
6. Click "Save"

### Step 4: Access Your Website

After a few minutes, your website will be live at:
```
https://Princess-Annie.github.io
```

## 🔧 Customization

### Update Resume

When your resume is ready, replace the Resume section in `index.html`:

```html
<!-- Replace this section -->
<section id="resume" class="section resume-section">
    <div class="container">
        <h2 class="section-heading">Resume</h2>
        <div class="resume-content">
            <p class="resume-note">Resume will be updated soon...</p>
            <a href="#contact" class="btn-primary">Contact Me</a>
        </div>
    </div>
</section>

<!-- With your actual resume content or link -->
```

### Add More Projects

To add more projects, copy the project card structure in the Projects section:

```html
<div class="project-card">
    <div class="project-image">
        <img src="images/your-project-image.jpg" alt="Project Name">
    </div>
    <div class="project-content">
        <h3>Your Project Title</h3>
        <p>Project description here...</p>
        <a href="your-project-link" target="_blank" class="btn-secondary">VIEW PROJECT</a>
    </div>
</div>
```

### Update Social Media Links

Edit the social media links in the header section of `index.html`:

```html
<div class="social-links">
    <a href="https://twitter.com/your-handle" target="_blank">...</a>
    <!-- Update with your actual handles -->
</div>
```

### Change Colors

Edit the color scheme in `style.css`:

```css
:root {
    --primary-color: #E87461;  /* Change this to your preferred color */
    --secondary-color: #333;
    /* ... other colors ... */
}
```

## 📱 Responsive Breakpoints

- Desktop: > 992px
- Tablet: 768px - 992px
- Mobile: < 768px

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)
- Font Awesome Icons
- Google Fonts

## 📞 Contact

- **Email**: princessjames563@gmail.com
- **Phone**: +234 902 197 7816
- **Location**: Akwa-Ibom State, Nigeria
- **LinkedIn**: [linkedin.com/in/princessani](https://www.linkedin.com/in/princessani)
- **Medium**: [@princessjames563](https://medium.com/@princessjames563)
- **GitHub**: [Princess-Annie](https://github.com/Princess-Annie)

## 📄 License

© 2025 Princess James. All rights reserved.

---

**Note**: After making any changes to your files, remember to commit and push them to GitHub for the changes to appear on your live website.