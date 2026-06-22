# Power BI Portfolio

A professional portfolio website showcasing expert-level Power BI dashboards and data analytics projects.

**Live Site:** [mumid.github.io](https://mumid.github.io)

---

## Overview

This portfolio demonstrates advanced Power BI proficiency through multi-page, interactive analytical solutions. Each project showcases:

- **Advanced DAX:** 100+ optimized measures, complex calculations, and time-based analytics
- **Data Modeling:** Efficient relational schemas, cardinality optimization, and performance tuning
- **Visual Design:** Professional custom themes, intuitive navigation, and data-driven insights
- **Data Preparation:** Rigorous ETL, quality assurance, and Python-based transformations

---

## Featured Projects

### 1. Sales & Retail Analytics Dashboard
**Status:** Published  
**Data Points:** ~60,000 transactions | $24.5M total sales  
**Pages:** 4 interactive reports  

**Report Pages:**
- **Executive Overview:** KPI summary, category performance, top products
- **Product Analysis:** Lifecycle segmentation, profitability matrix, trend analysis
- **Regional Performance:** Geographic heat maps, regional benchmarking, growth trends
- **Customer Analytics:** RFM segmentation, customer lifetime value, retention analysis

**Key Features:**
- Custom synthetic product categories (Electronics & Gadgets, Health & Wellness)
- Product lifecycle classification (New, Growing, Declining, Mature)
- Advanced date-shifting and data quality improvements
- 100+ DAX measures for comprehensive analytics

[View Dashboard](https://mumid.github.io/projects/sales-retail-analytics.html)

---

## Directory Structure

```
mumid.github.io/
├── index.html                    # Home page with project grid
├── about.html                    # About & expertise overview
├── styles.css                    # Unified stylesheet
├── projects/
│   ├── sales-retail-analytics.html   # Sales dashboard project page
│   └── (future projects)
└── README.md
```

---

## Getting Started

### For Visitors
Simply visit [mumid.github.io](https://mumid.github.io) to explore the portfolio.

### For Local Development

1. **Clone the repository:**
   ```bash
   git clone https://github.com/mumid/mumid.github.io.git
   cd mumid.github.io
   ```

2. **Run a local server:**
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   
   # Node.js (with http-server package)
   npx http-server
   ```

3. **Open in browser:**
   ```
   http://localhost:8000
   ```

---

## Technology Stack

### Frontend
- **HTML5** – Semantic markup
- **CSS3** – Modern styling with CSS variables for maintainability
- **JavaScript** – Interactivity and dynamic features

### Dashboards
- **Power BI Desktop** – Report development
- **DAX** – Advanced calculations and measures
- **Power BI "Publish to Web"** – Public embedding

### Data
- **Python** – Data transformation and preparation (Pandas, NumPy)
- **CSV/Excel** – Data sources and intermediate formats

---

## Project Structure & Design

### Home Page (`index.html`)
- Sticky navigation bar with active link highlighting
- Hero section with value proposition
- Blog-style project grid with filterable cards
- Social links and contact information
- Responsive design (mobile-first)

### Project Pages (e.g., `sales-retail-analytics.html`)
- Dashboard header with metadata (publish date, data scope, technology)
- Embedded Power BI report (responsive iframe)
- Comprehensive documentation:
  - Project overview
  - Dataset description and transformations
  - Report architecture (page-by-page breakdown)
  - Key metrics and DAX techniques
  - Design and interactivity notes
  - Technical implementation details
  - Skills demonstrated
  - Differentiators from generic projects

### Styling (`styles.css`)
- CSS variable system for consistent theming (colors, shadows, transitions)
- Responsive grid layouts (auto-fill minmax for fluid design)
- Accessibility-focused color contrasts
- Smooth transitions and hover states
- Mobile breakpoints at 768px and below

---

## Dashboard Embedding

Power BI reports are embedded using Microsoft's "Publish to Web" feature:

```html
<iframe 
    title="Report Title" 
    src="https://app.powerbi.com/view?r=..."
    allowfullscreen="true"
    frameborder="0"
></iframe>
```

**Note:** The embedded report is publicly accessible and does not require authentication.

---

## Adding New Projects

To add a new project to the portfolio:

1. **Create a new project page** in the `projects/` directory:
   ```html
   projects/new-project.html
   ```

2. **Use the existing template** from `sales-retail-analytics.html` with updated:
   - Title and description
   - Power BI embed URL
   - Metadata (publish date, data scope, etc.)
   - Comprehensive documentation

3. **Add a project card** to the grid on `index.html`:
   ```html
   <article class="project-card">
       <div class="project-header">
           <h3>New Project Title</h3>
           <span class="badge badge-featured">Featured</span>
       </div>
       <!-- Card content -->
       <a href="projects/new-project.html" class="btn btn-primary">View Dashboard</a>
   </article>
   ```

4. **Commit and push** to GitHub:
   ```bash
   git add .
   git commit -m "Add new project: [Project Name]"
   git push origin main
   ```

---

## Customization

### Colors & Branding
Update CSS variables in `styles.css`:
```css
:root {
    --primary-color: #0078d4;      /* Main brand color */
    --secondary-color: #50e6ff;    /* Accent color */
    --text-dark: #1a1a1a;          /* Primary text */
    --bg-light: #f5f5f5;           /* Light backgrounds */
}
```

### Social Links & Contact
Update URLs in the footer across all pages:
```html
<a href="https://linkedin.com/in/YOUR_PROFILE" class="social-link">LinkedIn</a>
<a href="https://github.com/YOUR_HANDLE" class="social-link">GitHub</a>
```

---

## Performance & Accessibility

- **Semantic HTML:** Proper heading hierarchy, alt text for images
- **CSS Efficiency:** Variables reduce duplication, minimal repaints
- **Responsive Design:** Mobile-first approach with breakpoints
- **Accessibility:** Color contrast ratios meet WCAG AA standards
- **Loading:** Lightweight pages; embedded iframes load on-demand

---

## Future Enhancements

- [ ] Additional portfolio projects (Finance, HR, Marketing, Operations)
- [ ] Dark mode toggle
- [ ] Search/filter functionality across project cards
- [ ] Blog section for analytics insights
- [ ] Contact form integration
- [ ] Analytics integration (Google Analytics or Plausible)

---

## License

This portfolio is for professional use. The source code is provided as-is; Power BI reports and datasets are proprietary.

---

## Contact

- **LinkedIn:** [linkedin.com/in/abdulquadir](https://linkedin.com/in/abdulquadir)
- **GitHub:** [github.com/mumid](https://github.com/mumid)
- **Portfolio:** [mumid.github.io](https://mumid.github.io)

---

**Last Updated:** June 2026
