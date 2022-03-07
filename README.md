# UFOs

## Overview of Project
The purpose of this project was to build a website that includes a dynamic table that can be, but isn't required to be, filtered across 5 different inputs: Date, City, State, Country, and Shape.

## Results
### General Layout
The UFO Finder webpage opens with the title, "The Truth Is Out There" over a photograph of the earth at night, with the lights of civilization illuminating the shot. After ufologists weigh in with a short article on "UFO Sightings: Fact or Fancy?". Beneath this section, we arrive at a set of filters and a table with the results!

### Filter Walkthrough
Originally, this website included just a single filter and a button that had to be clicked in order to refilter the data. Through the use of JavaScript, the code has been refactored to "listen" for changes across any of the filters. To get started, here is a sample view of the table.

![Unfiltered Data Table](https://github.com/kramerkyle/UFOs/blob/main/static/images/Unfiltered.png)

A user might first select a particular date of interest, "1/10/2010", for example.

![Date Filtered Table](https://github.com/kramerkyle/UFOs/blob/main/static/images/Filter%20Date.png)

The user may then decide to take a closer look at the state of California, by typing "ca" into the State box.

![State Filtered Table](https://github.com/kramerkyle/UFOs/blob/main/static/images/Filter%20Date%20%2B%20State.png)

Finally, the user may wish to focus in on a single city of interest.

![City Filtered Table](https://github.com/kramerkyle/UFOs/blob/main/static/images/Filter%20Date%20%2B%20State%20%2B%20City.png)

Each change is reflected as soon as the user finishes inputting their filter criteria. The change is "heard" when the user leaves the box that was altered.

## Summary
One of the drawbacks of this current design is that the user cannot implement multiple date criteria into the Date Filter Box. This limitation is carried through each of the other input boxes as well.

Allowing the user greater flexibility in recognizing capitalized and uncapitalized inputs as well as selecting multiple dates, cities, and states would be two excellent areas for future development.
