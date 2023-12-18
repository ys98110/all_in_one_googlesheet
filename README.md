# Project management/data entry/AR template 

## [Link](https://docs.google.com/spreadsheets/d/12Ga3FjOTrPm-NbdD_vt1rYL4uHXxFE2lnjU66pd6VWE/edit?usp=sharing)

## Overview
I've created this template on google sheets to replace the company's current excel only, disconnected data entry system.
Eventually they would need to switch to a database system but they first need some kind of structure before becoming so. This I believed would help them transition into it. <Br>
Due to several reasons, it was not used thus many parts are not fully complete or well thought out but I had fun making it and learned a trick or two.
The company I worked for is a travel agency that handle packaged tours and customised incentive tours.
This goolge sheet is designed to streamline one data entry to connect into accounts receivable, profit and loss, and project management. 
It is a very flexible/user customisable but at the same time due to this characteristics, the data quality may not be optimal. 
This is because many of the columns that should be restricted to certain entries are open for edit to allow for any unforeseen circumstances. 
<br>
## How to use
1. Go to Settings tab to customise for your own desirable settings.
2. Go to Supplier/product info tab to add products you want in your tours.
3. Go to the Template tab to set up a tour that would be repeated. The Code column can be changed to any reference you want for this specific set of tour.
4. Got to the Template Generator to set up the actual teams entering.
5. In cells A2:B9, enter the relevant details. The Code entry here can be any reference you want this specific team to be.
6. Within the coloured cells, copy the automatically filled out entry(don't copy where there is no entry and NA values) and paste value only to the data tab.
7. The data tab is where the actual data entry is happening. Change any details that maybe wrong from the template.
8. When invoices of each of the entries come, enter the amount in the actual amount column, change the due date if needed and enter the invoice number.
9. To calculate how much to charge customer for these tours, go to the Pricing Calculator tab and calculate it.
10. This tab is open for any customisation to help calculate the pricing as it does not change any other values in other tabs.
11. With the final pricing, go to the Invoice Tracker tab and enter relevant details into the columns.
12. Invoice can be created in the invoice tab.
13. Everything entered in the data tab, is visible through the Gantt Chart. This shows schedules of all teams entered that was entered into the data tab. It is also highly customisable.
<br>
## What this sheet is actually capable of at this state
1. Get entries of the data of the tours with their costs
2. Manage charging a single customer for the tours

## Problem of this sheet
1. Can only manage single customer. (This was not the problem for this agency, as they maiinly dealt with a single big company)
2. Gets slow if the data tab gets too big. 

## To be but what never became...
### Accounts Payable Manager
A separate page that manages the invoices enetered that could also connect into bank reconciliation.<br>
It can possibly used to overview how much the company spends on each supplier and etc. 

### Profit and Loss
A separate page that fully analyses the financial side of the data entered into the data tab and the invoice tracker.<br>
The data tab has fairly detailed information and with this, we should be able to derive detailed report.

**These two reports were the reasons why I wanted to create this google sheet in the first place. But sadly it never came to be.**


