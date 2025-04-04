# UI-TESTING-GEN-AI


<br>
This project automates the extraction of UI elements from a website, generates corresponding test cases, and creates Selenium scripts for automation testing.
<br><br>
<br>
APPROACH:-
<br><br>
The project follows these three main steps:
<br><br>
1. Web Scraping:

Uses requests and BeautifulSoup to extract UI elements (buttons, links, input fields, and forms) and Saves extracted elements in elements.json.
<br><br>
2.Test Case Generation:

Reads elements.json and generates structured test cases and Saves test cases in test_cases.xlsx.
<br><br>
3.Selenium Script Generation:

Converts test cases into Python Selenium scripts for automation testing ans Saves scripts in test_scripts.xlsx.
<br><br><br>

CHALLENGES FACED:-<br><br>
1.Handling websites with dynamic content that require Selenium instead of simple HTTP requests.<br>

2.Ensuring valid element selection while generating test cases.<br>

3.Formatting Selenium scripts for better reusability.
<br><br><br>



HOW TO RUN THE SCRIPTS:-<br><br>
1.Run the following command in your terminal:  


pip install requests beautifulsoup4 openpyxl selenium webdriver-manager<br><br>
2.Run the main Python script:  python Task.py <br><br>
3.After execution, you will get the following files:
<br>
elements.json → Extracted UI elements from the website.
<br>
test_cases.xlsx → Automatically generated test cases.
<br>
test_scripts.xlsx → Selenium scripts to automate testing.

![image](https://github.com/user-attachments/assets/71625b72-5ecc-4c97-810c-28fb97df7bff)

![image](https://github.com/user-attachments/assets/e14c9473-2830-46ae-9225-035c88f5b9b1)







