<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pharmacy Management System</title>
</head>
<body>

<h1>Pharmacy Management System</h1>

<p>The <strong>Pharmacy Management System</strong> is a software application developed in R, designed to efficiently manage and track various aspects of a pharmacy's operations. This system enables users to handle inventory, manage drug sales, monitor expiry dates, add and manage workers, and track electricity usage. It is a comprehensive solution that aids in maintaining a well-organized pharmacy environment.</p>

<h2>Features</h2>

<h3>Add Drug (<code>pms</code>)</h3>
<ul>
    <li>Adds new drugs to the inventory.</li>
    <li>Includes validation for manufacturing dates and negative values.</li>
</ul>

<h3>Display Inventory (<code>disp</code>)</h3>
<ul>
    <li>Shows current inventory data.</li>
</ul>

<h3>Bar Graph of Quantity Available (<code>dispg</code>)</h3>
<ul>
    <li>Visualizes the inventory levels with a bar graph.</li>
</ul>

<h3>Read from CSV File (<code>reading</code>)</h3>
<ul>
    <li>Reads pharmacy data from a CSV file and displays it.</li>
</ul>

<h3>Sell Drug (<code>sell_drug</code>)</h3>
<ul>
    <li>Sells drugs and updates inventory.</li>
    <li>Calculates total price before and after discounts.</li>
</ul>

<h3>Check Low Stock (<code>check_low_stock</code>)</h3>
<ul>
    <li>Alerts users about drugs with a quantity less than 10.</li>
</ul>

<h3>Search Drug (<code>search_drug</code>)</h3>
<ul>
    <li>Searches and displays information about a specific drug.</li>
</ul>

<h3>Check Expiry Dates (<code>check_expiry_dates</code>)</h3>
<ul>
    <li>Lists all drugs that have expired.</li>
</ul>

<h3>Delete Drug (<code>delete_drug</code>)</h3>
<ul>
    <li>Removes a drug from the inventory.</li>
</ul>

<h3>Drug Comparison (<code>compare_drug_sales</code>)</h3>
<ul>
    <li>Compares and identifies the drug(s) that sold the most.</li>
</ul>

<h3>Add Worker (<code>add_worker</code>)</h3>
<ul>
    <li>Adds new workers to the system.</li>
</ul>

<h3>Display Workers (<code>display_workers</code>)</h3>
<ul>
    <li>Shows the list of workers.</li>
</ul>

<h3>Add Electricity Data (<code>add_electricity</code>)</h3>
<ul>
    <li>Records electricity usage data for tracking.</li>
</ul>

<h3>Display Electricity Data (<code>display_electricity</code>)</h3>
<ul>
    <li>Displays electricity usage data for the past year.</li>
</ul>

<h3>Save Workers Data (<code>save_workers_data</code>)</h3>
<ul>
    <li>Saves worker data to a file.</li>
</ul>

<h2>Learning Outcomes</h2>
<p>By using this system, students will learn:</p>
<ul>
    <li><strong>Data Manipulation:</strong> Adding, deleting, and managing inventory data.</li>
    <li><strong>File Handling:</strong> Reading from and writing to CSV files.</li>
    <li><strong>Data Visualization:</strong> Creating bar graphs to display inventory levels.</li>
    <li><strong>Functions and Conditionals:</strong> Implementing functions with condition checks (e.g., expiry dates, low stock alerts).</li>
    <li><strong>Practical Application:</strong> Applying programming skills in a real-world scenario to manage and analyze pharmacy data.</li>
</ul>

<h2>Target Audience</h2>
<p>This module is designed for:</p>
<ul>
    <li><strong>Pharmacy Managers:</strong> For efficient management of pharmacy operations.</li>
    <li><strong>Pharmacists and Staff:</strong> To keep track of inventory, sales, and compliance.</li>
    <li><strong>Students:</strong> Particularly those studying engineering or related fields interested in database management and software development.</li>
</ul>

<h2>Future Enhancements</h2>
<ul>
    <li>Integration with a billing system for automated invoicing.</li>
    <li>User authentication and access control.</li>
    <li>Enhanced reporting and analytics features for comprehensive data analysis.</li>
</ul>

<h2>Conclusion</h2>
<p>The Pharmacy Management System provides a user-friendly interface and essential functionalities to manage a pharmacy's operations effectively. It is a valuable tool for both educational purposes and real-world applications in pharmacy management.</p>

</body>
</html>
