# UFOs

## Overview
The purpose of this project was to update an already functional dynamic table. In order to provide users with the possibility of deeper analysis of the data, we added extra filters to browse through the information. In the original table, users could filter by date, but with these simple adjustments, now the users are able to filter for multiple criteria like city, state, country and shape. 

### Resources
- Software
  - Javascript
  - HTML
  - CSS
- Data
  - data.js

## Results
The first adjustment made was to eliminate the search button and add the new search criteria. 

*Fig 1. Filter Search*

![Search_criteria](https://user-images.githubusercontent.com/22451540/157927072-5fa8487d-e292-47be-8b1b-8bbd4cdba326.PNG)

The next steps were taken to extract the necessary information from the users input and build a new table based on those inputs.
Say, for instance that you wanted to get all the sightings of a specific shape. You would type "triangle" in the search box and the table would update to show only those results

*Fig 2. Shape filter*

![triangle](https://user-images.githubusercontent.com/22451540/157929008-003702d6-910a-45fe-9603-4c39dfc49393.PNG)

Let's continue with that example, and say that from those tirangle shape sightings, you were interested only in the ones that happened in the state of California. You would type "ca" in the state box and would be shown an updated table.

*Fig 3. State filter*

![state_shape](https://user-images.githubusercontent.com/22451540/157929867-5ce150e1-f600-4349-a166-d7daf7f6b9e3.PNG)

This process can be repeated and changed as many times as the user wants and the results can be as narrow or as broad, depending on the search criteria. 

## Summary
### Drawback
One possible drawback from this interaction is that the user needs to browse the table in order to know how the data is stored. For instance, if you were to type California instead of ca, you would not get the expected results. 

### Recommended actions
1. In order to improve this drawback, we could display a dropdown menu in each criteria, so the user can see the way the information is stored and select accordingly.
2. Another possible improvement is to add equivalencies in the code to capture this "mismatches".
