#Project Chapter 3 - due 10/5/2016 5:00 p.m.
Computing Tax.

The United States federal personal income tax is calculated based on filing status and taxable income. 
There are four filing statuses: single filers, married filing jointly, married filing separately, and head of household. 
The tax rates vary every year. The table below shows the rates for 2009. 
If you are, say, single with a taxable income of \$10,000, the first \$8,350 is taxed at 10% and the other \$1,650 is taxed at 15%. So, your tax is \$1,082.5.

|**Marginal Tax Rate**	|**Single**	|**Married Filing Jointly or Qualified Widow(er)**	|**Married Filing Separately**	|**Head of Household**|
|**10%**	|\$0 – \$8,350	|\$0 – \$16,700	|\$0 – \$8,350	|\$0 – \$11,950|
|**15%**	|\$8,351– \$33,950	|\$16,701 – \$67,900	|\$8,351 – \$33,950	|\$11,951 – \$45,500|
|**25%**	|\$33,951 – \$82,250	|\$67,901 – \$137,050	|\$33,951 – \$68,525	|\$45,501 – \$117,450|
|**28%**	|\$82,251 – \$171,550	|\$137,051 – \$208,850	|\$68,525 – \$104,425	|\$117,451 – \$190,200|
|**33%**	|\$171,551 – \$372,950	|\$208,851 – \$372,950	|\$104,426 – \$186,475|\$190,201 - \$372,950|
|**35%**|\$372,951+	|\$372,951+	|\$186,476+	|\$372,951+|

You are to write a program to compute personal income tax. 
Your program should prompt the user to enter the filing status and taxable income and compute the tax. Enter 0 for single filers, 1 for married filing jointly, 2 for married filing separately, and 3 for head of household. 

Here are sample runs:

```
Enter the filing status: 0
Enter the taxable income: 100000
Tax is 21720.0
```

```
Enter the filing status: 1
Enter the taxable income: 300339
Tax is 76932.87
```

```
Enter the filing status: 2
Enter the taxable income: 123500
Tax is 29665.5
```

```
Enter the filing status: 3
Enter the taxable income: 4545402
Tax is 1565250.7
```

Task #1: Analysis: Describe the problem including input and output in your own words.

Task #2: Write the program with appropriate comments.

Task #3: Run the program to make sure it works.

Task #4: Submit the homework, including your analysis, using git.
