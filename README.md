<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chrome Password Recovery Tool</title>
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
        header {
            background: #333;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #bbb 1px solid;
        }
        header h1 {
            text-align: center;
            margin: 0;
            font-size: 2.5em;
        }
        article {
            padding: 20px;
            background: #fff;
            margin-top: 20px;
            border-radius: 5px;
        }
        h2 {
            border-bottom: 2px solid #333;
            padding-bottom: 5px;
        }
        code {
            background: #f4f4f4;
            border: 1px solid #ddd;
            padding: 2px 5px;
        }
        pre {
            background: #f4f4f4;
            border: 1px solid #ddd;
            padding: 10px;
            overflow-x: auto;
        }
        a {
            color: #333;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        .footer {
            text-align: center;
            padding: 20px;
            background: #333;
            color: #fff;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Chrome Password Recovery Tool</h1>
        </div>
    </header>

    <div class="container">
        <article>
            <h2>Introduction</h2>
            <p>This tool is designed to recover saved passwords from Google Chrome's profile data using Delphi. It reads the encrypted passwords stored in Chrome and decrypts them for retrieval.</p>

            <h2>Features</h2>
            <ul>
                <li>Recover saved passwords from Google Chrome</li>
                <li>Decrypt encrypted passwords</li>
                <li>Simple and easy-to-use interface</li>
            </ul>

            <h2>Installation</h2>
            <p>To use this tool, follow these steps:</p>
            <ol>
                <li>Clone the repository:</li>
                <pre><code>git clone https://github.com/yourusername/chrome-password-recovery-tool.git</code></pre>
                <li>Open the Delphi project file (.dpr) in your Delphi IDE.</li>
                <li>Compile the project to generate the executable.</li>
                <li>Run the executable to start the tool.</li>
            </ol>

            <h2>Usage</h2>
            <p>1. Launch the application.</p>
            <p>2. The tool will automatically locate the Chrome profile directory and start scanning for saved passwords.</p>
            <p>3. The recovered passwords will be displayed in the tool's interface.</p>

            <h2>Contributing</h2>
            <p>Contributions are welcome! If you have any improvements or bug fixes, please fork the repository and submit a pull request.</p>

            <h2>License</h2>
            <p>This project is licensed under the MIT License. See the <a href="LICENSE">LICENSE</a> file for more details.</p>
        </article>
    </div>

    <footer class="footer">
        <p>&copy; 2024 Your Name. All rights reserved.</p>
    </footer>
</body>
</html>
