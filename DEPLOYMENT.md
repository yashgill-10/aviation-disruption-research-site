# Deployment Guide — Aviation Disruption Research Website

## Overview

This repository contains a static research website for the ES 335 Machine Learning course project. The site is deployed via GitHub Pages.

## Repository Structure

```
.
├── index.html          # Main research website (self-contained)
├── README.md           # Project overview and disclaimers
├── SHA256SUMS.txt      # Integrity verification hashes
└── DEPLOYMENT.md       # This file
```

## Deployment

This site is deployed automatically via GitHub Pages:

1. Push changes to `main` branch
2. GitHub Pages builds and deploys from repository root
3. Site available at `https://yashgill-10.github.io/aviation-disruption-research-site/`

## Verification

To verify file integrity:

```bash
sha256sum -c SHA256SUMS.txt
```

## Security

This repository contains ONLY:
- Static HTML/CSS/JavaScript
- Aggregate research metrics
- Documentation

It does NOT contain:
- Raw flight data or datasets
- Flight identifiers or canonical IDs
- Model binaries or checkpoints
- API keys or credentials
- Personal information
- Local file paths or internal logs

## Contact

For questions about this research, please contact the project maintainers through the main repository.
