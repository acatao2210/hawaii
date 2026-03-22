# 🌺 Hawaii Trip 2025

A static website itinerary for an 11-day Hawaii trip (May 18–29, 2025) across Oahu and the Big Island.

## How to Deploy on GitHub Pages

1. **Create a new GitHub repository** at github.com (e.g., `hawaii-trip-2025`)

2. **Upload all files** — drag and drop the entire folder contents into the repository, or use git:
   ```bash
   git init
   git add .
   git commit -m "Hawaii trip website"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/hawaii-trip-2025.git
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - Go to your repository → Settings → Pages
   - Under "Source", select `main` branch and `/ (root)` folder
   - Click Save
   - Your site will be live at `https://YOUR_USERNAME.github.io/hawaii-trip-2025/` within a minute or two

## File Structure

```
index.html          ← Main itinerary page (start here)
style.css           ← Shared stylesheet
days/
  may18.html        ← Day pages (one per day)
  may19.html
  ...
  may29.html
```

## Local Preview

Just open `index.html` in any browser — no server needed.
