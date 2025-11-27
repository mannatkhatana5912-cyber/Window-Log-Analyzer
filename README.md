Windows Log Analyzer

A lightweight and efficient Windows Log Analyzer built using Python, designed to parse, filter, and analyze Windows log files directly from the Windows PowerShell environment.
This tool helps users quickly identify system issues, warnings, security events, and performance anomalies by providing well-structured insights from raw Windows logs.

🔧 Features

✔️ Parse Windows Event Logs (System, Application, Security, or custom .evtx / .log files)

✔️ Filter logs by date, event level, event ID, provider, keywords, etc.

✔️ Export results to CSV, TXT, or JSON

✔️ Highlight critical and warning events

✔️ Search logs for specific patterns (errors, keywords, timestamps)

✔️ Works directly from Windows PowerShell

✔️ Simple, modular Python code structure

📁 Project Structure
Windows-Log-Analyzer/
│── logs/                   # Optional: directory to store log files
│── output/                 # Analysis output files (CSV/JSON/TXT)
│── analyzer.py             # Main Python script
│── utils.py                # Helper functions (if you added them)
│── README.md               # Project documentation

🚀 Getting Started
1. Requirements

Make sure you have the following installed:

Python 3.8+

Windows PowerShell

Required Python libraries (if any used by your script), for example:

pip install pandas
pip install python-evtx

2. Clone the Repository
git clone https://github.com/your-username/Windows-Log-Analyzer.git
cd Windows-Log-Analyzer

3. Run the Analyzer

From PowerShell, execute:

python analyzer.py


You may also specify options depending on your script, for example:

python analyzer.py -f "C:\Windows\System32\winevt\Logs\System.evtx" -o output.csv

📊 Example Use Cases

🔍 Investigating system crashes

🔐 Monitoring security-related events

🛠 Troubleshooting application failures

📈 Analyzing performance and service logs

🕵️ Searching for specific event patterns or error messages
