# Weather-News React App

**Create a Local language news aggregator react app which also provides weather information based on the user's geolocation. You can use open weather map API to fetch weather info - https://openweathermap.org/api You can use GnewsAPI for news info - https://gnews.io - Filter news by user's search query and language**

## Acceptance Criteria
- [ ] use ```fetch()``` to make api call.
- [ ] should able to load show weather info based on user's current location when **App** loads.
- [ ] should be able to show news info when **App** loads.
- [ ] After **App** loads completely you should have called ```fetch()``` only 2 times(one for weather-info and one for news-info).
- [ ] weather info must contain temperature and location(initially user's location, later searched location).
- [ ] news info must contain title and description of each article.
- [ ] use **Geolocation.getCurrentPosition()** for user's location.*https://developer.mozilla.org/en-US/docs/Web/API/Geolocation/getCurrentPosition*
- [ ] Only one input-box for search query to get weather-info.
- [ ] Should be able to get weather-info by entering location and pressing ```Enter``` **key**.
- [ ] Should be able to make api call based on search query for weather-info.
- [ ] Should be able to handle invalid location search query for weather-info.

***Note: please don't make unnecessary api calls***
