<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Password Manager Application</title>
</head>
<body>

    <h1>Password Manager Application</h1>

    <p>This is a simple password manager application built using Python and Tkinter. It allows users to generate secure passwords and store them along with website and email credentials.</p>

    <h2>Features</h2>
    <ul>
        <li><strong>Password Generation:</strong> Generate strong passwords using a combination of letters, numbers, and symbols.</li>
        <li><strong>Data Storage:</strong> Store website URLs, email addresses, and passwords securely.</li>
        <li><strong>Data Persistence:</strong> Data is stored locally in a JSON file (<code>data.json</code>), ensuring persistence across sessions.</li>
    </ul>

    <h2>Installation</h2>

    <p>To run the application locally, follow these steps:</p>

    <h3>Clone the Repository</h3>
    <pre><code>git clone https://github.com/adithor/password-manager.git<br>cd password-manager</code></pre>

    <h3>Install Dependencies</h3>
    <p>Ensure you have Python and pip installed. Then, install the required dependencies:</p>
    <pre><code>pip install -r requirements.txt</code></pre>

    <h3>Run the Application</h3>
    <p>Start the password manager application:</p>
    <pre><code>python password_manager.py</code></pre>

    <h2>Usage</h2>

    <ol>
        <li><strong>Generating Passwords:</strong>
            <ul>
                <li>Click on the "Generate Password" button to create a strong, random password.</li>
                <li>The generated password will be automatically populated in the password field.</li>
            </ul>
        </li>
        <li><strong>Saving Credentials:</strong>
            <ul>
                <li>Enter the website URL, email/username, and password.</li>
                <li>Click on the "Add" button to save the credentials securely in <code>data.json</code>.</li>
            </ul>
        </li>
        <li><strong>Viewing Stored Data:</strong>
            <ul>
                <li>The stored data can be found in <code>data.json</code> file in JSON format.</li>
            </ul>
        </li>
    </ol>

    <h2>File Structure</h2>
    <ul>
        <li><code>password_manager.py</code>: Main Python script containing the Tkinter GUI and functionality.</li>
        <li><code>data.json</code>: JSON file used for storing website credentials.</li>
    </ul>

    <h2>Dependencies</h2>
    <ul>
        <li>Python 3.x</li>
        <li>Tkinter (standard Python interface to the Tk GUI toolkit)</li>
        <li><code>json</code> (standard Python library for JSON manipulation)</li>
    </ul>

    <h2>Contributing</h2>
    <p>Contributions are welcome! If you have suggestions, improvements, or bug fixes, please fork the repository and create a pull request.</p>

    <h2>License</h2>
    <p>This project is licensed under the MIT License - see the <code>LICENSE</code> file for details.</p>

</body>
</html>


    
  
  
