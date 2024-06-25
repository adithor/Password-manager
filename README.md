<h1>Password Manager Application</h1>
This is a simple password manager application built using Python and Tkinter. It allows users to generate secure passwords and store them along with website and email credentials.

<h2>Features</h2>
1. Password Generation: Generate strong passwords using a combination of letters, numbers, and symbols.<br>
2. Data Storage: Store website URLs, email addresses, and passwords securely.<br>
3. Data Persistence: Data is stored locally in a JSON file (data.json), ensuring persistence across sessions.

<h2>Installation</h2>
To run the application locally, follow these steps:

Clone the Repository

git clone https://github.com/adithor/password-manager.git<br>
cd password-manager

<h3>Install Dependencies</h3>

Ensure you have Python and pip installed. Then, install the required dependencies:

pip install -r requirements.txt

<h3>Run the Application</h3>

<h3>Start the password manager application:</h3>

python password_manager.py


<h2>Usage</h2>

Generating Passwords:

Click on the "Generate Password" button to create a strong, random password.
The generated password will be automatically populated in the password field.

<h2>Saving Credentials:</h2>

Enter the website URL, email/username, and password.
Click on the "Add" button to save the credentials securely in data.json.

<h2>Viewing Stored Data:</h2>

The stored data can be found in data.json file in JSON format.

<h2>File Structure</h2>

1. password_manager.py: Main Python script containing the Tkinter GUI and functionality.
2. data.json: JSON file used for storing website credentials.

<h2>Dependencies</h2>

Python 3.x
Tkinter (standard Python interface to the Tk GUI toolkit)
json (standard Python library for JSON manipulation)


<b>Contributions are welcome! Please fork the repository and create a pull request if you have suggestions, improvements, or bug fixes.</b>

License
This project is licensed under the MIT License - see the LICENSE file for details.
