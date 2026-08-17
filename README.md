# 🌐 Public API Directory

A clean, fast, and responsive directory for discovering **free public APIs** for your next project.

Search APIs, filter them by category, save your favorites, and quickly explore API endpoints — all from a modern dark-themed interface.

## ✨ Features

- 🔍 **Instant Search** — Find APIs by name, description, or category
- 📂 **Category Filtering** — Browse APIs by categories such as Animals, Finance, Weather, Games, and more
- ⭐ **Favorites** — Save your favorite APIs using `localStorage`
- 📊 **Live Statistics** — View total APIs, categories, and HTTPS-supported APIs
- 🔗 **Shareable URLs** — Open and share direct links to API details
- 📋 **Copy Endpoints** — Copy API URLs with one click
- 🔒 **HTTPS & CORS Info** — Quickly check API security and browser compatibility
- 📱 **Responsive Design** — Optimized for desktop, tablet, and mobile
- 🌙 **Dark Theme** — Developer-friendly dark interface
- ⚡ **No Frameworks** — Built with vanilla HTML, CSS, and JavaScript


## 🛠️ Technologies

| Technology | Purpose |
|---|---|
| **HTML5** | Semantic page structure |
| **CSS3** | Styling, custom properties, Flexbox, and responsive layouts |
| **JavaScript** | Search, filtering, favorites, API details, and interactions |
| **LocalStorage** | Persisting favorite APIs |
| **GitHub Pages** | Free static website hosting |
| **Public APIs Dataset** | API directory data |

## 📋 How It Works

### 1. Browse APIs

Explore the complete collection of public APIs displayed in a searchable directory.

### 2. Search

Use the search bar to find APIs by:

- Name
- Description
- Category

### 3. Filter by Category

Select a category to narrow the results and discover APIs relevant to your project.

### 4. View API Details

Click an API to view additional information such as:

- API description
- Category
- Endpoint
- Authentication requirements
- HTTPS support
- CORS availability

### 5. Save Favorites

Click the ⭐ button to save an API.

Favorites are stored locally in your browser using `localStorage`, so no account is required.

### 6. Copy API URLs

Use the copy button to quickly copy an API endpoint to your clipboard.

## 📁 Project Structure

```text
public-api-directory/
│
├── index.html          # Main application page
└── README.md
```

> Adjust the structure above to match your actual project files.

## ⚙️ Getting Started

### Prerequisites

No build tools, package managers, or frameworks are required.

You only need a modern web browser.

### Clone the Repository

```bash
git clone https://github.com/hxrsh7d/api-directory.git
```

### Navigate to the Project

```bash
cd YOUR_REPO_NAME
```

### Run Locally

Because this is a static website, you can open `index.html` directly in your browser.

Alternatively, use a local development server:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## 🌍 Deploy with GitHub Pages

This project can be hosted for free using GitHub Pages.

### 1. Push the Project to GitHub

```bash
git add .
git commit -m "Initial commit"
git push -u origin main
```

### 2. Enable GitHub Pages

Go to:

**Repository → Settings → Pages**

Under **Build and deployment**:

- **Source:** Deploy from a branch
- **Branch:** `main`
- **Folder:** `/ (root)`

Click **Save**.

Your website will be available at:

```text
https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/
```

## 📡 Data Source

The API information is based on the **Public APIs** repository:

https://github.com/public-apis/public-apis

Please review the source repository's current license and usage terms before redistributing its data.

## 🔐 Privacy

This project does not require user accounts or collect personal information.

Favorites are stored locally in the user's browser using `localStorage`.

## 🤝 Contributing

Contributions are welcome!

### Create a Fork

Fork this repository on GitHub.

### Create a Branch

```bash
git checkout -b feature/your-feature
```

### Make Your Changes

Implement your feature or fix.

### Commit Your Changes

```bash
git add .
git commit -m "Add your feature"
```

### Push Your Branch

```bash
git push origin feature/your-feature
```

Then open a Pull Request.

## 🐛 Issues & Feature Requests

Found a bug or have an idea?

Please open an issue and include:

- A clear description
- Steps to reproduce the problem
- Expected behavior
- Actual behavior
- Screenshots, if applicable

## ⭐ Support

If you find this project useful, consider giving it a ⭐ on GitHub.

It helps others discover the project and motivates further development.

## 📄 License

This project is open source. Add your chosen license file, such as `MIT`, to the repository and update this section accordingly.

---

**Built with ❤️ for developers who love APIs.**
