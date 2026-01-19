# 📊 HR Analytics Pro Dashboard

A modern, responsive, and standalone HR Analytics Dashboard built with vanilla JavaScript. This tool visualizes workforce metrics, attrition rates, and demographic distributions using interactive charts and dynamic data tables.

## 🚀 Features

* **Single-File Architecture:** No build steps, `npm` installs, or backend required. Just open the HTML file.
* **Data Import:** Drag-and-drop support for **CSV** and **Excel (.xlsx, .xls)** files.
* **Interactive Visualizations:**
    * Attrition by Department (Horizontal Bar).
    * Workforce Demographics (Area Chart).
    * Gender Distribution (Doughnut Chart).
    * Salary Analysis (Bar Chart).
* **Dynamic Filtering:** Filter data by Department, Role, Education, and Gender in real-time.
* **Dark Mode:** Built-in toggle for Light/Dark themes.
* **Data Export:** Export filtered datasets back to Excel with one click.
* **Responsive Design:** Fully optimized sidebar layout for desktop and mobile devices.

## 🛠️ Tech Stack

* **Core:** HTML5, CSS3 (CSS Variables), Vanilla JavaScript.
* **Visualization:** [Chart.js](https://www.chartjs.org/) (via CDN).
* **Data Parsing:** [SheetJS (xlsx)](https://sheetjs.com/) (via CDN).
* **Icons:** [FontAwesome](https://fontawesome.com/) (via CDN).
* **Fonts:** Inter (Google Fonts).

## 📂 How to Run

1.  Clone this repository or download the ZIP file.
2.  Locate the `index.html` file.
3.  **Double-click to open it** in any modern web browser (Chrome, Edge, Firefox, Safari).
4.  Click **"Load Sample Data"** to see the demo, or upload your own dataset.

## 📊 Data Structure Requirements

To use your own data, ensure your CSV or Excel file contains the following column headers (case-sensitive):

| Column Header | Description | Example |
| :--- | :--- | :--- |
| `EmployeeID` | Unique ID for the employee | `1024` |
| `Age` | Employee age | `29` |
| `Attrition` | "Yes" or "No" | `No` |
| `Department` | Department name | `Sales` |
| `JobRole` | Specific role title | `Manager` |
| `Education` | Education level | `Bachelor` |
| `Gender` | "Male" or "Female" | `Female` |
| `MonthlyIncome` | Numerical salary value | `5000` |
| `YearsAtCompany`| Numerical tenure value | `4` |

## 🎨 Customization

You can easily customize the color scheme by editing the CSS variables at the top of the `<style>` block in the HTML file:

```css
:root {
    --primary: #4f46e5;     /* Change your brand color here */
    --bg-body: #f3f4f6;     /* Background color */
}
