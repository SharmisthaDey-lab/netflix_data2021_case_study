Netflix Data Exploration Business Case
- Netflix is one of the most popular media and video streaming platforms. They
have over 8000 movies or tv shows available on their platform, as of mid-2021,
they have over 200M Subscribers globally.
- The particular business case focuses on the Netflix show data and provides
insightful information on 8807 shows
- Analyzing the data and generating insights helps Netflix decide which type of
shows/movies to produce and how to grow the business.


Dataset:
This tabular dataset consists of listings of all the movies and tv shows available on
Netflix, along with details such as - cast, directors, ratings, release year, duration, etc.

Link : https://www.kaggle.com/datasets/sdey2006/netflix-titles-until-2021

The data is available in a single csv file :

- Show ID : The ID of the show
- Type: Identifier - A Movie or TV Show
- Title: Title of the Movie / Tv Show
- Director: Director of the Movie
- Cast: Actors involved in the movie/show
- Country: Country where the movie/show was produced
- Date_added: Date it was added on Netflix
- Release_year: Actual Release year of the movie/show
- Rating: TV Rating of the movie/show
- Duration: Total Duration - in minutes or number of seasons
- Listed_in: Genre
- Description: The summary description

Dashboard Visuals - [Tableau](https://public.tableau.com/views/NetflixData1925-2021BusinessCaseStudy/NetflixMoviesTvShowsDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

<img width="1249" height="999" alt="Netflix Movies   Tv Shows Dashboard" src="https://github.com/user-attachments/assets/ff9d5a34-a5e4-47ff-a63d-29c7b507ab87" />


Executive Summary - Netflix Content Strategy

1. **Netflix Core Library Structure**
Our analysis confirms that Netflix remains a movie-heavy platform, with feature films are greater in number than TV shows by 70% of total set. Production of TV shows is more consistent and stable which suggest strategic approach towards long term subscriber retention while Movies are primary strategy for volumn of content and variaty for continuity of engagement.

2. **Global Production Leaders**
The United States and India are the primary leaders in licenced content where USA outperforms in both the segments of content. India is powerhouse of bollywood movies and versatile regional cinemas.South Korea & Japan are emerging markets for Tv Shows and it highlights that Netflix's long terms vision is global expansion towards more specialized international gerne like k-darmas.

3. **Seasonality**
Netflix follows Holiday Pulse stratgy by timing its movie uploads during July i.e summer holidays and December i.e Thanks Giving and New Years. It targets to achive more engagement during the holiday season due to peak leisure time with Adults and Students.
Early month upload cycle reflects Netflix aligns their effort towards freshness of the content aligned with every billing cycle

4. **The "Originals" Era**
The data shows that there was explosion of content on Netflix platform in 2010 which indicates pivotal shift from content distribution business strategy towards global production. Hitorically, Netflix had a gap mode of 2 days which shifted 2010 onwards to 0 days indicating Netflix shifted to same year content integration strategy as release year. So they are now first window destination for new entertainment.

5. **Audience Targeting**
Netflix library is heavily loaded with Adult(TV-MA) and Teens (TV-14), while Kids content is vital niche it is significally lower in concentation on the platform. So this indicates Netflix's primary business goal is to capture binge watching adult demographics

6. **Data Quality Reflection**
There were several data quality gaps observed through the analysis with unknown or missing values for Directors/Country and samll percentage of illlogical entires. We were able to filter out these anomolies  and identify startegic patterns driving the platform.

Key Recomendations

1. Double down on the global engagment for originals and regional content for all demographics
2. Maintain a consistent content provisioning cycle during the low peak seasons like Feb for consistent engagment
3. Netflix data is heavily skewed towards Adult and Teen content. While adult content is saturated,Netflix should invest around kids and family niche to maintain viewer retention with high quality kids content as it is a daliy need for majority of household.
4. Netflix should invest in Metadata governance as major data quality issues were found and streamline for more comprehensive data engagement to suport AI expansion in future as well.



