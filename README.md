# SQL for Data Analysis Presentation

This repository contains a web-based presentation on **SQL for Data Analysis** by **Dr. Chukwuka Obionwu**, hosted on GitHub Pages at [https://victordeman.github.io/sql-presentation/slide1.html](https://victordeman.github.io/sql-presentation/slide1.html). The presentation introduces SQL (Structured Query Language), its core operations, data analysis techniques, practical examples, data visualization, and key takeaways, designed for learners and professionals in business analytics, data science, and inventory management.

## Overview

The presentation is split into six slides, each in a separate HTML file, with a modern vertical navigation bar on the right side for easy access. The content is styled using [TailwindCSS](https://tailwindcss.com/) and [Feather Icons](https://feathericons.com/) for a responsive, visually appealing design.

### Brief History of SQL
SQL was developed in the 1970s by IBM researchers Raymond Boyce and Donald Chamberlin, based on Edgar F. Codd’s relational database model. Initially called SEQUEL (Structured English Query Language), it was designed for querying IBM’s System R database. Standardized in 1986 by ANSI, SQL evolved into a universal language for relational databases, widely adopted across industries for its simplicity and power in managing and analyzing data.

### Slides
1. **Introduction (slide1.html)**: Introduces SQL as a tool for managing and analyzing data, presented by Dr. Chukwuka Obionwu on September 24, 2025.
2. **CRUD Operations (slide2.html)**: Explains Create, Read, Update, and Delete operations with animated examples on a Sales table, visualizing data manipulation.
3. **Data Analysis (slide3.html)**: Describes data analysis with SQL, its importance, and use cases like retail inventory optimization and customer segmentation.
4. **Practical Example (slide4.html)**: Demonstrates SQL queries to analyze sales data, including:
   - Top 5 products by total sales.
   - Electronics-only product sales.
   - Clothing-only product sales.
   - Total sales by category.
5. **Data Visualization (slide5.html)**: Explores how visualization enhances SQL analysis with examples (e.g., pie charts, line graphs).
6. **Summary (slide6.html)**: Summarizes key takeaways, including SQL’s efficiency, wide applications, and tools like SQLValidator, with a call to action.

## Accessing the Presentation

Visit the presentation at the following URLs:
- [Slide 1: Introduction](https://victordeman.github.io/sql-presentation/slide1.html)
- [Slide 2: CRUD Operations](https://victordeman.github.io/sql-presentation/slide2.html)
- [Slide 3: Data Analysis](https://victordeman.github.io/sql-presentation/slide3.html)
- [Slide 4: Practical Example](https://victordeman.github.io/sql-presentation/slide4.html)
- [Slide 5: Data Visualization](https://victordeman.github.io/sql-presentation/slide5.html)
- [Slide 6: Summary](https://victordeman.github.io/sql-presentation/slide6.html)

Navigate between slides using the vertical navigation bar on the right side of each page.

## Repository Structure
```
sql-presentation/
├── slide1.html        # Introduction
├── slide2.html        # CRUD Operations
├── slide3.html        # Data Analysis
├── slide4.html        # Practical Example
├── slide5.html        # Data Visualization
├── slide6.html        # Summary
├── images/
│   └── profile.jpg
└── README.md         # This file
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

