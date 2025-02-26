# ZeotapAssignment1
# Web Application Mimicking Google Sheets  
A web-based spreadsheet application built using **HTML, CSS, and JavaScript** that provides functionalities similar to Google Sheets, including data entry, formatting, mathematical calculations, and file operations.

Our site is live at https://smitananaware.github.io/ZeotapAssignment1/


## 🚀 Features  
✔️ **Spreadsheet Interface** – Rows, columns, and a toolbar for formatting.  
✔️ **Mathematical Functions** – Support for basic arithmetic operations.  
✔️ **Data Quality Functions** – Validation, error handling, and input restrictions.    
✔️ **Row/Column Management** – Insert, delete, and resize rows/columns.  
✔️ **Chart Generation** – Visual representation of data.  
✔️ **File Operations** – Save and load spreadsheets as `.xlsx` files.  

## 🏗️ Tech Stack & Why It Was Chosen  

| Technology | Purpose | Why? |
|------------|---------|------|
| **HTML** | Structure & UI | Provides the base for table structure, toolbar, and input elements. |
| **CSS** | Styling & Layout | Ensures a clean, user-friendly spreadsheet-like appearance. |
| **JavaScript** | Functionality & Event Handling | Enables dynamic cell editing, formulas, and user interactions. |
| **Chart.js** | Data Visualization | Allows users to generate bar, line, and pie charts dynamically. |
| **SheetJS (xlsx.js)** | File Operations | Facilitates saving/loading spreadsheets as `.xlsx` files instead of JSON. |

---
## 📂 Data Structures & Why They Were Used  

| Data Structure | Purpose | Why? |
|---------------|---------|------|
| **2D Array (`Array[][]`)** | Stores spreadsheet cell data | Provides a grid-like structure for rows and columns, making data access efficient. |
| **Object (`{}` for Cell Metadata)** | Stores cell properties (bold, color, formulas) | Keeps track of formatting and formula-related properties for each cell. |
| **Event Listeners** | Captures user actions | Handles real-time interactions like cell edits, formula inputs, and chart generation. |
| **Stack (`Undo/Redo`)** | Implements Undo/Redo functionality | Maintains previous states of the spreadsheet, allowing users to revert changes. |

---
## 📝 Usage
1. Enter data in the cells just like in Google Sheets.
2. Use the toolbar for formatting (bold, italics, color).
3. Perform calculations by clicking mathematical functions.
4. Apply Data Quality Functions.
5. Click the "Generate Chart" button to create a visual representation of selected data.
6. Save your spreadsheet as an Excel file using the "Save" button.
7. Load a previously saved file using the "Load" button.
   
## 📦 Installation  

1. Navigate to the project directory:
    ```bash
    cd Web-Application-Mimicking-Google-Sheets
2. Open index.html in a browser to run the application.