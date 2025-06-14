X Analysis - Interactive Social Media Analytics Report
This is an interactive web application designed to help you analyze social media data exported from X (formerly Twitter). It allows users to upload CSV data and view aggregated metrics, engagement insights, top-performing content, and dynamic observations based on the provided data.

Live Demo: https://thomas-nada.github.io/X-analysis/

Features
CSV Data Upload: Easily upload your X analytics CSV files. The tool attempts to automatically detect the type of CSV (Content-level or Account Overview).

Comprehensive Analytics Sections:

Individual Post Analysis: (For Content CSVs) Select individual posts from a dropdown to view all their associated metrics.

Aggregate Performance Metrics: (For Content CSVs) View total and average values for key metrics like impressions, likes, engagements, etc., across all analyzed posts.

Content Engagement Insights: (For Content CSVs) See the overall engagement rate and a list of key engagement drivers (e.g., likes, reposts).

Top Performing Posts: (For Content CSVs) Highlights of your best-performing posts based on metrics like engagements, impressions, likes, and reposts.

Account Overview Analytics: (For Account Overview CSVs) Displays summary cards for total impressions, engagements, net follower growth, etc., and a table of daily overview data.

Dynamic Data-Driven Insights:

Key Content Themes: Automatically identifies and displays prominent themes from the textual content of your posts (for Content CSVs).

Key Observations & Potential Insights: Generates data-driven observations based on the performance metrics in the uploaded CSV.

Conclusion: Provides a summary conclusion based on the analyzed themes and observations.

HTML Slide Show Mode: View the entire report as an interactive, navigable HTML-based slide presentation directly in your browser.

Download Sections as PNG: Download individual report sections (e.g., Top Posts, Key Observations, Individual Post Details) as transparent PNG images for easy sharing or inclusion in other reports.

Light/Dark Mode Theme: Toggle between light and dark themes for comfortable viewing.

Responsive Design: The report is designed to be usable on various screen sizes.

How to Use
Prepare Your Data:

Export your analytics data from X. The tool is designed to work with CSV files, typically either:

Content CSV: Contains data for individual posts (e.g., "Post id", "Post text", "Impressions", "Engagements", "Likes", etc.).

Account Overview CSV: Contains daily aggregated data for your account (e.g., "Date", "Impressions", "New follows", "Unfollows", etc.).

The tool will attempt to identify the CSV type based on common column headers.

Upload CSV:

Click the "Choose CSV File" button.

Select your exported CSV file from your computer.

Click the "Load and Process Data" button.

View Report:

Once the data is processed, the relevant report sections will populate.

If a known channel/account name column (like "Screen name" or "Author") is found in your CSV, the main title of the report will update to reflect this (e.g., "@YourChannel Report"). Otherwise, it defaults to "@IntersectMBO Report".

Browse through the different sections to view your analytics.

Use the table sorting features by clicking on column headers in tables.

For "Individual Post Analysis," select a post from the dropdown to see its details.

View as Slides:

After loading data, click the "View as Slides" button.

This will open an HTML-based slide show mode.

Use the "Previous" and "Next" buttons to navigate.

Click "Exit Slide Show" to return to the main report view.

Download Sections as PNG:

Each report section has a small image icon button () in its title bar.

Click this button to download the content of that specific section as a PNG image with a transparent background.

The PNG download button for "Individual Post Analysis" is enabled only after you select a post. Other PNG buttons are enabled once their respective sections have data.

Technology Stack
HTML5

Tailwind CSS (for styling)

JavaScript (for all interactivity, data processing, and dynamic content generation)

Font Awesome (for icons)

html2canvas (for generating PNG images from HTML sections)

Contributing / Issues
If you encounter any bugs or have suggestions for new features, please feel free to open an issue on this GitHub repository.

When reporting a bug, please include:

A description of the issue.

Steps to reproduce the bug.

The type of CSV you were using (Content or Account Overview, if known).

Any error messages from the browser console.
