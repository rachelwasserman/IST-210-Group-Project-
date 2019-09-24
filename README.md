# IST-210-Group-Project-

NETFLIX

We chose to create a database for a video streaming service called Netflix. This database includes five entities: Movies, TV, Actors, DVD, and Users. This service allows users to stream both movies and tv shows, so our team decided it was best to separate the two entities. In the “Movie” entity, we will include all the information regarding movies available, including title, length, year of release, genre, director(s), cast, and maturity rating. In the “TV” category, we will include all the information regarding the tv-shows available, including title, number of seasons, number of episodes, year the show began, genre, cast, and maturity rating. Our next entity is “Actors,” since users are able to search by actor or actress. The attributes would include name, movies, shows, and similar actors. In addition, the DVD entity is home to attributes such as DVD title, DVD ID number, Location ID, address, and recipient (a.k.a. where the DVD is being sent). The dynamic entity that our database will hold is “Users”. This end-user table will include subscription status, watch history, ratings, search history, total streaming time, profile name, and age restriction as its attributes.
Now that we have described the entities in our database and the coinciding attributes to each, we will explain the relationship between them and whether any constraints exist. Our Users watch Movies at a many-to-many relationship. The only constraints we found necessary for the “User” table is that the subscription status cannot be inactive. Our Users watch TV shows with the same many-to-many relationship. Both TV and Movie entities would have a constraint requiring that year of release be before 2020. The two differ in the fact that the “Movies” entity will require a constraint that the length not be less than 20 minutes, and the “TV” entity will require a constraint that the number of seasons can not be less than one and number of episodes can not be less than one. The DVD entity can encompass a variety of relationships, such as many DVDs to one user or one DVD to one user (1:1 or M:M).  Lastly, Actors can appear in Movies and TV shows at a many-to-many relationship, and have no constraints. The “Actors” entity does not have constraints since Netflix still includes actors and actresses in the database and search results, even if he or she does not have any streaming material on Netflix. 

 SPOTIFY

Our team wants to create a database which provides and organizes music in a more accessible way to users around the world. There are many entities such as this that exist in society today, but our idea has attributes which make it unique such as offline downloading. For example, on airplanes (where Wi-Fi may not be available) users are still able to access their music libraries if they downloaded their music prior to takeoff. We intend to organize this database/table in 5 different ways. The 5 entities we believe would best showcase our data in the database are: song, artist, album, playlist, and listeners. The listeners entity, specifically, is real time “end-user” data because the number of listeners are constantly being updated throughout the system. Our different entities are characterized by multiple attributes. “Song” is described by a specific title, length, genre, and song identification number (which makes it a unique entity within the database). The entity “Artist” has attributes such as artist first name, last night, classification (such as band, solo artist, group, etc.), and artist identification number. “Album” can be made unique through attributes such as album name, year released, and genre. “Playlist” has attributes such as type (e.g. chill, romance, workout), classification, and playlist identification number. Finally, the end-user data from the “Listeners” entity can be sorted by customer identification number, first name, or last name. 
From this plethora of entities and corresponding attributes, we can now determine the different relationships among the data. Let's start at the beginning. “Song” and “Artist” have a one-to-one relationship, because even if there are many artists, they are classified as one group. “Artist” and “Album” also have a one-to-one relationship, but can have a many-to-one relationship if an album is a collaboration between many different artists. “Playlist” and “Song” is an example of a one-to-many relationship, because one playlist hosts many songs. Lastly, listeners to song represents a many-to-one relationship because numerous people can be listening to one song at the same time around the world through the Spotify application. 

2021LIFE

Our team wants to create a database that is accessible and appealing to the current generation of teenagers and young adults. The database will include five entities: category, price, customers, shipping and website traffic. Website traffic is the dynamic entity in our database that will be classified as the “end-user” data because it is being updated on a consistent basis to allow our team to have better information on our database visitations and allows users to give us feedback on their likes and dislikes. The five entities in our database all have different attributes that make them unique. “Category”, for example, is made up of Bedroom, Bathroom, Kitchen, Clothes, and Pet Supplies. This may seem random, but our research has shown that these different types of products appeal most to consumers. In addition, “Price” is split up in two different categories. Users can sort our products from low to high price or from high to low price. “Shipping” has multiple options such as UPS Ground Shipping, Priority Shipping, 2-day Shipping, Saturday Delivery, and Next Day Shipping. Users can choose whichever they please...at a price. “Customers” is classified through gender, age, location, and customer identification number. Finally, “Website Traffic”, our end-user data, can be categorized by country, per day, per week, per year, and/or by specific user information.
The varying entities and attributes can also be categorized through their relationship to one another. For example, “Category” and “Customers” have a many-to-many relationship due to the fact that numerous users can be browsing through the different categories at the same time. In addition, “Shipping” and “Customers” have a one-to-one relationship because each customer can only choose one specific shipping option. Lastly, “Category” and “Price” have a many-to-one relationship because all of the different categories are sorted by the user selecting one specific price range.



