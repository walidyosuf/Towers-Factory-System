Tower Manufacturing Management System
A comprehensive, web-based management solution designed specifically for the tower manufacturing industry (66KV, 220KV, 500KV, and Telecom). This system streamlines the production lifecycle from model database management to daily production tracking and reporting.

🚀 Key Features
Models Database: Maintain a central repository of tower models. Upload Excel files containing item specifications (Item Name, Section, Steel Grade) and automatically process operational sequences.

Work Order Management: Create and track work orders tied to specific projects and sales orders. Automatically import operational steps from the model database and track quantities and weights.

Daily Production Tracking: Log daily output by shift, machine, and operator. The system features a "smart" input form that remembers preferences (Machine, Operator, Shift) to speed up data entry.

Interactive Dashboard: Real-time visualization of active work order progress, daily completion statistics, and pending operations.

Reporting & Exports: Generate detailed PDF reports and Excel exports for work order status and production history.

Data Security: Built-in backup and restore functionality to safeguard your manufacturing data.

🛠️ Built With
Frontend: HTML5, Tailwind CSS (for modern, responsive UI).

Libraries:

SheetJS (XLSX): For processing Excel uploads and exports.

jsPDF & jsPDF-AutoTable: For generating high-quality PDF reports.

Font Awesome: For professional iconography.

Google Fonts (Inter): For clear typography.

📂 Project Structure
index.html: The core single-page application containing the UI structure and business logic.

Sections:

dashboardSection: Overview of manufacturing KPIs.

modelsSection: Management of tower types and item databases.

workOrderSection: Planning and tracking individual manufacturing orders.

productionSection: Recording daily floor activity.

📖 How to Use
Setup Database: Navigate to the Database tab and upload your tower models via Excel files. Ensure columns for "Item Name," "Section," and "Steel Grade" are present.

Create Work Order: Go to the Work Orders tab, select a model, and upload the specific quantities required for your project.

Log Production: As items are manufactured, use the Daily Production tab to select the machine and operator, then log the completed quantities for specific items.

Monitor & Report: Use the Dashboard for a quick glance at progress or the Reports tab for detailed analysis.

📱 Responsiveness
The system is fully responsive and optimized for:

Desktops: Detailed data entry and management.

Tablets/Mobiles: On-the-floor production logging and quick status checks.

🛡️ Data Management
The application supports:

Local Storage: Data persists in the browser's local storage.

Backup: Export your entire database to a file for safekeeping.

Clear Database: Reset the system for a new manufacturing cycle when needed.
