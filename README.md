# GitHub Profile Analyzer ⚡

A beautiful, fully client-side web application that analyzes any GitHub user profile and provides instant insights about their coding patterns, languages, top repositories, and developer strengths.

🔗 **[Live Demo](https://YOUR_USERNAME.github.io/github-profile-analyzer/)** *(replace with your URL after deployment)*

## ✨ Features

- 🔍 **Instant Analysis** — Enter any GitHub username and get a full profile breakdown in seconds
- 📊 **Quality Score** — Smart algorithm scores profiles out of 100 based on activity, impact, and diversity
- 💻 **Language Distribution** — Visual breakdown of top programming languages with animated bars
- 🏆 **Developer Badges** — Earn badges like *Polyglot*, *Star Power*, *Veteran*, and more
- 🔥 **Top Repositories** — See the most starred projects with descriptions and metadata
- 💪 **Smart Insights** — Personalized strengths, growth areas, and career recommendations
- 📥 **Export Report** — Download analysis as a text file
- 🎨 **Modern UI** — Glass-morphism design with navy/purple gradient theme
- 📱 **Fully Responsive** — Works perfectly on mobile, tablet, and desktop
- ⚡ **Zero Setup** — Single HTML file, no build tools, no API keys, no backend

## 🚀 Quick Start

Just open `index.html` in any modern browser. That's it!

```bash
# Or serve it locally:
python -m http.server 8000
# Then visit http://localhost:8000
```

## 🛠️ Tech Stack

- **HTML5** — Semantic markup
- **CSS3** — Custom properties, grid, flexbox, animations, glass-morphism
- **Vanilla JavaScript** — Async/await, Fetch API, ES6+
- **GitHub REST API** — Live profile data

No frameworks. No build tools. No dependencies. 100% client-side.

## 🎨 Design Specifications

### Color Palette
- **Primary Navy:** `#1a202c`
- **Accent Purple:** `#7c3aed`
- **Electric Blue:** `#3b82f6`
- **Success Green:** `#10b981`
- **Background:** Navy gradient with floating purple blob

### Typography
- **Inter** — Primary UI font (300-900 weights)
- **JetBrains Mono** — Code & usernames

## 📋 How It Works

1. **User Input** — Enter a GitHub username
2. **Fetch Data** — Calls GitHub REST API for profile + repos (no auth needed)
3. **Analyze** — Calculates quality score, languages, badges, and insights
4. **Render** — Beautiful dashboard with charts, cards, and recommendations
5. **Export** — Optional text report download

## 🏆 Quality Score Algorithm

The score (0-100) considers:
- Followers count (up to 25 pts)
- Public repositories (up to 20 pts)
- Total stars earned (up to 25 pts)
- Language diversity (up to 15 pts)
- Profile completeness — bio, blog, company, README (up to 15 pts)

## 🎯 Try It With

- `torvalds` — Linux creator
- `gaearon` — React core team
- `sindresorhus` — Open source legend
- `octocat` — GitHub mascot

## ⚙️ GitHub API Rate Limits

The unauthenticated GitHub API allows **60 requests per hour per IP**. Each analysis uses 2 requests. For higher limits, you can fork this and add a personal access token.

## 📂 Project Structure

```
github-profile-analyzer/
├── index.html       # Everything (HTML + CSS + JS inline)
└── README.md        # This file
```

## 🌟 Why Single File?

This project demonstrates:
- ✅ Modern vanilla web development without frameworks
- ✅ Clean separation of concerns within one file
- ✅ Beautiful UI achievable with pure CSS
- ✅ Real API integration (no fake data)
- ✅ Easy deployment (GitHub Pages, Netlify, anywhere)

## 📜 License

MIT License — Feel free to use, modify, and share!

## 🙏 Credits

- GitHub REST API
- Google Fonts (Inter, JetBrains Mono)
- Designed and built with vanilla web tech

---

**Built as a portfolio project to demonstrate full-stack thinking with a minimalist tech stack.**
