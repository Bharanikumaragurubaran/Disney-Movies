### Disney-Movies
This is a Web Scrapping project where I have extracted details of all the Disney movies that were released till now.
### Python packages used
1. Requests
2. Pandas
3. Beautiful Soup
### Process
1. Using Python Web Scrappinig I have scrapped through various Wikipedia pages to extract 'info box' of every Disney Movie.
2. It will contain all the necessary informations like movie name, director name, release date, budget, box-office etc.,
3. Scrapped data might have some irregular value so the next step will be <b>Data Cleaning</b>.
4. Below steps were carried out in Data Cleaning,
   <ul>
     <li>Clean up references., [1] --> Altered while scraping</li>
     <li>Convert dates into Datetime object</li>
     <li>Convert runnng time into integers</li>
     <li>Split long strings --> --> Altered while scraping</li>
     <li>Convert Box office and Budget to numbers</li>
   </ul>
Once we get a clean dataset., I saved it in CSV and JSON formats for further analysis in future.
