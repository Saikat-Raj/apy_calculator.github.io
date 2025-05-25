# Atal Pension Yojana (APY) Calculator

A comprehensive web-based calculator for the Atal Pension Yojana (APY), a government-backed pension scheme in India. This tool helps users calculate their pension contributions, returns, and XIRR (Extended Internal Rate of Return) based on various parameters.

## Features

### Core Functionality
- **Contribution Calculator**: Calculate monthly, quarterly, or half-yearly contributions
- **Return Analysis**: Comprehensive analysis of pension returns including self and nominee benefits
- **XIRR Calculation**: Advanced financial metric calculation for investment performance
- **Nominee Support**: Include nominee benefits in calculations with flexible options

### User Interface
- Clean, responsive design that works on desktop and mobile devices
- Real-time input validation with error messages
- Interactive form with conditional fields
- Professional styling with modern UI components

## How to Use

### Access the Calculator
- **Online Access**: Visit [https://saikat-raj.github.io/apy_calculator.github.io/](https://saikat-raj.github.io/apy_calculator.github.io/)
- No installation or download required
- Works directly in your web browser
- Compatible with desktop and mobile devices

### Input Parameters

#### Required Fields
- **Starting Age**: Your age when joining APY (18-40 years)
- **Contribution Frequency**: Choose from Monthly, Quarterly, or Half-yearly
- **Pension Amount**: Select desired monthly pension (₹1,000 to ₹5,000)
- **Expected Age of Death**: Your expected lifespan for calculation purposes

#### Optional Fields
- **Include Nominee**: Add nominee to receive benefits after your death
- **Nominee Lumpsum**: Choose between lumpsum payment or continued pension for nominee
- **Nominee Details**: Age and expected lifespan of nominee (if continuing pension)

### Calculation Results

The calculator provides comprehensive results including:

- **Minimum Guaranteed Pension**: Monthly pension amount
- **Vesting Period**: Years from enrollment to pension start (age 60)
- **Total Contribution**: Total amount you'll pay during vesting period
- **Total Recovery (Self)**: Amount you'll receive during your lifetime
- **Total Recovery (Nominee)**: Amount nominee will receive
- **Recovery Ratio**: Total recovery divided by total contribution
- **XIRR**: Internal rate of return for your investment

## APY Scheme Overview

### What is Atal Pension Yojana?
- Government-backed pension scheme launched in 2015
- Guaranteed minimum pension of ₹1,000 to ₹5,000 per month
- Available for Indian citizens aged 18-40
- Pension starts at age 60

### Key Benefits
- **Guaranteed Returns**: Government-backed minimum pension guarantee
- **Tax Benefits**: Contributions eligible for tax deduction under Section 80CCD
- **Nominee Benefits**: Spouse can continue receiving pension or take lumpsum
- **Low Risk**: Minimal market risk due to government guarantee

### Eligibility Criteria
- Indian citizen aged 18-40 years
- Valid bank account
- Aadhaar number
- Mobile number linked to bank account

## Technical Details

### Calculation Methodology
- **Contribution Amounts**: Based on actuarial calculations for different age groups
- **XIRR Calculation**: Uses bisection method for accurate internal rate of return
- **Age-based Scaling**: Contribution amounts increase with entry age
- **Nominee Calculations**: Accounts for different nominee scenarios

### Browser Compatibility
- Works on all modern browsers (Chrome, Firefox, Safari, Edge)
- Responsive design for mobile and tablet devices
- No external dependencies required

### Data Simulation
The calculator uses simulated APY data that closely matches official government rates:
- Age-based contribution scaling
- Frequency-based adjustments
- Realistic lumpsum amounts for nominees

## Validation and Error Handling

The calculator includes comprehensive validation:
- **Age Limits**: Starting age must be 18-40 years
- **Death Age**: Must be greater than 60 years
- **Nominee Logic**: Validates nominee death age scenarios
- **Input Sanitization**: Ensures all inputs are within valid ranges

## Example Scenarios

### Scenario 1: Basic Calculation
- Starting Age: 25 years
- Frequency: Monthly
- Pension Amount: ₹3,000
- Death Age: 75 years
- No Nominee

### Scenario 2: With Nominee (Lumpsum)
- Same as above plus:
- Include Nominee: Yes
- Nominee takes lumpsum: Yes

### Scenario 3: With Nominee (Continued Pension)
- Same as Scenario 1 plus:
- Include Nominee: Yes
- Nominee takes lumpsum: No
- Nominee current age: 22 years
- Nominee death age: 78 years

## Financial Disclaimer

This calculator is for educational and planning purposes only. Actual APY rates and benefits may vary based on:
- Government policy changes
- Actuarial adjustments
- Market conditions
- Individual circumstances

Always consult with financial advisors and refer to official government sources for the most current APY information.


## Contributing

To improve this calculator:
1. Update contribution rates based on latest government notifications
2. Add new features like inflation adjustment
3. Enhance UI/UX design
4. Add more detailed financial analysis

---

*Note: This calculator uses approximated data for demonstration purposes. For official APY enrollment and accurate calculations, please consult authorized financial institutions or government sources.*
