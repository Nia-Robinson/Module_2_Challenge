# Project Title: Loan Qualifier Application

This is a command line application to match applicants with qualifying loans.

---

## Technologies: Python 3, Visual Studio Code

Python 3 or later.

Visual Studio Code for IDE.

---

## Installation Guide: Install Python Fire and Python Questionary

Python Fire
![image](https://user-images.githubusercontent.com/34729547/178856360-f8e82761-3a82-4607-a106-2240011dee2b.png)

Python Questionary
![image](https://user-images.githubusercontent.com/34729547/178856302-7a89703f-1dc4-45c3-8128-0651d2e39df7.png)

---

## Usage: python app.py

def run():
    """The main function for running the script."""

    # Load the latest Bank data
    bank_data = load_bank_data()

    # Get the applicant's information
    credit_score, debt, income, loan_amount, home_value = get_applicant_info()

    # Find qualifying loans
    qualifying_loans = find_qualifying_loans(
        bank_data, credit_score, debt, income, loan_amount, home_value
    )

    # Save qualifying loans
    save_qualifying_loans(qualifying_loans)

---

## Contributors: Nia Robinson

LinkedIn: https://www.linkedin.com/in/niaelanrobinson/


---

## License

When you share a project on a repository, especially a public one, it's important to choose the right license to specify what others can and can't with your source code and files. Use this section to include the license you want to use.

