# magento_uk_tax_rules
An uploadable csv of UK, EEA and Worldwide tax rates for a UK-based Magento store

First set up your product tax classes that you will need.
Sales > Tax > Product Tax Classes:

- Taxable Goods
- Zero Rated
- Shipping

You may also need:

- Low Rate (5% for fuel and feminine hygiene products)
- Intra EU supply (for B2B zero rated supply)

Then set up Customer tax classes	

- General
- Not logged in
- Intra Eu Wholesale \ B2B

Now import the tax classes in the tax_rates.csv file at Sales > Tax > Import \ Export Tax Classes

Check that you can see 60+ records on the Sales > Tax > Manage Tax Zone and Rates

Finally add in the relevant tax rules:

- EEA VAT - Select all customer groups apart from Intra Eu, select taxable goods, all the VAT?? rates from the drop down
- EEA Zero rated - Select all customer groups apart from Intra Eu, select Zero rate goods, all the ZERORATED?? rates from the drop down
- Wholesale VAT Zero-rated Intra EU Supply - Select Intra EU customer, Intra EU product group, all the ZERORATED?? rates from the drop down


Let us know if this doesn't work for you as we want to refine this for every eventuality!
