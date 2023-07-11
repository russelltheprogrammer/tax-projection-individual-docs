# [TaxProjection.com (Tax Projection Individual Application)](https://taxprojection.com)

## Technical Documentation :memo:

### Tax Types

#### Included

+ Ordinary Tax
+ Capital Gains Tax
+ Self-Employment Tax

#### Not Included

+ Alternative Minimum Tax
+ Net Investment Income Tax
+ Additional Medicare Tax
+ MCTMT Tax

### Jurisdications Included

+ Federal
+ States with no income tax
+ New York
+ New York City


### What Are Quarterly Estimated Taxes?

Generally there are two options when you need to pay your quarterly estimated taxes, Actual and Safe Harbor. **You may pay the lesser of the two options.** If you do not pay quarterly estimated taxes you could be subject to interest and penalties.

1. Option 1 - Actual Tax Method
When paying estimated taxes to the IRS you must pay 90% of the current tax year's estimated tax. This is broken down into quarters, so you must pay 90% of the tax of the current
quarter's estimated taxable income (Note, some states differ on the percentage). However, you should annualize income per quarter so that you are using the correct effective tax rate based on your tax bracket.

2. Option 2 - Safe Harbor Tax Method
The second option is to pay your estimated taxes based on the Safe Harbor Method. The Safe Harbor Method is based on paying 100% (110% if above AGI threshold) of the prior year's tax per quarter. Essentially you would be paying 25% of 100% of the prior year's tax per quarter (Note, some states differ on the percentage). This option is simpler and much less time consuming than the Actual Tax Method. However, a few downsides are if you are projected to make less money in the current year than the prior year, you would be overpaying your tax. In addition, if tax is similar, 100% using the Safe Harbor Method is larger than 90% using the Actual Method. Safe Harbor is recommended if you are projected to have a larger tax balance in the current year compared to the prior year.

There are many factors to consider when choosing between the Actual Tax Method and the Safe Harbor Method. Another item to note is you can change between methods every quarter. For example, income was projected to be very high in quarter 1 so you decided to use the Safe Harbor Method to pay your first quarter estimates. In quarter 2, income was projected to be a lot lower than antipicated, you could then decide to use the Actual Method for the second quarter.

### Other Notes

+ If you wish to turn annualization off, click the button to the far right of the respective line item in the input section. Short-term capital gains/(losses) and long-term capital gains/(losses) have annualization turned off by default.
+ To make a number in the input section positive or negative, click the button directly to the right of it. (This functionality to be improved in a future update).
+ Short-Term and Long-Term Capital Losses are limited to -$3,000
+ Tax projection is currently using 2023 tax rates


## Disclosure: :rotating_light:

Although I do believe this tax projection to be accurate and I have tested it for bugs do not rely upon this to estimate your own taxes. Taxes are complicated and this projection does not include all tax scenarios. Please consult a tax professional while using this application.

## More Features? :bulb:

In the future, I plan to make a more advanced version of the application. However, I build this application all by myself and I have limited time capacity. There are a lot of additional features I would have liked to add to make this application more accurate and more functional, including adding additional scenarios, more jurisdications, and the list goes on...

If you have a specific feature requests? Please let me know.

## About :mega:

I developed this application entirely from scratch, encompassing the entire process from idea generation to conceptualization and designing the user interface. Throughout the development, I relied solely on my own skills and expertise, without resorting to tutorials, templates, or boilerplate code.

This application was created based on how a tax accountant and a programmer think, trying to create the best user experience from the knowledge of both. It is worth noting that this application is not something a tax accountant or a programmer could construct by themself. It necessitates a deep understanding of both disciplines to bring it to fruition.

The creation of this project was driven by my desire to enhance my programming abilities and to derive personal satisfaction from merging my interests in programming and tax accounting. As I continue to expand and add more features, the complexity of the project grows, requiring meticulous attention. To simplify the application, I employed Redux to streamline the management of global state. However, the intricate nature of the tax codes in the United States and various States introduces additional challenges. Nevertheless, I am enthusiastic about the development of this application and embrace any obstacles that come my way.

The primary purpose of this application is to assist individuals and accountants in estimating quarterly taxes for themself or their clients. Given the complexity of the United States and State tax codes, not everyone can afford the services of a high-end tax accountant. Hence, my aim is to make this application accessible to freelancers, CPAs, EAs, accountants, and others.

In developing this application, I had to make choices regarding the level of complexity to incorporate. Constructing a comprehensive tax projection application, accounting for every intricate detail, is an arduous and time-consuming task. The intricate nature of the United States and State tax codes further exacerbates this challenge. Hence, I had to strike a balance between the time investment and the complexity involved in building the application. It seems to resemble a problem of Big O Notation (a little coding joke) in terms of optimizing efficiency...

## Key Concepts Used

+ MERN STACK
+ Redux
+ Javascript
+ Typescript
+ Custom Functions
+ Custom CSS
+ React components
+ React hooks
+ Handle onClick and onChange Functions
+ Bootstrap
+ Material UI
+ MongoDB
+ Mongoose
+ Express.js
+ Node.js
+ Auth0
+ And much more

## Source Code?

Check out my source code above.

## Feedback?

Let me know! I would love to know what you think.

If you see any bugs, please let me know.

## Connect With Me :mailbox:

LinkedIn: [https://www.linkedin.com/in/russell-monteith-cpa-0a43975a/](https://www.linkedin.com/in/russell-monteith-cpa-0a43975a/)

My Github Homepage: [https://github.com/russelltheprogrammer/](https://github.com/russelltheprogrammer)

## Version - Latest Release Notes :rocket:

**Current version: 1.3.0**

### Release Notes Log

07/11/23
Version 1.3.0
+ Add safe harbor and comparison feature
+ Moved documentation to its own repo
+ Refactored portion of codebase to make more legible
+ Added migration backend feature for future database changes

06/27/23
Version 1.2.2
+ Added a reset button to the Tax Assumptions box

06/26/23
Version 1.2.1
+ Changed layout of input numbers to a grid system

06/26/23
Version 1.2.0
+ Added ability to annualize certain payments
+ Changes to backend & frontend data types and structures

06/23/23
Version 1.1.0
+ Added button to hide -0- rows in the "Income, Deduction, and Tax Summary"
+ State columns will now be hidden when not in use

06/20/23
Version 1.0.0 is now live!






