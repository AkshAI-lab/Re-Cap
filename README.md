# Cost Calculator

A simple web-based calculator to compute the total cost of a project based on the work portion cost and various additional charges (royalty, material testing, GST, labour insurance, contingency, PMC charges, and escalation).

---

## Features

- **Input Work Portion Cost**: Enter the base cost of the project.
- **Dynamic Labour Insurance**: Automatically calculates labour insurance based on the work portion cost:
  - 0.5% if the work portion cost is ≤ ₹25 lakh.
  - 1% if the work portion cost is > ₹25 lakh.
- **Customizable Percentages**: Adjust percentages for royalty, material testing, GST, contingency, PMC charges, and escalation.
- **Real-Time Calculation**: Instantly calculates and displays the total cost.

---

## How to Use

1. Open the `cost-calculator.html` file in a web browser.
2. Enter the **Work Portion Cost** in the input field.
3. Adjust the percentages for the following factors (if needed):
   - Royalty
   - Material Testing Charges
   - GST
   - Labour Insurance
   - Contingency
   - PMC Charges
   - Escalation
4. Click the **Calculate Total Cost** button.
5. The total cost will be displayed below the button.

---

## Code Structure

- **HTML**: The structure of the calculator is defined in the `cost-calculator.html` file.
- **CSS**: Styling for the calculator is included in the `<style>` tag within the HTML file.
- **JavaScript**: The calculation logic is implemented in the `<script>` tag within the HTML file.

---

## Hosting Instructions

You can host this project for free using one of the following platforms:

### 1. GitHub Pages
1. Create a GitHub repository.
2. Upload the `cost-calculator.html` file to the repository.
3. Enable GitHub Pages in the repository settings.
4. Your website will be live at:
