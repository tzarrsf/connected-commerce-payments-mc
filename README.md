# Implementation Camp: Connected Commerce with Payments and Marketing Cloud (aka connected-commerce-payments-mc)

### Preamble

The data and code samples in this repository are organized in a traditional "developer package" deployable from an IDE such as Visual Studio Code; That is very much 'by design.' SFDX packages while unwieldly for Administrators who just want to stand up an environment, place orders and test out basic features can greatly accelerate self-enablement and productivity for those familiar with this setup. If you believe you've reached this repository in error, please consult these resources first as they're considered a prerequisite before attempting this implementation camp.

#### Prerequisites
* [Get to Know B2B Commerce for Administrators](https://sfdc.co/B2BAdminGetToKnowCurriculum)
* [Get to Know B2B Commerce for Administrators repository](https://github.com/tzarrsf/b2b-commerce-gtk-admin/)
* [Get to Know B2B Commerce for Developers](https://sfdc.co/B2BDevGetToKnowCurriculum)
* [Get to Know B2B Commerce for Developers repository](https://github.com/tzarrsf/b2b-commerce-gtk-dev/)

### Course candidates
The target audience / persona is __developers__. No sales material will be covered except maybe to get you excited about the possibilities of incorporating additional clouds in your customers' projects. This course is currently offered by invitation only. Preference is given to those who hold relevant qualifications. In addition to the Salesforce Administrator, Platform App Builder and Developer I/II and JavaScript certifications, these are the candidate tiers listed in descending order of likelihood to secure a seat.

1. Ideal Candidate: Holds all four Accredited Professional credentials: B2B Administrator, B2B Developer, Order Management Administrator, Order Management Developer
1. Tier 2 Candidate: Holds a credential on each product track (B2B vs Order Management) __or__ holds the full track on one products. Examples: B2B Admin + Dev / B2B Admin + SOM Admin / SOM Admin + SOM Dev
1. Tier 3 Candidate: Holds one credential on the B2B or Order Management product
1. Tier 4 Candidate: Does not hold any Accredited Professional credentials but has experience implementing with the product

## ⚠️ Disclaimers

Examples are provided as-is. It's not officially supported by Salesforce or covered by SLAs.
API documentation is not provided with the examples. Please refer to the official documentation.
The documentation for the majority of the data and code in this collection can be found in these URLS:

* [Integration Architecture for B2B and D2C Stores (LWR)](https://developer.salesforce.com/docs/atlas.en-us.b2b_b2c_comm_dev.meta/b2b_b2c_comm_dev/b2b_b2c_comm_integration_architecture.htm)
* [Native Shipping Service](https://help.salesforce.com/s/articleView?id=sf.comm_set_up_native_shipping.htm&type=5)
* [Configure the Salesforce Tax Solution](https://help.salesforce.com/s/articleView?id=sf.comm_salesforce_tax_solution.htm&type=5)
* [Cart Calculate API](https://developer.salesforce.com/docs/commerce/salesforce-commerce/guide/cart-calculate-api.html)
* [Default Calculator Invocation Logic](https://developer.salesforce.com/docs/commerce/salesforce-commerce/guide/cart-calculate-api.html#default-calculator-invocation-logic)
* [Extension Provider Examples](https://developer.salesforce.com/docs/commerce/salesforce-commerce/guide/extension-provider-examples.html)
* [Commerce Extensibility Repository](https://github.com/forcedotcom/commerce-extensibility/tree/releases/248)
* [Cart Reference](https://developer.salesforce.com/docs/commerce/salesforce-commerce/guide/cart-reference.html)
* [Tax Reference](https://developer.salesforce.com/docs/commerce/salesforce-commerce/guide/tax-reference.html)
* [Shipping Cart Calculator](https://developer.salesforce.com/docs/commerce/salesforce-commerce/guide/ShippingCartCalculator.html)
* [CSV File Format for Importing Data for a Store](https://help.salesforce.com/s/articleView?id=sf.comm_store_csv_format.htm&type=5)
* [Plan Your Category Structure](https://help.salesforce.com/s/articleView?id=sf.comm_categories_structure.htm&type=5)
* [Create Product Categories and Subcategories](https://help.salesforce.com/s/articleView?id=sf.comm_categories_create.htm&type=5)
* [Configure Store Language, Currency, and Tax](https://help.salesforce.com/s/articleView?id=sf.comm_create_international_store.htm&type=5)
* [B2B and D2C Commerce Resources](https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/connect_resources_commerce.htm) of the Connect REST API Developer Guide.

### Organization

This repository contains a code folder and a data folder at the root level meant to support Developers during the implementation camp (live or virtual course). The contents are aligned with the following resources which you'll reference throughout the three days.

* [Connected Commerce Payments Prework](https://sfdc.co/ConnectedCommercePaymentsPrework) [WIP - access may not be public yet as of 4/24/24]
* [Connected Commerce Payments Day 1 Exercises](https://sfdc.co/ConnectedCommercePaymentsExercisesDay1) [WIP - access may not be public yet as of 4/24/24]
* [Connected Commerce Payments Day 2 Exercises](https://sfdc.co/ConnectedCommercePaymentsExercisesDay2) [WIP - access may not be public yet as of 4/24/24]
* [Connected Commerce Payments Day 3 Exercises](https://sfdc.co/ConnectedCommercePaymentsExercisesDay3) [WIP - access may not be public yet as of 4/24/24]
* [Connected Commerce Take Home Lab](https://sfdc.co/ConnectedCommercePaymentsTakeHomeLab) [WIP - access may not be public yet as of 4/24/24]

### Applicability

This code is meant to support the "Get to Know B2B Commerce for Developers" Partner Learning Camp curriculum in the Partner Learning Camp. Examples here may be oversimplified to support a speedy setup. It's up to you as a Solution Implementing Partner and Developer or Architect to explore the rest of the capabilities that that the checkout integration, data models and platform can handle.

### Change Frequency

This code may be updated with each seasonal release. The original check-in was tied to Spring '24.

