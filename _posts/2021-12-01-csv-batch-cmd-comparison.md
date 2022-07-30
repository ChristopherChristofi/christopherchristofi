---
category: Programming
topic: Shell Scripting
title: Saving CSV Business activity with CMD
---

I wanted to re-correlate and re-integrate business intelligence that was added to a data sheet of records received at regular intervals.
Upon each regular interval the added business intelligence was lost in the newly acquired data sheet, as the set of data records was either reprinted, new, or no-longer requested data entries.
The purpose of my script was to carry over any added business intelligence, that could be considered as important notes, from the existing old and edited data sheet into the newly acquired, unedited data sheet, which also represented the only true data instances - the old data sheet, of a past time interval, would have data records that were either no longer required or missing.
I wrote the script for Windows using cmd batch, I wanted to use a minimal amount of resources, not have to rely on a high level programming language, and I like cmd for its simple execution.

***A diagram depicting the workflow of the script can be seen below:***

<br>

![Diagram of process workflow of the csv comparison script](/assets/img/misc/uml/cmdcsvcomparison_workflow.png)

<br>
<br>
<br>

***A diagram depicting the outline of the data structures can be seen below:***

<br>

![Diagram of the change in data structure for the cmd csv comparison script](/assets/img/misc/uml/cmdcsvcomparison_datastructures.png)

<br>

To view the script, please visit my GitHub profile [here](https://github.com/ChristopherChristofi/csv-compare-script/blob/main/csv_compare_script.cmd), and the validation tests can be found [here](https://github.com/ChristopherChristofi/csv-compare-script/blob/main/comp_test.cmd).
