# Tax-Calculator
## Challenge outline: Tax Calculator
Design a website that allows for tax calculation based on a users input.
![image](https://github.com/123Saikeerthi/Tax-Calculator/assets/99475756/6b5c8a87-9758-4ecd-9cfe-193cfdb93c92)
![image](https://github.com/123Saikeerthi/Tax-Calculator/assets/99475756/b883b2e4-80f0-4bc8-a062-4f1f2181d94f)
### References & Requirements

- The tax calculation works based on this formula -
    - Overall income (after deductions) under 8 (≤) Lakhs is not taxed.
        - Ex - if Gross Annual Income + Extra Income - Deductions =  6 Lakhs, no tax
        - if Gross Annual Income + Extra Income - Deductions =  9 Lakhs, tax
    - Income over 8 (>) Lakhs, the amount over 8 Lakhs is taxed at
        - 30% for people with age < 40
        - 40% for people with age ≥ 40 but < 60
        - 10% for people with age ≥ 60
        - Example
            - Age = 34, Income = 40 Lakhs, no deductions, tax = .3 * (40 - 8) = .3 * 32 = 9.6 Lakhs
- Do not restrict user from entering incorrect values like characters in the number fields
- Highlight a error icon to the right of the input field (shown as an example in above image as a circle with `!`). Hovering over it should show the error in a tooltip
- If no errors are present, dont show the error icon
- This should be present in all the number fields
- The age dropdown field should have 3 values -
    - <40
    - ≥ 40 & < 60
    - ≥ 60
    - If user has not entered this value and clicks on submit, show a error icon hovering over which should show that input field is mandatory
- Error icons should not be visible in the form by default.
- Clicking on submit should show a modal which would show the final values based on above calculations.

### Notes

- The assignment has to be done in HTML, CSS and Javascript. You can use Bootstrap and Jquery but no other library/design system is allowed.
- You're free to make assumptions, please make sure they are mentioned in the README.
- Design is for representation purposes only, you are free to modify it, but all the functionalities as shown in the design (and as listed in requirements) should be present.
- Make sure all edge cases are thought out throughly and handled.
  
### Screenshots of the test results
![Screenshot (46)](https://github.com/123Saikeerthi/Tax-Calculator/assets/99475756/9532774a-6395-432d-abec-4a9e448574e3)
![image](https://github.com/123Saikeerthi/Tax-Calculator/assets/99475756/d894fa0a-6171-47f8-b0de-abee2edb8e9b)
![Screenshot (45)](https://github.com/123Saikeerthi/Tax-Calculator/assets/99475756/ca41ff75-2133-405d-b25d-5a00f63be3d0)



