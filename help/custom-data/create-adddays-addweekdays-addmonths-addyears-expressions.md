---
title: Create ADDDAYS, ADDWEEKDAY, ADDMONTHS, ADDYEARS expressions
description:  Learn how to use and create the ADD expressions in a calculated field in Adobe [!DNL Workfront].
activity: use
type: tutorial
team: Technical Marketing
kt: 8912

---
# Create ADDDAYS, ADDWEEKDAY, ADDMONTHS, ADDYEARS expressions

In this video, you will learn:

* What the ADDDAYS/ADDWEEKDAY/ADDMONTHS/ADDYEAR expressions calculate
* How to create an ADDWEEKDAYS data expression in a calculated field

>[!VIDEO](https://video.tv.adobe.com/v/335175/?quality=12)

## Additional examples

Below are a few additional ADDDAYS/ADDWEEKDAY/ADDMONTHS/ADDYEAR expressions Adobe [!DNL Workfront] customers have created.

**Should have been done by**

The customer wanted to know when the task should have been completed based on the Actual Start Date and the Planned Duration. The Projected Completion Date won’t work in this case because it can move if the task is late, and the Planned Completion Date doesn't help if there are delays in prior tasks. 

The expression created was ADDDAYS(Actual Start Date,(Duration/480))

Time in the Duration field is stored in minutes. So in this expression, the Duration field cannot stand alone if the time is to be reflected in days. For that to happen, the Duration has to be divided by 480 minutes (480 minutes = 8 hours = 1 Day)

This is why the second value slot contains (Duration/480).


**Invoice completion date**

This example includes another calculated field, already created and saved in the system, within the expression.

The customer was capturing the date the invoice was submitted through a custom date field, titled “Invoice Submission Date”, in the custom form. Once submitted, they have 30 days to complete and file the invoice. To automatically produce that completion and filing date, they created a calculated field using ADDDDAYS and the Invoice Submission Date field. The expression looked like this:

ADDDAYS(Invoice Submission Date,30)
