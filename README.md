# Google-Maps-Review-Scraper
Scrape google maps reviews
Crawl google map reviews using google colab.
Just provide the all reviews link and set a date limit in getGoogleMapsReviews() function, it will return a dataframe containing all reviews and place info. <br>
example : getGoogleMapsReviews('https://www.google.com/maps/place/Hoover+Dam/@36.0160655,-114.7377325,17z/data=!4m8!3m7!1s0x80c92b497f82a14b:0x89d59d0bd29de37!8m2!3d36.0160655!4d-114.7377325!9m1!1b1!16zL20vMDNxNGs?authuser=0&hl=en' ,date_limit = '2022-04-01') #YYYY-MM-DD
<br> The reviews are crawled in the most recent order so when you set a pass a date limit, it will crawl every review till that date
<br> If you want to get the whole reviews just remove the date_limit parameter
<br> getGoogleMapsReviews('https://www.google.com/maps/place/Hoover+Dam/@36.0160655,-114.7377325,17z/data=!4m8!3m7!1s0x80c92b497f82a14b:0x89d59d0bd29de37!8m2!3d36.0160655!4d-114.7377325!9m1!1b1!16zL20vMDNxNGs?authuser=0&hl=en')
