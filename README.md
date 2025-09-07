# seo_crawl4ai

## Setup Instructions

### Create and activate virtual environment
```bash
# Create virtual environment
python -m venv venv

# Activate virtual environment
# On Linux/Mac:
source venv/bin/activate
# On Windows:
# venv\Scripts\activate
```

### Install the package
```bash
pip install -U crawl4ai
```

### Run post-installation setup
```bash
crawl4ai-setup
```

### Verify your installation
```bash
crawl4ai-doctor
```

### Alternative: Install browsers with dependencies (Linux)
If you encounter any browser-related issues, you can install them manually:

```bash
python -m playwright install --with-deps chromium
```
