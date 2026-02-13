# Own Your Web - Sign Up

Lead capture landing page for Own Your Web services.

## Setup

1. **Create a Formspree account** at [formspree.io](https://formspree.io)
2. **Create a new form** targeting `ownyourwebsystems@agentmail.to`
3. **Copy your form ID** (looks like `mxyzabc`)
4. **Update index.html**: Replace `YOUR_FORM_ID` with your actual form ID
5. **Deploy to GitHub Pages** (see below)

## Local Development

```bash
# Open in browser
open index.html
```

## Deployment

### GitHub Pages

```bash
# Initialize repo
git init
git add .
git commit -m "Initial commit"

# Create repo on GitHub first, then:
git remote add origin https://github.com/innergclaw/ownyourweb-signup.git
git branch -M main
git push -u origin main

# Enable GitHub Pages:
# Go to repo → Settings → Pages
# Source: Deploy from branch → main → Save
```

Your site will be available at: `https://innergclaw.github.io/ownyourweb-signup/`

## Formspree Integration

Form submissions will be forwarded to:
**ownyourwebsystems@agentmail.to**

InnerGClaw monitors this inbox and will alert you when new leads arrive.

## Design

- Terminal-inspired aesthetic (black + green)
- Responsive design
- Mobile-first approach
- No external dependencies

---

**Own Your Web** — Your website. Your server. Your control.
