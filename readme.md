
# Data Visualization - Ford GoBike (Bike Shares Dataset)

[![LinkedIn][linkedin-shield]][linkedin-url]
<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#main-features-of-interest">Main Features of Interest</a>
    </li>
    <li>
    <a href="#slideshow">Slideshow</a>
  </li>
 <li>
 <a href="#summary-of-findings">Summary of Findings</a>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

## About The Project
CSV File is downloaded from [Ford GoBike](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv). This dataset includes 183,412 Bike Sharing trips, with 16 features to describe them. There are start and end stations.

## Main Features of Interest
What time of day are trips taking place?
What locations are the busiest, and does time affect station traffic?
What User Profiles (age, user_type, gender) are riding trips?
Do different user profiles correspond to different trips? different times? Do they frequent different stations?
Is bike sharing more common amongst certain ages?
How long is the average trip?
Does average trip time differ if user is a subscriber or customer?

## Slideshow
[![Watch the video](https://user-images.githubusercontent.com/80590275/113487551-d2266100-94c9-11eb-8e12-2289df9e9b4c.gif)](https://user-images.githubusercontent.com/80590275/113487492-6c39d980-94c9-11eb-92d9-74f1f4228703.mp4)

### You can view this Jupyter Notebook as a slide by going to this directory in your terminal, and running the following command:
jupyter nbconvert Bike_Sharing_Analysis_Viz.ipynb --to slides --post serve --template output_toggle

## Summary of Findings
1. Univariate exploration: 90.5% of the users (riders) and Subscribers, with only 9.5% being Customers. 75% of the users are Males. The average user's age is 36. The 75th percentile is age 41, so most of the users are young. The average trip time is 11.74 Minutes.


2. Bivariate exploration: There is a positive correlation between age and duration of trips. The top 5 most popular stations where rides started are: 
-  Market St at 10th St
-  San Francisco Caltrain Station 2  (Townsend St at 4th St)
-  Berry St at 4th St'
-  Montgomery St BART Station (Market St at 2nd St)
-  Powell St BART Station (Market St at 4th St

We also further validate the findings from Univariate Explorations here.

3. Multivariate exploration: Segmenting users by their features helps gain insight into the dataset. We discovered that this dataset pertains to only one month of the year. Popular areas, logically, have much higher traffic. There is no clear explanation to why Male riders and significantly more than Female riders. We notice however that most female rides are under 200 minutes.

 
The stations with the most trips are located in San Francisco and connect to public transportations such as Market St, Caltrain, and Berry St, and Montgomery St Bart.

<!-- CONTACT -->
## Contact

Kareem Ayyad- [@kareem_ayyad](https://twitter.com/kareem_ayyad) - kareem@ayyad.net

Project Link: [https://github.com/kareemayyad/BikeSharing-Analysis-Visualization-DAND](https://github.com/kareemayyad/BikeSharing-Analysis-Visualization-DAND)

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/kareemayyad/
