# [TaxProjection.com (Tax Projection Individual Application)](https://taxprojection.com)

## Technical Documentation :memo:

### Tax Types

#### Included

- Ordinary Tax
- Capital Gains Tax
- Self-Employment Tax

#### Not Included

- Alternative Minimum Tax
- Net Investment Income Tax
- Additional Medicare Tax
- MCTMT Tax

### Jurisdictions Included

- Federal
- States with no income tax
- New York
- New York City

### What Are Quarterly Estimated Taxes?

Generally there are two options when you need to pay your quarterly estimated taxes, Actual and Safe Harbor. **You may pay the lesser of the two options.** If you do not pay quarterly estimated taxes you could be subject to interest and penalties.

1. Option 1 - Actual Tax Method
   When paying estimated taxes to the IRS you must pay 90% of the current tax year's estimated tax. This is broken down into quarters, so you must pay 90% of the tax of the current quarter's estimated taxable income (Note, some states differ on the percentage). However, you should annualize income per quarter so that you are using the correct effective tax rate based on your tax bracket.

2. Option 2 - Safe Harbor Tax Method
   The second option is to pay your estimated taxes based on the Safe Harbor Method. The Safe Harbor Method is based on paying 100% (110% if above AGI threshold) of the prior year's tax per quarter. Essentially you would be paying 25% of 100% of the prior year's tax per quarter (Note, some states differ on the percentage). This option is simpler and much less time consuming than the Actual Tax Method. However, a few downsides are if you are projected to make less money in the current year than the prior year, you would be overpaying your tax. In addition, if tax is similar, 100% using the Safe Harbor Method is larger than 90% using the Actual Method. Safe Harbor is recommended if you are projected to have a larger tax balance in the current year compared to the prior year.

There are many factors to consider when choosing between the Actual Tax Method and the Safe Harbor Method. Another item to note is you can change between methods every quarter. For example, income was projected to be very high in quarter 1 so you decided to use the Safe Harbor Method to pay your first quarter estimates. In quarter 2, income was projected to be a lot lower than anticipated, you could then decide to use the Actual Method for the second quarter.

### Other Notes

- If you wish to turn annualization off, click the button to the far right of the respective line item in the input section. Short-term capital gains/(losses) and long-term capital gains/(losses) have annualization turned off by default.
- Short-Term and Long-Term Capital Losses are limited to -$3,000
- Tax projection is currently using 2023 tax rates

### Line By Line Instructions

#### Navigation Bar

- Documentation: Links to the technical documentation page. If you are reading this, you are already here!
- Contact: Links to Russell's contact information. Send him a message!
- Info: General information & disclosure about the web application
- Login: Create an account to login and save clients. Once logged in the Profile Button will appear which contains the following.
  - Profile: Gives user information and a list of all of the user's saved clients with name and Id. This is helpful if a user forgets a client's name or Id and needs to use the other login functions.
  - Save: Save clients for use in the future.
  - Load: Load clients.
  - Delete: Delete clients.
  - Logout: Sign out.

##### Client Title Box

Input the NAME and ID of the intended client. This is needed to be able to save a client.

#### Tax Assumptions

This section is where one must choose the specific tax assumptions that are used to calculate the specific tax.

