###Readme


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Expense Tracker Documentation</title>
    <style>
        body {
            font-family: system-ui, -apple-system, sans-serif; /* Using system fonts for a native feel [cite: 35] */
            line-height: 1.6;
            max-width: 800px;
            margin: 40px auto;
            padding: 20px;
            color: #333;
            background-color: #f9fafb;
        }
        h1 {
            color: #1a1a1a;
            border-bottom: 3px solid #2ecc71;
            padding-bottom: 10px;
        }
        h2 {
            color: #2c3e50;
            margin-top: 30px;
            border-left: 5px solid #2ecc71;
            padding-left: 15px;
        }
        ul {
            list-style-type: square;
            padding-left: 20px;
        }
        li {
            margin-bottom: 8px;
        }
        .container {
            background: white;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05); /* Clean, minimal shadow */
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Expense Tracker</h1>
        
        <h2>Overview</h2>
        <p>
            A simple expense tracker built using HTML, CSS, and JavaScript to understand how user input 
            can be processed and reflected dynamically in a web interface.
        </p>

        <h2>Features</h2>
        <ul>
            <li><strong>Add expenses:</strong> Input fields for name, amount, and category.</li>
            <li><strong>Dynamic balance update:</strong> Real-time calculation of totals as data is entered.</li>
            <li><strong>Table display:</strong> A historical log of transactions for immediate feedback.</li>
            <li><strong>Basic pie chart:</strong> A CSS-based visual representation of spending versus remaining balance.</li>
        </ul>

        <h2>Coding Languages Used</h2>
        <ul>
            <li><strong>HTML</strong> - For the document structure.</li>
            <li><strong>CSS</strong> - For the modern, minimal aesthetic.</li>
            <li><strong>Beginner JavaScript</strong> - For DOM manipulation and logic handling.</li>
        </ul>

        <h2>How It Works</h2>
        <p>
            User input is captured through the form &rarr; processed using JavaScript functions 
            &rarr; the UI and balance displays are updated dynamically without a page refresh
        </p>

        <h2>Limitations</h2>
        <ul>
            <li>No persistent data storage (data is lost upon browser refresh).</li>
            <li>Basic UI focus over complex animations.</li>
            <li>Static chart logic based on a fixed starting balance.</li>
        </ul>

        <h2>Learnings</h2>
        <p>
            This project provided a foundation in connecting frontend structure, styling, and logic. 
            It specifically helped in mastering basic DOM manipulation and state handling.
        </p>
    </div>
</body>
</html>
