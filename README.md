DFC Bank Statement Automation

Automates IDFC NetBanking tasks including logging in, downloading account statements, extracting transaction data, generating logs, and emailing processed results.
Built for fast, accurate, and fully unattended financial automation.

✅ Features

Automated login to IDFC Internet Banking

Automatic monthly statement download

PDF/OCR-based transaction extraction

Clean parsing of Date, Description, Amount, Type, Balance

Log creation for every automation run

Email dispatch of extracted data using SMTP

Config-driven architecture (credentials, paths, email settings)

✅ Tech Stack

Java

Selenium

Apache PDFBox 

Jakarta Mail

Maven

Linux-compatible

✅ Folder Structure
project/
│── src/main/java/...
│── src/main/resources/
│── logs/
│── downloads/
│── pom.xml
│── README.md
config.properties

✅ Setup Instructions




Update config.properties with:

IDFC credentials

Folder paths

Email properties

Install dependencies:

mvn clean install


Run the automation:

java -jar target/IDFC_Automation.jar

✅ How It Works

Logs in to IDFC NetBanking via Selenium

Navigates to the statement download section

Downloads the latest PDF

Extracts data using PDFBox

Logs results

Sends email containing transaction details / logs

✅ Use Cases

Automatic reconciliation

Financial reporting

Email-based transaction notifications

Daily/weekly scheduled jobs (cron)

✅ Disclaimer

This project is for educational and internal automation use only.
Do not use it to access accounts without authorization
