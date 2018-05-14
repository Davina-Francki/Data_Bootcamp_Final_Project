# Data_Bootcamp_Final_Project

This project was completed by Davina Francki in partial fulfilment of ECON-UB.0232, Data Bootcamp, Spring 2018. I certify that the NYU Stern Honor Code applies to this project. 

In particular, I have:

Clearly acknowledged the work and efforts of others when submitting written work as our own. The incorporation of the work of others–including but not limited to their ideas, data, creative expression, and direct quotations (which should be designated with quotation marks), or paraphrasing thereof– has been fully and appropriately referenced using notations both in the text and the bibliography.

And I understand that:

Submitting the same or substantially similar work in multiple courses, either in the same semester or in a different semester, without the express approval of all instructors is strictly forbidden.
I acknowledge that a failure to abide by NYU Stern Honor Code will result in a failing grade for the project and course.

---

## Project Description

Medicaid expansion involves extending coverage to individuals with incomes below 138% of the federal poverty line. However, in 2012, the Supreme Court ruled that states could not be coerced into expanding Medicaid via the Affodable Care Act. Instead it was up to each state to decide whether or not to expand the program. Therefore, this project sets out to answer the following question: Did a state's decision to expand Medicaid have an effect on how much it spends on drug utilization? This question is addressed using a combination of Medicaid enrollment data, US census data, and state drug utilization(SDU) data. The enrollment data, provided by [Medicaid.gov](https://www.medicaid.gov) will help determine which states have expanded Medcaid. Then the SDU data, also available on [Medicaid.gov](https://www.medicaid.gov), but through the [Socrata API](https://dev.socrata.com), will provide information on state spending over time. Finally, population data will be taken from the census to normalize spending to spending per capita. Analysis of this data leads to the conlcusion that as a group, states that decided to expand Medicaid coverage in 2014 have increased their spending on drug utilization at a much faster rate than their non-expansion counterparts. However, the expansion states have always spent at least a bit more on prescription reimbursements. These states could have been somehow predisposed to agree to Medicaid expansion. In the future, further research on why states decide to expand Medicaid would be interesting. Perhaps there are some key features that help predict whether or not a state decides to expand.
