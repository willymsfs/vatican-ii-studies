# GitHub Pages Deployment Guide for Vatican II Website

This guide provides step-by-step instructions for deploying your Vatican II website to GitHub Pages.

## Prerequisites

- A GitHub account
- Basic familiarity with GitHub (or willingness to learn)
- All website files ready for deployment

## Method 1: Web Interface Deployment (Recommended for Beginners)

### Step 1: Create a New Repository

1. **Log in to GitHub** at [github.com](https://github.com)
2. **Click the "+" icon** in the top right corner
3. **Select "New repository"**
4. **Configure your repository**:
   - Repository name: `vatican-ii-studies` (or your preferred name)
   - Description: "Vatican II: The Battle for Meaning - Digital Study Resource"
   - Make it **Public** (required for free GitHub Pages)
   - Check "Add a README file"
   - Click "Create repository"

### Step 2: Upload Your Website Files

1. **In your new repository**, click "uploading an existing file"
2. **Drag and drop** all files from your `vatican-ii-website` folder
   - Include: `index.html`, `css/`, `js/`, all `.html` files
   - The folder structure should be maintained
3. **Scroll down** to the commit section
4. **Add a commit message**: "Initial website upload"
5. **Click "Commit changes"**

### Step 3: Enable GitHub Pages

1. **Go to your repository's Settings** (tab at the top)
2. **Scroll down** to the "Pages" section in the left sidebar
3. **Under "Source"**, select "Deploy from a branch"
4. **Choose "main" branch** and "/ (root)" folder
5. **Click "Save"**

### Step 4: Access Your Website

1. **GitHub will show you the URL** where your site is published
2. **It will be**: `https://[your-username].github.io/[repository-name]`
3. **Wait 5-10 minutes** for the initial deployment
4. **Visit your URL** to see your live website!

## Method 2: GitHub Desktop (For Regular Updates)

### Step 1: Install GitHub Desktop

1. **Download** from [desktop.github.com](https://desktop.github.com)
2. **Install and sign in** with your GitHub account

### Step 2: Clone Your Repository

1. **In GitHub Desktop**, click "Clone a repository from the Internet"
2. **Select your repository** from the list
3. **Choose a local folder** where you want to work
4. **Click "Clone"**

### Step 3: Add Your Website Files

1. **Copy all website files** into the cloned repository folder
2. **In GitHub Desktop**, you'll see all the new files listed
3. **Add a commit message**: "Add Vatican II website files"
4. **Click "Commit to main"**
5. **Click "Push origin"** to upload to GitHub

### Step 4: Enable GitHub Pages

Follow Step 3 from Method 1 above.

## Method 3: Using docs/ Folder (Alternative Structure)

If you prefer to keep your website files in a `docs/` folder:

1. **Create a `docs` folder** in your repository
2. **Move all website files** into the `docs` folder
3. **In GitHub Pages settings**, choose "/docs" folder instead of "/ (root)"

## Updating Your Website

### Using Web Interface:
1. **Go to your repository**
2. **Navigate to the file** you want to edit
3. **Click the pencil icon** to edit
4. **Make your changes**
5. **Commit the changes**

### Using GitHub Desktop:
1. **Make changes** to files in your local folder
2. **Open GitHub Desktop**
3. **Review changes** in the left panel
4. **Add a commit message**
5. **Click "Commit to main"**
6. **Click "Push origin"**

## Custom Domain (Optional)

If you want to use your own domain name:

1. **In your repository**, create a file named `CNAME`
2. **Add your domain** (e.g., `vatican-ii-studies.com`) as the only content
3. **Configure your domain's DNS** to point to GitHub Pages
4. **In GitHub Pages settings**, add your custom domain

## Troubleshooting

### Website Not Loading
- **Wait 10-15 minutes** after enabling GitHub Pages
- **Check that your repository is public**
- **Ensure `index.html` is in the root directory** (or docs/ if using that option)

### Styling Not Working
- **Check file paths** in your HTML files
- **Ensure CSS and JS files** are uploaded correctly
- **Verify folder structure** matches your HTML references

### 404 Errors on Navigation
- **Check that all linked HTML files** exist in the repository
- **Verify file names** match exactly (case-sensitive)
- **Ensure relative paths** are correct

## Security and Privacy

- **Repository must be public** for free GitHub Pages
- **Don't include sensitive information** in your files
- **All content will be publicly accessible**

## Best Practices

1. **Test locally first** before uploading
2. **Use descriptive commit messages**
3. **Keep file names simple** (no spaces, use hyphens)
4. **Maintain consistent folder structure**
5. **Regular backups** of your content

## Support Resources

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [GitHub Desktop Help](https://docs.github.com/en/desktop)
- [HTML/CSS Validation](https://validator.w3.org/)

---

**Your Vatican II website will be live and accessible to anyone with the URL once deployed!**

