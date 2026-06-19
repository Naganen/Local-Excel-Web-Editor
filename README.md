# Local Web Excel Editor

A lightweight, local-first web application that allows you to manage multiple Excel files directly in your browser. It provides an intuitive sidebar navigation for files and their internal worksheets, along with a powerful grid interface for real-time data editing, type management, and row/column manipulation.

## 🚀 Features

* **Local-First Processing:** No backend, no API keys, and no server-side storage. All data is processed locally in your browser for maximum privacy.
* **Hierarchical Navigation:** Load multiple Excel files and manage them using a clean sidebar menu. Each file expands to show its worksheets as sub-menus.
* **Dynamic Data Editing:**
* Edit cell content directly in a spreadsheet-like interface.
* Change cell data types (String, Number, Date, Boolean) on the fly.
* Input fields automatically adapt to the selected data type.


* **Structural Control:** Easily add or remove rows and columns with a simple click.
* **Export Capabilities:** Download your modified work back as an `.xlsx` file with all changes preserved.

## 🛠 Tech Stack

* **HTML5/CSS3:** Responsive layout using Tailwind CSS.
* **JavaScript (Vanilla):** Logic for file handling and data manipulation.
* **SheetJS (xlsx):** Industry-standard library for reading and writing Excel files.
* **Lucide Icons:** Modern iconography for a sleek UI.

## 📦 How to Use

1. **Clone or Download:** Clone this repository to your local machine.
2. **Open:** Simply open the `index.html` file in any modern web browser (Chrome, Firefox, Edge).
3. **Upload:** Use the "Upload Files" area to drop your Excel files.
4. **Edit:**
* Select a file from the sidebar.
* Select a worksheet to load the data grid.
* Double-click any cell to edit its content or change its data type.
* Use the toolbar to add rows/columns or delete selected data.


5. **Save:** Click the "Download" button to save your changes to your local machine.

## 📋 Project Structure

```text
/
├── index.html       # Main application interface and logic

```

## ⚠️ Important Notes

* **Data Privacy:** This application performs all operations client-side. No data is sent to external servers. Your files remain on your computer.
* **Browser Support:** Please use a modern, up-to-date web browser to ensure full compatibility with the File System and Web APIs used.

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.
