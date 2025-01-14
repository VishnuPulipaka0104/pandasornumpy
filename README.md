# pandasornumpy
In this module we would be analysing and drawing some conclusions from the Bands, Albums and Songs Data that we have. 
Bands: 

 "id":[1,2,3,4,5,6,7],
    "name":["Seventh Wonder","Metallica","The Ocean","Within Temptation","Death","Van Canto","Dream Theater"]

    
  Albums:
  [
  {"id": 1, "name": "Tiara", "release_year": 2018, "band_id": 1},
  {"id": 2, "name": "The Great Escape", "release_year": 2010, "band_id": 1},
  {"id": 3, "name": "Mercy Falls", "release_year": 2008, "band_id": 1},
  {"id": 4, "name": "Master of Puppets", "release_year": null, "band_id": 2},
  {"id": 5, "name": "...And Justice for All", "release_year": 1988, "band_id": 2},
  {"id": 6, "name": "Death Magnetic", "release_year": 2008, "band_id": 2},
  {"id": 7, "name": "Heliocentric", "release_year": 2010, "band_id": 3},
  {"id": 8, "name": "Pelagial", "release_year": 2013, "band_id": 3},
  {"id": 9, "name": "Anthropocentric", "release_year": 2010, "band_id": 3},
  {"id": 10, "name": "Resist", "release_year": 2018, "band_id": 4},
  {"id": 11, "name": "The Unforgiving", "release_year": 2011, "band_id": 4},
  {"id": 12, "name": "Enter", "release_year": 1997, "band_id": 4},
  {"id": 13, "name": "The Sound of Perseverance", "release_year": 1998, "band_id": 5},
  {"id": 14, "name": "Individual Thought Patterns", "release_year": 1993, "band_id": 5},
  {"id": 15, "name": "Human", "release_year": 1991, "band_id": 5},
  {"id": 16, "name": "A Storm to Come", "release_year": 2006, "band_id": 6},
  {"id": 17, "name": "Break the Silence", "release_year": 2011, "band_id": 6},
  {"id": 18, "name": "Tribe of Force", "release_year": 2010, "band_id": 6}
]



Songs:
[
  {"id": 1, "name": "Arrival", "length": 1.5, "album_id": 1},
  {"id": 2, "name": "The Everones", "length": 6.2167, "album_id": 1},
  {"id": 3, "name": "Dream Machines", "length": 5.6333, "album_id": 1},
  {"id": 4, "name": "Against the Grain", "length": 6.9667, "album_id": 1},
  {"id": 5, "name": "Victorious", "length": 4.9167, "album_id": 1},
  {"id": 6, "name": "Tiara's Song (Farewell Pt. 1)", "length": 7.2667, "album_id": 1},
  {"id": 7, "name": "Goodnight (Farewell Pt. 2)", "length": 7.1667, "album_id": 1},
  {"id": 8, "name": "Beyond Today (Farewell Pt. 3)", "length": 5.1, "album_id": 1},
  {"id": 9, "name": "The Truth", "length": 4.2833, "album_id": 1},
  {"id": 10, "name": "By the Light of the Funeral Pyres", "length": 3.9, "album_id": 1},
  {"id": 11, "name": "Damnation Below", "length": 6.7333, "album_id": 1},
  {"id": 12, "name": "Procession", "length": 0.75, "album_id": 1},
  {"id": 13, "name": "Exhale", "length": 9.5, "album_id": 1},
  {"id": 14, "name": "Wiseman", "length": 5.7, "album_id": 2},
  {"id": 15, "name": "Alley Cat", "length": 6.1, "album_id": 2},
  {"id": 16, "name": "The Angelmaker", "length": 8.4833, "album_id": 2},
  {"id": 17, "name": "King of Whitewater", "length": 7.3333, "album_id": 2},
  {"id": 18, "name": "Long Way Home", "length": 4.4333, "album_id": 2},
  {"id": 19, "name": "Move on Through", "length": 5.0667, "album_id": 2},
  {"id": 20, "name": "The Great Escape", "length": 30.2333, "album_id": 2},
  {"id": 21, "name": "A New Beginning", "length": 3.0833, "album_id": 3},
  {"id": 22, "name": "There and Back", "length": 3.0333, "album_id": 3},
  {"id": 23, "name": "Welcome to Mercy Falls", "length": 5.1833, "album_id": 3},
  {"id": 24, "name": "Unbreakable", "length": 7.3167, "album_id": 3},
  {"id": 25, "name": "Tears for a Father", "length": 1.9667, "album_id": 3},
  {"id": 26, "name": "A Day Away", "length": 3.7167, "album_id": 3},
  {"id": 27, "name": "Tears for a Son", "length": 1.7, "album_id": 3},
  {"id": 28, "name": "Paradise", "length": 5.7667, "album_id": 3},
  {"id": 29, "name": "Fall in Line", "length": 6.15, "album_id": 3},
  {"id": 30, "name": "Break the Silence", "length": 9.4833, "album_id": 3},
  {"id": 31, "name": "Hide and Seek", "length": 7.7667, "album_id": 3},
  {"id": 32, "name": "Destiny Calls", "length": 6.3, "album_id": 3},
  {"id": 33, "name": "One Last Goodbye", "length": 4.35, "album_id": 3},
  {"id": 34, "name": "Back in Time", "length": 1.2333, "album_id": 3},
  {"id": 35, "name": "The Black Parade", "length": 6.95, "album_id": 3},
  {"id": 36, "name": "Battery", "length": 5.2167, "album_id": 4},
  {"id": 37, "name": "Master of Puppets", "length": 8.5833, "album_id": 4},
  {"id": 38, "name": "The Thing That Should Not Be", "length": 6.6, "album_id": 4},
  {"id": 39, "name": "Welcome Home (Sanitarium)", "length": 6.45, "album_id": 4}
]



Exercises to do:
1. Change the name of the column the data returns to Band Name
2. Make sure to only return one result from this query, and that you are not returning any albums that do not have a release year. Select the Oldest Album
3. Get all Bands that have Albums. There are multiple different ways to solve this problem, but they will all involve a join. Return the band name as Band Name.
4. Get all Bands that have No Albums. This is very similar to #4 but will require more than just a join. Return the band name as Band Name.
5. Get the Longest Album. This problem sounds a lot like #3 but the solution is quite a bit different. I would recommend looking up the SUM aggregate function. Return the album name as Name, the album release year as Release Year, and the album length as Duration.
6. Insert a record for your favorite Band and one of their Albums
7. Delete the Band and Album you added in #8
8. Get the Average Length of all Songs
9. Select the longest Song off each Album
10. Get the number of Songs for each Band

**Answers would be available in ipynb file and Data loading process would als be discussed over there**

