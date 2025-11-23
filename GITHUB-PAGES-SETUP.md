# GitHub Pages Setup Instructions

This repository is configured for GitHub Pages deployment.

## Setup Steps

1. **Go to repository settings**:
   - Navigate to https://github.com/vishalsachdev/ai-taskforce/settings/pages

2. **Configure GitHub Pages**:
   - Source: Deploy from a branch
   - Branch: `main`
   - Folder: `/ (root)`
   - Click "Save"

3. **Wait for deployment** (2-3 minutes):
   - GitHub Actions will automatically build and deploy the site
   - Check the "Actions" tab to monitor progress

4. **Access the site**:
   - URL: https://vishalsachdev.github.io/ai-taskforce/

## Site Configuration

The site uses:
- **Jekyll**: Static site generator (native GitHub Pages support)
- **Theme**: jekyll-theme-cayman (clean, documentation-focused)
- **Custom CSS**: `assets/css/style.scss` for enhanced styling

## File Structure

```
ai-taskforce/
├── _config.yml           # Jekyll configuration
├── index.md              # Homepage
├── agents/
│   ├── index.md          # Agents overview page
│   ├── agent-alpha-institutional.md
│   ├── agent-beta-stakeholders.md
│   ├── agent-gamma-peer-analysis.md
│   ├── agent-delta-curriculum.md
│   ├── agent-epsilon-ethics.md
│   └── agent-zeta-administration.md
├── research/
│   └── TASK-FORCE-SYNTHESIS.md
├── RESEARCH-METHODOLOGY-ARTICLE.md
├── PROVOST-CHARGE.md
└── assets/
    └── css/
        └── style.scss    # Custom styling
```

## Navigation

The site includes:
- **Homepage**: Overview with key recommendations
- **Synthesis Report**: Full 35-page analysis
- **Methodology**: AI-assisted research process
- **Agent Documentation**: 6 specialized agents
- **Provost Charge**: Official task force mandate

## Custom Features

- **Navigation cards**: Visual grid on homepage
- **Responsive design**: Mobile-friendly
- **Enhanced tables**: Styled financial projections
- **Warning callouts**: Methodological transparency notes
- **Clean theme**: Documentation-focused design

## Updating the Site

To update content:
1. Edit `.md` files in the repository
2. Commit and push changes to `main` branch
3. GitHub automatically rebuilds and deploys (2-3 minutes)

## Troubleshooting

If the site doesn't appear:
- Check GitHub Actions for build errors
- Verify Pages is enabled in repository settings
- Ensure `_config.yml` `baseurl` matches repository name
- Clear browser cache and wait a few minutes

## Local Testing

To test locally before pushing:
```bash
gem install bundler jekyll
bundle install
bundle exec jekyll serve
# Visit http://localhost:4000/ai-taskforce/
```
