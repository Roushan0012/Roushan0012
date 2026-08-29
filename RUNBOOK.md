# Runbook — GitHub Profile Setup & Automation Guide for Roushan Kumar

This repository powers the dynamic GitHub Profile README for **Roushan Kumar** ([@Roushan0012](https://github.com/Roushan0012)).

## 📂 Project Structure
```
Git_profile/
  ├── README.md                               # Dynamic GitHub Profile README
  ├── RUNBOOK.md                              # This setup guide
  ├── info-card.svg                           # Animated neofetch terminal info card
  ├── contrib-heatmap.svg                     # Daily contribution heatmap SVG
  ├── avi-ascii.svg                           # ASCII portrait SVG (optional)
  ├── requirements-local.txt                  # Image processing dependencies
  ├── .github/
  │   └── workflows/
  │       └── update-profile-art.yml          # Daily GitHub Action to refresh heatmap
  ├── data/
  │   └── contributions.json                  # Parsed GitHub contribution records
  └── scripts/
      ├── fetch_contributions.py              # Scrapes GitHub public contributions
      ├── render_heatmap_svg.py               # Generates contribution SVG heatmap
      ├── make_info_card.py                   # Generates animated terminal info card SVG
      ├── make_ascii_svg.py                   # Generates ASCII art SVG from portrait
      ├── prep_photo.py                       # Prepares photo with background removal
      └── requirements.txt                    # Scraper dependencies (requests, bs4)
```

---

## 🛠️ Step-by-Step Setup & Deployment

### 1. Install Dependencies
```bash
pip install -r scripts/requirements.txt
```

### 2. Regenerate SVG Assets
```bash
# Render terminal info card
python3 scripts/make_info_card.py

# Fetch Roushan0012's contributions & render heatmap
GH_PROFILE_USER=Roushan0012 python3 scripts/fetch_contributions.py
python3 scripts/render_heatmap_svg.py
```

### 3. Push to GitHub Repositories

#### Option A: Push to `Github-Profile` repository
```bash
git add .
git commit -m "Update profile README, projects, skills, and achievements according to resume"
git branch -M main
git remote set-url origin https://github.com/Roushan0012/Github-Profile.git
git push -u origin main
```

#### Option B: Connect Directly to Your GitHub Profile Header (`Roushan0012/Roushan0012`)
> [!NOTE]
> GitHub shows the README on your profile page `https://github.com/Roushan0012` if it lives in a special repository named **`Roushan0012`** (matching your username).

To link this README to your profile page:
1. Create a public repository named `Roushan0012` on GitHub (if not created already).
2. Push this repo to `Roushan0012/Roushan0012`:
```bash
git remote set-url origin https://github.com/Roushan0012/Roushan0012.git
git push -u origin main
```

---

## 🔄 Automated Daily Updates via GitHub Actions
1. Go to your repo on GitHub: **Settings → Actions → General → Workflow permissions**.
2. Select **"Read and write permissions"** and click **Save**.
3. The `.github/workflows/update-profile-art.yml` action will now automatically scrape and update your contribution heatmap every day!
