# UFOs

## Overview of Analysis:
Client requested a website to present data on UFO sightings. This includes a small blurb written by the client and a table of UFO sightings based of a dataset provided by the client. It was requested that the table be dynamic by including multiple filter options.
## Resources
- Software: VS Code, Bootstrap, Cloudflare D3
## Results
The table filters start out blank with grey examples in each field as seen below.

<p align="center">
  <img src="https://github.com/justinkirk8/UFOs/blob/main/static/images/filter_before.png" width="900" />
</p>

When the user enters info into the filters and presses enter. The table will automatically filter itself to only show the entries that match all the filters with values in them. The example below is filtered for ‘1/1/2010’ for the date and ‘ak’ for the state.

<p align="center">
  <img src="https://github.com/justinkirk8/UFOs/blob/main/static/images/filter_after.png" width="900" />
</p>

## Summary
One of the major drawbacks of the site in its current condition is that the user must look through the table to see what they can enter into each filter to actually return a result. One improvement would be to add drop downs to the filter to provide a quicker and less frustrating user experience. A second improvement would be to add processing to the filters to account for differences in capitalization. So that if a user entered AK it would still accurately filter to ak on the table. A third improvement would be to obtain a larger dataset. The current dataset is not terribly compelling since it only has one month of data.
