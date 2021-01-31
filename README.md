# DineAt

### Description
Shows you the near by few restaurants based on price where one being too fancy and one being at cheap cost whereas the other 2 are of in between them based on the reviews and ratings too!

### The problem Dine At solves
1. When a person is new to the city, they wouldn't like spending much time on searching for a restaurant. This website will solve this issue. The main purpose of this website is to make the user work easier for someone who is new.

2. We will suggest a cheaper restaurant, a expensive restaurant and other 2 averagely rated restaurants to him such that he would feel easy to choose in a few rather than many. We have designed a factor to suggest restaurants keeping in mind about average cost, ratings, text ratings, ambience and all.

3. We will let the user know the ratings, location, types of cuisines present over there, ratings, mobile number & timings!

### Challenges we ran into
1. Being a beginner in django, we felt difficult in populating the data we got from models in our html page.

2. Rendering the pages in Javascript where each restaurant card should get a particular id and based on the card clicked, it has to navigate to another page and display the details. It took a little bit more time, used URL params which would make communication between two html pages easier!

3. Another challenge was, collecting the data from Zomato API and processing it. As the data may vary from query to query, we had to keep our data processing dynamic.

4. Defining the factor for sorting restaurants was also an area we felt difficult with, because it has to match properly for any place.

### Technologies we used
jQuery HTML Bootstrap CSS Django JavaScript RestAPIs python-pandas
