# SQL for Data Analysis Presentation

This repository contains a web-based presentation on **SQL for Data Analysis** by **Dr. Chukwuka Obionwu**, hosted on GitHub Pages at [https://victordeman.github.io/sql-presentation/slide1.html](https://victordeman.github.io/sql-presentation/slide1.html). The presentation introduces SQL (Structured Query Language), its role in data analysis, and practical examples using a sample sales dataset. It is designed for learners and professionals interested in leveraging SQL for business analytics, data science, and inventory management.

## Overview

The presentation is split into four slides, each in a separate HTML file, with a vertical navigation bar on the right side for easy access. The content is styled using [TailwindCSS](https://tailwindcss.com/) and [Feather Icons](https://feathericons.com/) for a modern, responsive design.

### Slides
1. **Introduction (slide1.html)**: Introduces SQL and its importance in analyzing sales data, presented by Dr. Chukwuka Obionwu on September 24, 2025.
2. **What is SQL? (slide2.html)**: Explains SQL as a Structured Query Language, its key commands (`SELECT`, `WHERE`, `GROUP BY`), and includes a sample Sales table.
3. **Practical Example (slide3.html)**: Demonstrates SQL queries to analyze sales data, including:
   - Top 5 products by total sales.
   - Electronics-only product sales.
   - Clothing-only product sales.
   - Total sales by category.
4. **Summary (slide4.html)**: Highlights key takeaways, such as SQL’s efficiency, wide applications, and tools like SQLValidator, with a call to action to explore business problems using SQL.

## Accessing the Presentation

Visit the presentation at the following URLs:
- [Slide 1: Introduction](https://victordeman.github.io/sql-presentation/slide1.html)
- [Slide 2: What is SQL?](https://victordeman.github.io/sql-presentation/slide2.html)
- [Slide 3: Practical Example](https://victordeman.github.io/sql-presentation/slide3.html)
- [Slide 4: Summary](https://victordeman.github.io/sql-presentation/slide4.html)

Navigate between slides using the vertical navigation bar on the right side of each page.

## Repository Structure
```

sql-presentation/
├── slide1.html        # Introduction slide
├── slide2.html        # What is SQL? slide
├── slide3.html        # Practical Example slide with multiple queries
├── slide4.html        # Summary slide
├── images/
│   └── profile.jpg    # Profile image for Dr. Obionwu
└── README.md          # This file

```

## Setup Instructions

1. **Clone the Repository**:

To host or modify this presentation locally or on your own GitHub Pages:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/victordeman/sql-presentation.git
   cd sql-presentation

2. **Host on GitHub Pages**:

   Create a new repository or use an existing one.
    Push all files to the main branch:bash

    git add .
    git commit -m "Update presentation with right-side navbar"
    git push origin main

    Go to Settings > Pages in your repository.
    Set Source to main branch and / (root) folder.
    Access the presentation at https://<your-username>.github.io/<repo-name>/slide1.html.

