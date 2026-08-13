# CleverBuy Legal Documentation

This repository contains the legal documentation and website for the CleverBuy Android application.

## Structure

```
cleverbuy/
├── _config.yml              # Jekyll configuration
├── index.md                 # Homepage
├── docs/
│   ├── terms_of_service.md  # Terms of Service
│   └── privacy_policy.md    # Privacy Policy
├── assets/
│   └── style.css           # Custom styles
├── README.md               # This file
└── .gitignore              # Git ignore file
```

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/AndreiDzehtsiarou/cleverbuy.git
cd cleverbuy
```

### 2. Install Jekyll (Optional for Local Development)

If you want to test the website locally:

```bash
# Install Ruby (if not already installed)
# Then install Jekyll:
gem install jekyll bundler

# Navigate to the repo directory and run:
jekyll serve
```

The site will be available at `http://localhost:4000/cleverbuy/`

### 3. Enable GitHub Pages

1. Go to your repository settings
2. Scroll to "GitHub Pages" section
3. Select "Deploy from a branch"
4. Select `main` branch and `/root` folder
5. Click Save

Your site will be live at: `https://AndreiDzehtsiarou.github.io/cleverbuy/`

## File Descriptions

- **_config.yml** - Configuration file for Jekyll. Contains site title, description, theme, and plugins
- **index.md** - Homepage of the website
- **docs/terms_of_service.md** - Legal terms for using the CleverBuy application
- **docs/privacy_policy.md** - Privacy policy explaining how user data is handled
- **assets/style.css** - Custom CSS styling for the website
- **.gitignore** - Specifies files to ignore in Git

## Using for Google Play Store

These documents are required for Google Play Store submission. You can provide the following URLs:

```
Terms of Service:
https://AndreiDzehtsiarou.github.io/cleverbuy/docs/terms_of_service.html

Privacy Policy:
https://AndreiDzehtsiarou.github.io/cleverbuy/docs/privacy_policy.html
```

## Editing Content

### Update Terms of Service

Edit `docs/terms_of_service.md` with any changes to your terms.

### Update Privacy Policy

Edit `docs/privacy_policy.md` with any changes to your privacy policy.

### Update Homepage

Edit `index.md` to modify the homepage content.

## Committing Changes

After making changes:

```bash
git add .
git commit -m "Update: describe your changes"
git push origin main
```

Changes will be live on GitHub Pages within 1-2 minutes.

## Contact

For questions or support:
- **Email:** andrej.dzehtsiarou@gmail.com
- **GitHub:** [@AndreiDzehtsiarou](https://github.com/AndreiDzehtsiarou)

## License

© 2024 Andrei Dzehtsiarou. All rights reserved.
