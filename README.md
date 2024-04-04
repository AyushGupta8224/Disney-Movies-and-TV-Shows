# Disney-Movies-and-TV-Shows

## Roadmap
<ul style="list-style-type:circle;">
  <li>Data subset collected from kaggle: https://www.kaggle.com/datasets/shivamb/disney-movies-and-tv-shows/data</li>
  <li>Loading Data in PowerBi Dekstop</li>
  <li>Data Transformation & Cleaning</li>
  <li>Visualization Using Tools</li>
  <li>Preparing PowerBi Report</li>
  <li>Project is ready and live</li>
  </ul>

## New Variables Added
The dataset has the following new columns:
<ul style="list-style-type:circle;">
  <li>Count of directors</li>
  <li>Count of countries</li>
  <li>Presence in number of countires</li>
  <li>Date, Month and Year from the date_added</li>
  <li>Difference between date_added and release_year for which different Time of Show are formed</li>  
  <li>Category of duration</li>
  <li>Count of genres</li>
  </ul>

## Formulae used
The formulae used during data cleaning are:
<ul style="list-style-type:circle;">
  <li>First Text to Columns and then COUNTA function used to obtain count of directors</li>
  <li>First Text to Columns and then COUNTA function used to obtain count of countries</li>
  <li>Used IFS function where less than or equal to 2, low presence; less than or equal to 5, medium presence; TRUE, high presence</li> 
  <li>First Text to Columns and then used IFS function where less than or equal to 3, recent; less than or equal to 8, little old; less than or equal to 15, old; TRUE, very old</li>
  <li>First Text to Columns and then used IFS function where less than or equal to 30, very short; less than or equal to 60, short; less than or equal to 90, medium; less than or equal to 120, long; TRUE, very long</li>
  <li>First Text to Columns and then COUNTA function used to obtain count of genres</li>
  </ul>

## Disney+ Analysis Dashboard
The dashboard shows:
<ul style="list-style-type:circle;">
  <li>Total No of Movies in Disney+</li>
  <li>The Dashboard will provide interactive interface of list according to user choice of rating</li>
  <li>The User can search according to the category of duration which a movie has</li>
  <li>The User can observe the number of movies added by month in a year</li>
  <li>The User can search according to the number of directors which a movie has</li>
  <li>The User can search according to the number of genres which a movie has</li>
  <li>The User can search according to the number of genres which a movie has</li>
  <li>The User can search according to the presence in number of countries which a movie has</li>
  <li>The Dashboard will provide interactive interface of list according to user choice of time of show</li>
  <li>The User can see the most commonly used words in Title and Description through Word Cloud</li>
  </ul>
  
