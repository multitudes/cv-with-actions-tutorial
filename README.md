# CV with GitHub Actions Tutorial

**Get your professional CV online with a permanent, free URL in minutes.**

Perfect for job seekers who want to:
- Share their CV instantly with a clean, permanent link
- Update their resume anytime and have changes go live automatically
- Never worry about broken links or outdated versions
- Impress recruiters with a professional, always-accessible CV

## Two Ways to Get Started

### Option 1: Auto-Compile LaTeX Resume (Recommended)
If you want to edit your CV in LaTeX and have it automatically compiled and deployed:
1. Use the provided LaTeX template (or bring your own)
2. GitHub Actions automatically compiles your `.tex` files into a PDF
3. PDF gets pushed to GitHub Pages for instant hosting
4. Edit your CV → Push to GitHub → Live in seconds

### Option 2: Simple PDF Upload
Just want to host an existing PDF? Remove the `build-resume.yml` file from the `.github/workflows/` folder.
1. Place your `resume.pdf` in the `docs/` folder
2. Push to your repository
3. Your CV is live with a permanent URL

## Quick Setup Guide

### Step 1: Get Your Own Copy
**Option A: Fork this repository** (recommended for contributing back)
Click the "Fork" button at the top of this page to create your own copy.

**Option B: Create a private repository** (for privacy)
1. Create a new private repository on GitHub
2. Copy all files from this repository to your new private repo
3. This allows you to keep your CV source code private while still having a public GitHub Pages URL

### Step 2: Enable GitHub Pages
1. Go to your repository's **Settings** tab
2. Scroll down to **Pages** in the left sidebar
3. Under **Source**, select **Deploy from a branch**
4. Choose **main** branch and **/ (root)** or **/docs** folder
5. Click **Save**

*Note: GitHub Pages is free for public repositories. Private repos require a GitHub Pro account.*

**Example:** Your CV will be available at: `https://johndoe.github.io/cv-with-actions-tutorial/resume.pdf`

### Step 3: Customize Your CV
- **LaTeX users**: Edit files in the `cv/` folder
- **PDF users**: Replace `docs/resume.pdf` with your own

## Bonus Features

### Create a QR Code
Generate a QR code linking to your CV URL for:
- Business cards
- Conference networking
- Easy mobile sharing

### Apple Wallet Integration
Add your CV QR code to Apple Wallet for instant access at networking events.

## Getting Your Own Copy

### Fork vs. Private Repository
- **Fork this repository** if you want to contribute back or don't mind a public repository
- **Create a private repository** by copying the files if you prefer to keep your CV source private while still having a public GitHub Pages URL

### Example URL
Once set up, your CV will be accessible at a URL like:
`https://johndoe.github.io/cv-with-actions-tutorial/resume.pdf`

## Contributing

This is an open source project. Contributions, ideas, and improvements are welcome! Feel free to:
- Submit issues for bugs or feature requests
- Create pull requests with improvements
- Share your own CV templates
- Suggest better workflows or automation ideas
- Add an "Add to Apple Wallet" button workflow (would require Apple Developer certificates and proper secret management)

## Resources

### LaTeX Template Credit
The included LaTeX resume template is based on the work by [TimmyChan](https://github.com/TimmyChan). Original template: [Data Science Tech Resume Template](https://www.overleaf.com/latex/templates/data-science-tech-resume-template/zcdmpfxrzjhv)

### Some ideas for the Apple Wallet Integration
- [Ionic Enterprise Digital Passes Tutorial](https://github.com/ionic-enterprise/tutorials-digital-passes/tree/main/backend) - Backend implementation guide for creating digital passes
- [PassKit Generator](https://github.com/alexandercerutti/passkit-generator) - Node.js library for generating Apple Wallet passes
- [Ionic Digital Passes Guide](https://ionic.io/docs/tutorials/integrations/digitial-passes/apple-wallet-passes/creating) - Step-by-step tutorial for creating Apple Wallet passes

#### Apple Developer Documentation
- [PassKit Programming Guide (Archived)](https://developer.apple.com/library/archive/documentation/UserExperience/Conceptual/PassKit_PG/index.html#//apple_ref/doc/uid/TP40012195-CH1-SW1) - Comprehensive guide to Apple Wallet pass development
- [Wallet Passes Documentation](https://developer.apple.com/documentation/walletpasses) - Current Apple developer documentation for Wallet passes

## License

This project is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License - see the [LICENSE](LICENSE) file for details.  
