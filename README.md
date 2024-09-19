<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Data Analysis Project</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        h1, h2, h3 {
            color: #333;
        }
        .content {
            padding: 20px;
            background: #fff;
            border-radius: 5px;
            margin-bottom: 20px;
        }
        pre {
            background: #f8f8f8;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Data Analysis Project</h1>
        </header>

        <div class="content">
            <h2>Overview</h2>
            <p>This project involves analyzing university rankings data using various tools and techniques. The analysis includes data profiling, quality checks, and univariate analysis to gain insights into the rankings from different sources.</p>
        </div>

        <div class="content">
            <h2>Libraries Used</h2>
            <ul>
                <li><strong>numpy</strong> for numerical operations</li>
                <li><strong>pandas</strong> for data manipulation and analysis</li>
                <li><strong>matplotlib.pyplot</strong> for static visualizations</li>
                <li><strong>seaborn</strong> for statistical data visualization</li>
                <li><strong>scipy.stats</strong> for statistical functions</li>
                <li><strong>plotly.express</strong> and <strong>plotly.graph_objects</strong> for interactive visualizations</li>
            </ul>
        </div>

        <div class="content">
            <h2>Data Profiling</h2>
            <p>Data profiling is a process of examining the data available in a dataset to collect statistics and information about that data. This step helps understand the structure, content, and quality of the data.</p>
        </div>

        <div class="content">
            <h2>Data Quality Checks</h2>
            <p>Data quality checks are crucial for ensuring that the data is accurate, complete, consistent, relevant, and reliable. The following steps are involved in checking data quality:</p>
            <h3>Reliability</h3>
            <p>Evaluate the data's source and collection process to determine its trustworthiness.</p>
            <h3>Rankings and Sources</h3>
            <ul>
                <li><strong>Times Higher Education (THE):</strong>
                    <ul>
                        <li>Based on 10 million datapoints from over 7,000 institutions in 171 countries.</li>
                        <li>Provides insights and intelligence built on a 50-year relationship with universities.</li>
                    </ul>
                </li>
                <li><strong>Academic Ranking of World Universities (ARWU):</strong>
                    <ul>
                        <li>Published by the Center for World-Class Universities (CWCU) since June 2003.</li>
                        <li>Uses six objective indicators including Nobel Prizes, highly cited researchers, and publication metrics.</li>
                    </ul>
                </li>
                <li><strong>Center for World University Rankings (CWUR):</strong>
                    <ul>
                        <li>A consulting organization providing policy advice and strategic insights.</li>
                        <li>Assesses the quality of education, employability, faculty quality, and research without relying on surveys or university data submissions.</li>
                    </ul>
                </li>
            </ul>
        </div>

        <div class="content">
            <h2>Univariate Analysis</h2>
            <p>Univariate analysis involves examining each variable in the dataset individually to summarize and find patterns. This includes calculating basic statistics and creating visualizations to understand the distribution and characteristics of the data.</p>
        </div>
    </div>
</body>
</html>
