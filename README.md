# 🧹 Digital Janitor: Automated File Organizer

A simple, customizable Python script that automatically organizes files in a target directory (like your Downloads folder) into categorized subfolders.

## ✨ Features

* **Configurable:** Easily define new categories and file extensions using a simple `config.json` file.
* **Safe:** Only operates on files in the specified directory, leaving other folders untouched.
* **Command Line Ready:** Supports a Command Line Interface (CLI) for flexible execution.

## 🚀 Getting Started

### Prerequisites

You need Python 3 installed on your system.

### Installation

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/YourUsername/Digital-Janitor.git](https://github.com/YourUsername/Digital-Janitor.git)
    cd Digital-Janitor
    ```

2.  **Configuration:**
    Open the **`config.json`** file and update the following line with the directory you want to organize:

    ```json
    "target_directory": "/path/to/your/Downloads" 
    ```
    You can also modify the `categories` dictionary to suit your needs.

### How to Run

You have two options to run the script:

#### Option 1: Using the Default Config Path

If you set the `target_directory` in `config.json`:

```bash
python file_organizer.py 
