# UFOs

## Overview of Project: Explain the purpose of this analysis.

This analysis added several filtering options on a website for users to be able to search UFO sitings based on criteria for the date spotted, location of the siting (city, state, and country), and the shape of the UFO.

The data of the UFO sitings was stored in a javascript file. An application was written in javascript that built a data table with working filters on a webpage, and this app worked with html and css files for styling and formatting the webpage. 

### Tech Stack
- Javascript
- D3 JS library
- Bootstrap
- HTML
- CSS

## Results: Describe to Dana how someone might use the new webpage by walking her through the process of using the search criteria. Use images of your webpage during the filtering process to support your explanation.

To use this webpage for UFO analysis, a user can filter based on one or several search criteria. First, notice that there are 5 unique search criteria in the left panel of the webpage:

![All Filters](/static/images//UFOs/images/All_Filters.png)

Then reference the placeholder text within the filter input boxes to know what is the proper format for entering search criteria. For example, the placeholder text for state is `ca`, so one can run a similar search to find all UFOs in the state of Texas by entering `tx` and then hitting `Enter` on one's keyboard. 

![Texas Filter](/static/images/Texas_Filter.png)

To clear the UFO search criteria and return to the original state of the data table, simply delete the search criteria entered and hit `Enter` on one's keyboard again.

You can also search the UFO dataset by entering multiple criteria at once. Enter as many criteria as you want, and then hit `Enter` to get the results. In this example, the UFO dataset was filtered by triangle shaped UFOs spotted in California on 1/1/2010. It was an active day for aliens in CA!

![Multiple Filters](/static/images/Texas_Filter.png)


## Summary: In a summary statement, describe one drawback of this new design and two recommendations for further development.

The webpage design allows for dynamic searching of UFO data using the filters feature. However, one drawback is that the comprehensive list of filter options is not clear. For example, how does a user know which countries they can search for to find data on UFO sitings? Besides the `us` placeholder for the country filter, it's not possible to tell which other countries are included in the dataset. The same goes for all of the other filter options.

There are three recommendations to further improve this design.

1. Modify the State, Country, and Shape filters to be dropdowns instead of text entry, so that the user knows the complete options for filtering based on these criteria. These three filters were chosen because the number of options for these filters is limited enough that a dropdown of options would likely not be overwhelming for the user to choose from.

2. For the date filter, modify it so the user can choose from a range of dates instead of a specific date. It's frustrating to have to enter dates individually and for the search to yield nothing for the date entered. A range would limit the amount of work a user needs to do to find the information they are looking for.

3. Specify the the date range of the data included, either by adding that to the placeholder text after implementing the second recommendation (above, adding a range of dates), or by adding text to the webpage that specifies the time period evaluated. 