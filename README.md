# 🔬 AI Research Daily

**The Scholar's Automated Research Intelligence System**

AI Research Daily is a GitHub-native research aggregator that continuously monitors cutting-edge AI research from https://accidentaljedi.github.io/AI_Research_Daily/, analyzes discoveries with scholarly depth, and publishes comprehensive daily reports—all automated on GitHub's free tier.

## 🎯 What It Does

- **Ingests Research**: Daily scraping of AI Research Daily feed
- **Deep Analysis**: Three-layer scholarly examination (Deep Dive, Cross-Project Analysis, Practical Implications)
- **The Scholar Persona**: Academic voice with technical rigor and contextual depth
- **Auto-Publishes**: GitHub Pages deployment with searchable archive
- **Zero Maintenance**: Runs on GitHub Actions (scheduled at 08:05 CT daily)

## 🏗️ Architecture

```
AI_Research_Daily/
├── .github/workflows/
│   └── daily_lab_blog.yml    # Daily Scholar report generation (08:05 CT)
├── scripts/
│   └── generate_lab_blog.py  # Research ingestion + Scholar analysis
├── data/
│   └── lab/                  # {date}.json research data
├── docs/
│   ├── reports/
│   │   ├── index.html        # 📚 Reports Archive (list + calendar views)
│   │   └── pulse-{date}.html # Daily Scholar reports
│   └── _layouts/
│       └── default.html      # Crimson-accented dark theme
└── requirements.txt          # Python dependencies
```

## 🚀 Quick Start

### 1. Clone & Install
```bash
git clone https://github.com/Grumpified-OGGVCT/AI_Research_Daily.git
cd AI_Research_Daily
pip install -r requirements.txt
```

### 2. Enable GitHub Actions
- Go to Settings → Actions → General
- Enable "Read and write permissions"

### 3. Enable GitHub Pages
- Go to Settings → Pages
- Source: main branch, Folder: /docs

### 4. Test Locally
```bash
python scripts/generate_lab_blog.py
```

## 📊 Report Structure

Each daily report includes:

### 🔬 Deep Dive
Technical explanations of how technologies work:
- Architecture and algorithms
- Design decisions and trade-offs
- Implementation details

### 🔗 Cross-Project Analysis
Identifying synergies between research:
- Related projects and models
- Integration opportunities
- Comparative approaches

### 💡 Practical Implications
Real-world applications:
- Use cases and ecosystem fit
- Who should care and why
- Future possibilities

## 🎨 Design Features

- **Crimson Accents** (#DC143C) - Scholarly sophistication
- **Dark Theme** - Comfortable reading
- **Reports Archive** - Searchable with list/calendar views
- **Responsive Layout** - Mobile-friendly

## 🔗 Integration with GrumpiBlogged

AI Research Daily is part of the GrumpiBlogged ecosystem:
- **Ollama Pulse** (08:00 CT) - EchoVein's vein-tapping reports
- **AI Research Daily** (08:05 CT) - The Scholar's deep analysis
- **GitHub Trending** (09:00 CT) - Persona-driven project reviews

Access via: `http://127.0.0.1:8081/admin/grumpiblogged`

## 📄 License

MIT License

---

**Live Dashboard**: https://grumpified-oggvct.github.io/AI_Research_Daily
**Repository**: https://github.com/Grumpified-OGGVCT/AI_Research_Daily
**Source Feed**: https://accidentaljedi.github.io/AI_Research_Daily/
