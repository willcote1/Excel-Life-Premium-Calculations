# Excel-Life-Premium-Calculations

# Actuarial Mortality & Premium Calculator

## Overview
This is an Excel-based project designed to showcase key actuarial and Excel skills. It utilizes real-world mortality data to calculate a monthly premium for a life insurance policy. The workbook demonstrates the application of fundamental actuarial concepts such as mortality and survival probabilities, present value calculations, and premium determination— all within the Excel interface.

- **Mortality Data:**  
  This sheet imports and cleans real-world mortality data (e.g., IRS 2016 Defined Benefit Static Mortality Tables) by age.

- **Premium Calculation:**  
  In this sheet, users input key assumptions:
  - **Age** (cell F2)
  - **Policy Length (in years)** (cell F3)
  - **Benefit Amount** (cell F4)
  - **Annual Interest Rate** (cell F5)

  The model then calculates for each policy year:
  - Updated age and corresponding mortality rates (using VLOOKUP and INDEX/MATCH).
  - The probability of death and survival.
  - Discount factors to account for the time value of money.
  - The present value of the expected death benefit for each policy year.

- **Premium Determination:**  
  The total present value of the death benefits is summed over the policy term, and the result is spread across the policy’s duration to arrive at a monthly premium. This premium represents the cost required to cover the actuarially expected benefit.

## Technical Skills Demonstrated
- **Actuarial Modeling:** Understanding of mortality tables, survival probabilities, and premium pricing.
- **Financial Analysis:** Use of present value calculations and discounting techniques.
- **Excel:** Proficiency with lookup functions, dynamic formulas, and data visualization.
- **Data Integration:** Importing and cleaning external data sources for actuarial analysis.

## How to Use
1. **Download or Open the Workbook:**  
   Open the Excel file in your preferred version of Microsoft Excel (compatible with Mac).

2. **Input User Data:**  
   Enter your age in cell F2, the policy length (in years) in cell F3, and the benefit amount in cell F4. Also, specify the annual interest rate in cell F5.

3. **Review Calculations:**  
   The workbook automatically populates the mortality, survival, and discount factors for each policy year. The final monthly premium is calculated by summing the present values of the expected benefits and dividing by the total number of months in the policy term.


