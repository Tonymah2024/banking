FinSecure Analytics Canada | Banking & Microfinance Dashboard

This repository contains a single-page, interactive dashboard designed for a Canadian banking or microfinance institution. The project showcases modern data visualization techniques, tracks key financial metrics, and integrates Google's Gemini API to provide AI-powered analytical insights.

Live Demo: https://tonymah2024.github.io/banking/

Key Features

    KPI Monitoring: At-a-glance cards for crucial financial metrics like Total Loan Portfolio, Active Clients, Portfolio at Risk (PAR), and Average Loan Balance, all localized for the Canadian market (CAD).

    Interactive Charts: Visualize complex data with clear, responsive charts:

        Loan Portfolio Growth Over Time

        Loan Distribution by Type (Business, Agriculture, etc.)

        Portfolio at Risk by Branch (using Canadian locations)

        Monthly Client Growth and Attrition

    AI-Powered Insights: A "Generate Insights" button sends the current dashboard data to the Google Gemini API, which returns an executive-level summary, identifies key risks, and suggests actionable next steps.

    Custom Data Loading: Use the "Load Data" button to upload a local .json file and instantly populate the entire dashboard with your own custom data.

Technologies Used

    HTML5 for the core structure.

    Tailwind CSS for a modern, responsive, and utility-first design.

    Chart.js for creating interactive and animated data visualizations.

    Google Gemini API for the generative AI "Insights" feature.

How to Use
To Run Locally:

    Download the index.html file from this repository.

    Open the file directly in any modern web browser (like Chrome, Firefox, or Edge).

To Use the AI Insights Feature:

    When you first load the page, a prompt will ask for your Google AI API key.

    Go to Google AI Studio to generate your free key.

    Paste the key into the prompt to enable the "✨ Generate Insights" button.

To Load Your Own Data:

    Create a .json file that matches the structure outlined in the comments within the index.html file's <script> tag.

    Click the "Load Data" button on the dashboard.

    Select your prepared .json file to populate the dashboard with your data.

This project was developed by VisiVault Analytics Ltd. for demonstration purposes.
