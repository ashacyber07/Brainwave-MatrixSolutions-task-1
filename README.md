# Brainwave-MatrixSolutions-task-1
Build a Python Cyber Security - Phishing Link Scanner


# 📝 Project Description
  This project is a simple Phishing Link Scanner built using Python. It analyzes given URLs to detect potential phishing threats using:
  * Pattern matching
  * Keyword analysis
  * WHOIS domain data

# 📁 File Structure
phishing_link_scanner/
├── phishing_scanner.py       # Main scanner script
├── test_urls.txt             # Sample URLs for testing
├── README.md                 # Project documentation

📜 phishing_scanner.py

📂 test_urls.txt


⚙️ How It Works
 1.Regex Matching is used to detect:
    IP-based URLs
    URLs with suspicious keywords
    Shortened URLs
 2.WHOIS Lookup (optional): The domain creation date is fetched for further threat scoring.

 # ▶️ How to Run
  1. Install required package
    *cmnd - pip install python-whois
  2.Create files
    * Save the Python code in phishing_scanner.py
    * Add test URLs to test_urls.txt
  3.Run the script
     * python phishing_scanner.py
  4.Output
     [https://bit.ly/login-fake] => ⚠️ Suspicious 
     [http://192.168.0.1/verify] => ⚠️ Suspicious

# 📊Conclusion
  * This scanner helps:
  * Detect malicious patterns in links
  * Alert users before clicking on harmful URLs
  * Provide basic analysis for cyber threat awareness

# ✅Future Improvements
  * Integrate with VirusTotal API
  * GUI interface
  * Export results to CSV or JSON
  * Add threat scoring system



