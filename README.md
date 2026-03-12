# FITCoinTestCases

This repository contains the test cases and execution scripts for our homework assignment.

**⚠️ CRITICAL REQUIREMENT:** To ensure your environment matches the grading environment, all testing **must** be done on the Florida Tech `code01` server. Running these tests on your local machine may yield inaccurate results.

## 🚀 Getting Started

If you haven't already cloned this repository to your `code01` workspace, do that first.

If you already have the repository cloned and just need to fetch the latest test cases or updates, navigate to the repository directory and pull the latest changes:

```bash
# Navigate to your project folder
cd /path/to/your/repo

# Clone the latest test cases
git clone https://github.com/Suave101/FITCoinTestCases.git

```

## 🧪 Running the Tests

Make sure your homework source files are located in the same directory as the test scripts before running them.

### Standard Assignment Tests

To run the standard test cases for the main homework assignment, execute the main test script:

```bash
bash test.sh
```

This script will compile your code (if applicable), run it against the provided test inputs, and output your results compared to the expected outputs.

### Extra Credit Tests

If you attempted the extra credit portion of the assignment, there is a separate script to validate your extra credit file. Run the following command:

```bash
bash ecTest.sh
```

## 🛠️ Troubleshooting

* **"Command not found" or "Permission denied":** If bash complains about permissions, you can try granting execution rights to the scripts by running `chmod +x test.sh ecTest.sh`, then run them using `./test.sh` and `./ecTest.sh`.
* **Wrong Server:** If you get strange environment errors, double-check that you are actually SSH'd into `username@code01.fit.edu` and not your local terminal.
* **Missing Files:** Ensure your assignment files are named exactly as specified in the homework instructions, as the bash scripts are likely looking for those specific filenames.
