# CitiBike NYC Monthly Dashboard

Tools Used

    - Tableau

## Overview:

An interactive dashboard for Citi Biki bikesharing in New York City. Built to gather insight into trends that could determine viability of similar programs in other cities.

The full dashboard can be found [HERE](https://public.tableau.com/app/profile/jeremy.d.larsen/viz/Citibike_Monthly_Story/NYCCitiBikeStory)

This Dashboard can be used to analyze any of the monthly datasets available from CitiBike.
To view monthly data:

- Make a clone of this repository
- Download the requisite file from [CitiBike](https://s3.amazonaws.com/tripdata/index.html), into the Resources/Data folder
- Unzip the downloaded file
- Open the attached Workbook
- In the 'Data Source' tab select the unzipped .csv file:

#### Dashboard Visualizations

- Figure 1 - Where Trips Start
  A visualization of the start locations for bike rentals with their size and color denoting the frequency of use. **This value can be adjusted by interacting with the dashboard for a more focused look at ride count during specific times.**

- Figure 2 - How Often and How Long
  This Figure shows the length of time bikes are rented for the CitiBike New York program and how many trips are of similar lengths. The colors denoting if the renter is a subscriber or not. **This value can be adjusted by interacting with the dashboard for a more focused look at ride count during specific times.**

- Figure 3 - Number of Rides
  The total number of rides for the month. **This value can be adjusted by interacting with the dashboard for a more focused look at ride count during specific times.**

- Figure 4 - Customers/Subscribers
  A pie chart denoting the amount of customers that were subscribers or just renters for the month. **This value can be adjusted by interacting with the dashboard for a more focused look at ride count during specific times.**

- Figure 5 - Bike Utilization
  A bubble chart showcasing each bike and its frequency and average use time. The colored bubbles denote a bike's frequency of trips. The size of the bubble denotes the bikes average ride time. **This value can be adjusted by interacting with the dashboard for a more focused look at ride count during specific times.**

- Figure 6 - When and How Often
  A heamap showing the days and times that bikes are most frequently checked out. **Data from this chart can be isolated to use the other visualizations with a more focused look at specific days of the week and times thorughout the month.**

##### Additional Visualizations in the Story

- Figure A - Peak Hours Bar Chart
  A bar graph visualizing total rider count across the day highlighting peak times thoughout the month. Similar data output to Fig 6.

- Figure B - End Locations
  Counter visualization to Fig. 1, containing the end locations for bike rentals with their size and color denoting the frequency of use.

- Figure C - User Gender Breakdown
  A pie chart visualizing the gender breakdown of renters.

- Figure D - Duration by Age
  An area chart of the average Trip time by user age.
