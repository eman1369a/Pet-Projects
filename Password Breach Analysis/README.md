# Password Breach Analysis: Promoting Cybersecurity Awareness

![Security](../2020-Data-Breaches-800x400-1.jpg)

## Project Overview

This project focuses on analyzing a breached password dataset to educate employees about the importance of cybersecurity, password creation, and management.

## Analysis Highlights

### Top 20 Most Common Passwords

We analyzed the dataset and identified the top 20 most common passwords, accounting for approximately 39.4% of the total passwords:

| Password   | Count     | Percentage  |
|------------|-----------|-------------|
| 123456     | 6,690,567 | 1.74%       |
| 123456789  | 2,286,809 | 0.59%       |
| 111111     |   983,775 | 0.26%       |
| ...        |   ...     | ...         |

### Password Length Distribution

We examined password lengths and their distributions:

| Length | Count         | Percentage  |
|--------|---------------|-------------|
| 1      |         278   | < 0.01%     |
| 2      |       8,410   | 0.00%       |
| 3      |     118,303   | 0.03%       |
| ...    |     ...       | ...         |

### Password Classification

Passwords were categorized into types:

| Type         | Count         | Percentage  |
|--------------|---------------|-------------|
| Alphanumeric | 209,751,869   | 54.66%      |
| Alphabetic   | 102,299,695   | 26.68%      |
| Complex      |  38,251,465   | 9.98%       |
| Numeric      |  33,850,398   | 8.82%       |

### Entropy Analysis

We calculated entropy to measure password randomness:

| Entropy    | Count         | Percentage  |
|------------|---------------|-------------|
| 2.58       | 6,690,567     | 1.74%       |
| 3.17       | 2,286,809     | 0.59%       |
| -0.00      |   983,775     | 0.26%       |
| ...        | ...           | ...         |

### Dictionary Word Analysis

We identified passwords that match common words:

| Dictionary Word | Count      | Percentage  |
|-----------------|------------|-------------|
| password        | 964,657    | 0.25%       |
| welcome         |  61,807    | 0.02%       |
| letmein         |  54,791    | 0.01%       |
| ...             | ...        | ...         |

## Educational Impact

These insights emphasize the need for strong and unique passwords. By sharing these findings, we can empower employees to make informed decisions and enhance their cybersecurity practices.

## Technical Details

This analysis leveraged PySpark for efficient data processing and insights extraction. To explore the full analysis, refer to the [Jupyter Notebook](PySparks_MostCommonPasswords.ipynb).

Original Datasource from [here](https://web.archive.org/web/20200501154512/https://gist.github.com/scottlinux/9a3b11257ac575e4f71de811322ce6b3)

