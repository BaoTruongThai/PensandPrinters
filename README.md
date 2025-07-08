# Project Purpose
Examining and deciding the best marketing strategy that would be the most appropriate approach for maximising the revenue and profit of the new product line. 

# PensandPrinters

Pens and Printers was founded in 1984 and provides high-quality office products to large organizations. We are a trusted provider of everything from pens and notebooks to desk chairs and monitors. We don’t produce our own products but sell those made by other companies.

We have built long-lasting relationships with our customers, and they trust us to provide them with the best products for them. As the way in which consumers buy products is changing, our sales tactics have to change too. Launching a new product line is expensive and we need to make sure we are using the best techniques to sell the new product effectively. The best approach may vary for each new product so we need to learn quickly what works and what doesn’t. Six weeks ago we launched a new line of office stationery. Despite the world becoming increasingly digital, there is still demand for notebooks, pens and sticky notes. Our focus has been on selling products to enable our customers to be more creative and focused on tools for brainstorming. We have tested three different sales strategies for this, targeted email and phone calls, as well as combining the two.

# Files

# Data validation

The original dataset contains 15000 rows and 8 columns before cleaning and validation.

    **week**: 6 unique values, from 1 to 6. No cleaning is needed.
    **sales_method**: 3 unique methods including Call, Email and Email+Call, with 23 values like as “em + call” and 10 values like as “email” were corrected.
    **customer_id**: character variable without missing values, same as the description. No cleaning is needed.
    **nb_sold**: 10 numeric categories without missing values from 7 to 16, same as the description. No cleaning is needed.
    **revenue**: numeric values with 1074 missing values.
    **years_as_customer**: numeric values with a 2 outliers identified as a customer with 47 and 63 years as customer. However, the store has been in existence for 39 years, since 1984.
    **nb_site_visits**: numeric values without missing values, same as the description. No cleaning is needed.
    **state**: 50 possible values without missing values, same as the description. No cleaning is needed.
