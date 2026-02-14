# Customer-Behavior-Analytics
Customer Behavior Analytics is a retail data project that cleans and analyzes Kaggle sales data using Python, stores it in MySQL, and builds an interactive Power BI dashboard with DAX measures to visualize trends in sales, customers, demographics, and revenue for actionable business insights.

<!DOCTYPE html>
<html lang="en">
<!-- <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Customer Behavior Analytics Project</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f8f9fa;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 85%;
            margin: auto;
            background: #ffffff;
            padding: 20px;
            margin-top: 30px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2, h3 {
            color: #222;
        }
        p {
            font-size: 16px;
            line-height: 1.7;
        }
        ul {
            margin-left: 20px;
        }
        a {
            color: #0073e6;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 15px 0;
        }
        table, th, td {
            border: 1px solid #aaa;
        }
        th, td {
            padding: 10px;
            text-align: left;
        }
        .dashboard-link {
            display: inline-block;
            padding: 12px 18px;
            background-color: #0073e6;
            color: #fff;
            border-radius: 5px;
            margin-bottom: 20px;
        }
        .dashboard-link:hover {
            background-color: #005bb5;
        }
        .screenshot {
            width: 100%;
            border: 2px solid #ccc;
            margin-top: 10px;
        }
    </style> -->
</head>
<body>
    <div class="container">
        <h1>📊 Customer Behavior Analytics</h1>
        <p><strong>Retail Sales Trends & Consumer Insights Dashboard</strong></p>
        <!-- Live Dashboard -->
        <div>
            <h2>🔗 Live Dashboard</h2>
            <p>Explore the interactive dashboard created in Power BI:</p>
            <a href="https://app.powerbi.com/groups/me/reports/e52c5843-bb77-4902-91b5-c235dad869f8?ctid=8de99cc1-9a87-4fb0-b5b9-51e41ef7338d&pbi_source=linkShare"
               class="dashboard-link" target="_blank">
               View Power BI Interactive Dashboard
            </a>
        </div>
        <!-- Overview -->
        <div>
            <h2>📌 Project Overview</h2>
            <p>
                <strong>Customer Behavior Analytics — Retail Sales Trends & Consumer Insights</strong> is a complete data analytics and business intelligence project designed to analyze customer behaviour and sales performance using a real retail dataset. 
            </p>
            <p>
                The project involves data extraction, cleaning, transformation, SQL querying, and interactive dashboard creation to reveal meaningful insights into sales trends, customer groups, and product performance.
            </p>
        </div>
        <!-- Why It Matters -->
        <div>
            <h2>📍 Why This Project Matters</h2>
            <p>
                Raw data provides little value unless it is analyzed and explained visually. This dashboard helps businesses and analysts:
            </p>
            <ul>
                <li>Understand sales trends across seasons and categories.</li>
                <li>Identify high-value customer segments.</li>
                <li>Compare product performance by gender and age group.</li>
                <li>Make data-driven decisions.</li>
            </ul>
        </div>
        <!-- Tools & Workflow -->
        <div>
            <h2>🛠 Tools & Technologies Used</h2>
            <table>
                <tr>
                    <th>Tool</th>
                    <th>Purpose</th>
                </tr>
                <tr>
                    <td>Python</td>
                    <td>Data cleaning, null handling, new column creation</td>
                </tr>
                <tr>
                    <td>MySQL</td>
                    <td>Database storage & SQL querying</td>
                </tr>
                <tr>
                    <td>Power BI</td>
                    <td>Interactive dashboard creation & visualization</td>
                </tr>
                <tr>
                    <td>DAX</td>
                    <td>Measures and advanced calculations in Power BI</td>
                </tr>
                <tr>
                    <td>Kaggle</td>
                    <td>Source of the dataset</td>
                </tr>
            </table>
        </div>
        <!-- Project Workflow -->
        <div>
            <h2>🔍 Project Workflow & Methodology</h2>
            <h3>1. Data Collection & Source</h3>
            <p>
                The dataset was obtained from Kaggle and contained retail sales data including customer demographics, product categories, transaction dates, sales figures, and more.
            </p>
            <h3>2. Data Preprocessing Using Python</h3>
            <p>
                Python was used to inspect the dataset structure, remove null values, correct inconsistencies, and create calculated columns (like age group, revenue groups) to enhance analysis.
            </p>
            <h3>3. Data Import & Querying with MySQL</h3>
            <p>
                Cleaned data was imported into a MySQL database. Complex SQL queries were used to aggregate information — such as total revenue per category, total sales per season, and age group analysis — before visualization.
            </p>
            <h3>4. Interactive Visualization with Power BI</h3>
            <p>
                MySQL results were loaded into Power BI, and multiple visuals were created including bar charts, line charts, KPI cards, pie charts, and filters. Advanced calculations were implemented using DAX for dynamic insight.
            </p>
        </div>
        <!-- Key Features -->
        <div>
            <h2>📊 Key Features & Insights</h2>
            <ul>
                <li><strong>Total Sales and Customers</strong> summary for quick high-level overview.</li>
                <li><strong>Seasonal Trend Analysis</strong> showing how sales change across Fall, Spring, Summer, and Winter.</li>
                <li><strong>Revenue Contribution</strong> by gender and product category.</li>
                <li><strong>Subscription Status Insights</strong> showing subscribed vs non-subscribed customer percentages.</li>
                <li><strong>Revenue by Age Group</strong> to understand which age segments spend most.</li>
                <li>Interactive filters allow deep-dive trends and decisions.</li>
            </ul>
        </div>
        <!-- Business Value -->
        <div>
            <h2>🎯 Business Use Cases</h2>
            <p>This dashboard is valuable for:</p>
            <ul>
                <li>Retail managers optimizing stock and seasonal campaigns</li>
                <li>Marketing teams identifying target customers</li>
                <li>Business analysts revealing hidden trends</li>
                <li>Decision-makers improving strategic planning</li>
            </ul>
        </div>
        <!-- Summary -->
        <div>
            <h2>📝 Summary</h2>
            <p>
                This project demonstrates a real-world analytical process involving Python, SQL, and interactive Power BI dashboards. It turns raw retail data into actionable insights and provides a practical tool for exploring customer and sales trends.
            </p>
        </div>
    </div>

</body>
</html>
