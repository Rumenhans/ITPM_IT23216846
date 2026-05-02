## Setup Instructions

### 1. Install Python Packages
cd into the folder and run the following command to install python packages:

```
pip install -U pip && pip install playwright openpyxl && playwright install
```

---

## How to Run the Automation

Run the following command in Terminal:

```
python3 IT23216846.py \
  --excel "/Users/rumenkaluhendiwala/Desktop/clonedrepo/ITPM_IT23216846/test_automation/IT23216846.xlsx" \
  --url "https://www.pixelssuite.com/chat-translator" \
  --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open
```

---