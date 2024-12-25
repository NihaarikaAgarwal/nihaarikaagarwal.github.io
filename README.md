# Nihaarika Agarwal's GitHub.io Profile

Welcome to my GitHub.io profile! Below is a representation of my personal webpage layout:

## Overview
- **Name:** Nihaarika Agarwal  
- **Title:** MS Computer Science, Data Analyst  
- **GitHub Link:** [GitHub Profile](https://github.com)  

## Layout Description
The webpage layout consists of:
- A **split-screen design**:
  - **Left section:** Contains my name, title, and a clickable link to my GitHub profile.
  - **Right section:** Displays a background image.

## Code
Below is the HTML and CSS code used to create this layout. You can use this code to replicate the design:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nihaarika Agarwal</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background-color: #000;
            color: #fff;
        }

        .container {
            display: flex;
            height: 100vh;
            align-items: center;
            justify-content: space-between;
            overflow: hidden;
        }

        .text-section {
            flex: 1;
            padding: 50px;
        }

        .text-section h1 {
            font-size: 4rem;
            font-weight: bold;
            margin: 0;
        }

        .text-section p {
            font-size: 1.2rem;
            margin: 10px 0;
        }

        .text-section a {
            text-decoration: none;
            color: #00aaff;
            font-size: 1.2rem;
        }

        .image-section {
            flex: 1;
            background: url('Screenshot 2024-12-25 at 14.49.40.png') center/cover no-repeat;
        }

        .github-link {
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="text-section">
            <h1>Nihaarika Agarwal</h1>
            <p>MS Computer Science, Data Analyst</p>
            <a class="github-link" href="https://github.com" target="_blank">GitHub Profile</a>
        </div>
        <div class="image-section"></div>
    </div>
</body>
</html>
```

