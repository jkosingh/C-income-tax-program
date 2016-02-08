# C-income-tax-program

 a C++ program to calculate annual income tax. Program calculates the total income tax due based upon the amount of income earned (before any deductions), the number of dependents (children), and the amount of tax already deducted from their income by the employer. None of these quantities (income, number of dependents, or tax already paid) may be negative.  The amount of tax deducted cannot exceed the income.  Given below is a list of this year’s rules for calculating income tax based on income and number of dependents.  After the amount of tax owed or the tax return expected will be calculated. 
 
 1)      Determine your taxable income

a. Take the amount of money you earned

b. Determine the number of qualifying dependents. If you have less than or equal to 10 dependents your number of qualifying dependents is your number of dependents.  If you have more than 10 dependents then you have 10 qualifying dependents.

c. To determine your taxable income, begin with the amount of money you earned (before any deductions for taxes were made); call this amount your income.  Your taxable income is your income minus the number of qualifying dependents times $5000.

2)  If your taxable income is < $12,000 you pay no income tax.

3) If your taxable income is >=$12,000 and <= $20,000.00,  your income tax rate is  15%  of your taxable income

4) If  $20,000.00 < your taxable income <= $50,000.00  then you pay an income tax rate of 15% on the first $20000.00 of taxable income and an income tax rate of 20% on the remainder

5)  If your taxable income is greater than $50,000.00 then you pay an income tax rate of 18% of your total taxable income (on all of your taxable income).

6)   If your taxable income is > $100,000.00 and <= $10,000,000.00 then in addition to the 18%  of your total taxable income, you also pay a surtax rate of 3.5% of all taxableincome > $100,000.00

7)  If your taxable income is > 10,000,000 then you must use an alternate procedure not to be included in this program.
