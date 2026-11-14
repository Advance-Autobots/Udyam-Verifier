# Udyam Verifier

Python + Selenium tool to bulk verify Udyam Registration numbers from an Excel file. It opens the Udyam portal, shows each captcha in an always-on-top pop-up for manual entry, extracts the enterprise name, Udhyam number, activity, year and type into Excel, saves each verification page as a PDF, and logs invalid numbers.

# Features

- Reads Udyam numbers and vendor names from an Excel file
- Automatically navigates to **Verify Udyam Registration**
- Shows the captcha in a window with a textbox and OK button (press Enter to submit)
- Re-displays the captcha if the entered code is wrong
- Extracts **Enterprise Name, Udhyam Number, Activity, Year and Type** into an output Excel file
- Saves the verification page as a **PDF named after the vendor**
- Saves invalid Udyam numbers to `invalidnumber.txt`
- Saves the output Excel after every record, so nothing is lost if the script stops

## Requirements

Python - 3.15 or higher

### Python libraries

selenium,
openpyxl,
pillow
