# Screener Data Extraction Script

## Overview

This is a script to export the tickertape screener results. The extracted data is then formatted into a CSV file for easy analysis and download.


## Features

* **Robust Table Detection:**  The script repeatedly checks for the target table, ensuring it can handle dynamically loaded content.
* **Data Cleaning:** Removes non-printable characters and commas to ensure data integrity.
* **Customizable Delay:**  The 10-second countdown allows you to prepare the target webpage before extraction begins.
* **User-Friendly:** Provides clear messages and alerts in the console to guide the user.

## Usage Instructions

1. **Install (if needed):** This Script does not requires any external libraries or dependencies installation.
2. **Open Target Page:** Navigate to the webpage containing the table you want to scrape. Ensure the table is visible and loaded. Fully load all the data by clicking Load More if needed.
3. **Open Developer Tools and Console:**
    * **Chrome/Edge/Opera:** Right-click anywhere on the page and select "Inspect" or press `Ctrl+Shift+I` (Windows/Linux) or `Cmd+Option+I` (Mac). Then click on the "Console" tab.
    * **Firefox:** Right-click anywhere on the page and select "Inspect Element" or press `Ctrl+Shift+I` (Windows/Linux) or `Cmd+Option+I` (Mac). Then click on the "Console" tab.
    * **Safari:** Enable the Develop menu in Safari's preferences (if it's not already enabled). Then, right-click on the page and select "Inspect Element", or press `Cmd+Option+I`. Click on the "Console" tab.
4. **Run the Script:** Paste the script into the console and press `Enter`. 
5. **Wait for Countdown:** The script will initiate a 10-second countdown. During this time, make sure the relevant table is visible and fully loaded on your screen.
6. **Download CSV:** After the countdown, the script will extract the data, format it into a CSV, and automatically trigger a download for the file.

## Important Note

* **Disclaimer:** Web scraping should always be done responsibly and ethically. Be sure to review the terms of service of the target website before using this script.
* **Customization:** The selector `#screener-table table` is specific to the target table's ID.  If your table has a different structure, you'll need to modify this selector.

## Example

**Screenshot to illustrate the results of the script.**
![Screenshot Description](https://github.com/khosa76/exam/blob/main/Screenshot%20(155).png)

**Sample CSV output to illustrate the results of the script.**
![Screenshot Description](https://github.com/khosa76/exam/blob/main/Screenshot%20(156).png)


## Troubleshooting

You will not encounter with any issue tickertape update the site structure

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue with any suggestions or improvements.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
