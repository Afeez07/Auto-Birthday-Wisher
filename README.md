# Auto-Birthday-Wisher

This script automates the process of sending birthday greetings. It reads birthday information from a CSV file, selects a random message template, and sends personalized emails to the birthday person.

## Getting Started

### Prerequisites

* Python 3.12
* `pandas` library (install with `pip install pandas`)

### Installation

1.  Clone the repository:

    ```bash
    git clone [https://github.com/Afeez07/Auto-Birthday-Wisher]
    ```

2.  Navigate to the project directory:

    ```bash
    cd Auto-Birthday-Wisher
    ```

3.  Create a `birthdays.csv` file with the following format:

    ```csv
    name,email,year,month,day
    John Doe,JohnDoe@email.com,1990,1,15
    Jane Smith,JaneSmith@email.com,1985,3,20
    ```

4.  Create a `letter_templates` folder with at least three text files named `letter_1.txt`, `letter_2.txt`, and `letter_3.txt`. Each file should contain a birthday message template with `[NAME]` as a placeholder for the birthday person's name.

5.  Update the following variables in the Python script:

    * `MY_EMAIL`: Your email address.
    * `MY_PASSWORD`: Your email password.
    * `YOUR SMTP EMAIL PROVIDER`: Your email provider's SMTP server address (e.g., `smtp.gmail.com`).

6.  Run the program:

    ```bash
    python main.py
    ```

### Important Notes:

* You might need to enable "less secure app access" or generate an "app password" in your email account settings for the script to work.
* Be mindful of email sending limits to avoid your account being flagged.

### Contributing

Feel free to contribute to Auto-Birthday-Wisher by:

* Adding more message templates.
* Implementing error handling.
* Adding support for other email providers.
* Adding a feature that allows the user to set how many days before a birthday to send a warning email.