- Quarter: There are 4 quarters. Choose the respective quarter that is applicable. IRS quarters are from the following dates, Quarter 1 (1/1 to 3/31), Quarter 2 (4/1 - 5/30), Quarter 3 (6/1 - 8/31), and Quarter 4 (9/1 - 12/31).
- Filing Status: There are 4 options, Single, MFJ (Married Filing Joint), MFS (Married Filing Separate), HOH (Head Of Household)
- Standard/Itemized: Standard Deduction is the default deduction while Itemized Deduction is an aggregate of multiple expenses which are limited according to specific thresholds and limitations. Some of them are medical expenses, charitable contributions, SALT (State And Local Taxes), interest expense including mortgage interest expense, and others.
- Dependents: Number of dependents that the taxpayer has. This includes children, certain relatives, and others.
- State Residency: Choose state of residency. At this time this tax projection application is limited in its number of choices.
- Safe Harbor Comparison: This allows the safe harbor comparison to be included in the calculation. See information and explanation above. [What Are Quarterly Estimated Taxes?](https://github.com/russelltheprogrammer/tax-projection-individual-docs#what-are-quarterly-estimated-taxes)

#### Input Numbers

It is recommended to start here to learn more about line numbers. Instructions can change from year to year. [IRS 1040 Instructions 2022](https://www.irs.gov/pub/irs-pdf/i1040gi.pdf)

##### INCOME

- Wages (W-2): This is wage income. Check your most recent pay-stub for needed information.
- Interest: This is interest income. This is usually earned from loans, bank accounts, and brokerage accounts.
- Ordinary Dividends: This is usually earned from brokerage accounts or corporations.
- Qualified Dividends: These are dividends that have a beneficial tax treatment. These should be separated from Ordinary Dividends.
- Retirement Income: Income earned from retirement. Exclusions not included for different types of retirement income such as Social Security.
- Short-Term Capital Gains/(Losses) - Capital gains and losses are usually earned by the sale of stocks but there are many other varieties of assets that can be sold as a capital gain or loss. Short-term specifically has a holding period of less than a year.
- Long-Term Capital Gains/(Losses) - Capital gains and losses just like Short-Term except the holding period is greater than a year. Long-Term has a beneficial tax treatment.
- Business Income (Schedule C): Net income (income less expenses) earned through a business. Business income is subject to self-employment tax. The rules behind business income is complicated.
- Other Income: Other income not listed above.

##### ADJUSTMENTS

- HSA Contributions: Contributions to Health Savings Accounts. This is limited and the limit is different according to Filing Status.
- S/E Insurance: Self-Employed Health Insurance. This is health insurance that that can be deducted if you are self-employed. It is limited according to Business Income (Schedule C).
- Retirement Deduction: There are many different types of retirement deductions and some are more limited then others to what is allowed to be deducted.
- Student Loan Interest: Interest expense related to student loans. This deduction is limited to a certain threshold and phases out once a certain AGI level is met.
- Other Adjustments: Other adjustments not listed above.

##### ITEMIZED DEDUCTIONS

##### FEDERAL OTHER

##### STATE OTHER

##### OTHER TAXES

##### FEDERAL TAX PAYMENTS

##### STATE TAX PAYMENTS

## More Features? :bulb:

In the future, I plan to make a more advanced version of the application. However, I build this application all by myself and I have limited time capacity. There are a lot of additional features I would have liked to add to make this application more accurate and more functional, including adding additional scenarios, more jurisdictions, and the list goes on...

If you have a specific feature requests? Please let me know.

## Feedback?

Let me know! I would love to know what you think.

If you see any bugs, please let me know.

## Connect With Me :mailbox:

LinkedIn: [https://www.linkedin.com/in/russell-monteith-cpa-0a43975a/](https://www.linkedin.com/in/russell-monteith-cpa-0a43975a/)

My Github Homepage: [https://github.com/russelltheprogrammer/](https://github.com/russelltheprogrammer)

## About :mega:

I developed this application entirely from scratch, encompassing the entire process from idea generation to conceptualization and designing the user interface. Throughout the development, I relied solely on my own skills and expertise, without resorting to tutorials, templates, or boilerplate code.

This application was created based on how a tax accountant and a programmer think, trying to create the best user experience from the knowledge of both. It is worth noting that this application is not something a tax accountant or a programmer could construct by them-self. It necessitates a deep understanding of both disciplines to bring it to fruition.

The creation of this project was driven by my desire to enhance my programming abilities and to derive personal satisfaction from merging my interests in programming and tax accounting. As I continue to expand and add more features, the complexity of the project grows, requiring meticulous attention. To simplify the application, I employed Redux to streamline the management of global state. However, the intricate nature of the tax codes in the United States and various States introduces additional challenges. Nevertheless, I am enthusiastic about the development of this application and embrace any obstacles that come my way.

The primary purpose of this application is to assist individuals and accountants in estimating quarterly taxes for them-self or their clients. Given the complexity of the United States and State tax codes, not everyone can afford the services of a high-end tax accountant. Hence, my aim is to make this application accessible to freelancers, CPAs, EAs, accountants, and others.

In developing this application, I had to make choices regarding the level of complexity to incorporate. Constructing a comprehensive tax projection application, accounting for every intricate detail, is an arduous and time-consuming task. The intricate nature of the United States and State tax codes further exacerbates this challenge. Hence, I had to strike a balance between the time investment and the complexity involved in building the application. It seems to resemble a problem of Big O Notation (a little coding joke) in terms of optimizing efficiency...

## Key Concepts Used

- MERN STACK
- Redux
- Javascript
- Typescript
- Custom Functions
- Custom CSS
- React components
- React hooks
- Handle onClick and onChange Functions
- Bootstrap
- Material UI
- MongoDB
- Mongoose
- Express.js
- Node.js
- Auth0
- And much more

## Version - Latest Release Notes :rocket:

**Current version: 1.3.2**

### Release Notes Log

07/13/23 1.3.2

- Numbers will turn red if they are negative in Input Numbers Section

07/12/23
Version 1.3.1

- Removed operation sign button in Input Numbers Section
- Input in Input Numbers Section will now be strings for better user experience
- Input Numbers section no longer has a Submit Button. All numbers are automatically updated in the INCOME, DEDUCTION, AND TAX SUMMARY Section
- Highlighting of numbers as red in Input Numbers Section removed. Will be added back as soon as possible in next update.

07/11/23
Version 1.3.0

- Add safe harbor and comparison feature
- Moved documentation to its own repo
- Refactored portion of codebase to make more legible
- Added migration backend feature for future database changes

06/27/23
Version 1.2.2

- Added a reset button to the Tax Assumptions box

06/26/23
Version 1.2.1

- Changed layout of input numbers to a grid system

06/26/23
Version 1.2.0

- Added ability to annualize certain payments
- Changes to backend & frontend data types and structures

06/23/23
Version 1.1.0

- Added button to hide -0- rows in the "Income, Deduction, and Tax Summary"
- State columns will now be hidden when not in use

06/20/23
Version 1.0.0 is now live!

## Disclosure: :rotating_light:

Although I do believe this tax projection to be accurate and I have tested it for bugs do not rely upon this to estimate your own taxes. Taxes are complicated and this projection does not include all tax scenarios. Please consult a tax professional while using this application.
