# World Weather Analysis Challenge

## Deliverable 1: Retrieve Weather Data
In this deliverable, we generated 2,000 random latitudes and longitudes and retrieved the nearest city to those. We then retrieved the the current weather description for each city using an API call, and then went a step further to put it into a DataFrame with the updated weather data.

### Succesful DataFrame
Below, I have provided a screenshot of my WeatherPy Dataframe, which includes the required information (Latitude and longitude, Maximum temp.,
Percent humidity, Percent cloudiness, Wind speed, and the newly added Weather description)

<img width="850" alt="WeatherPy DF" src="https://user-images.githubusercontent.com/103979087/181164308-b8d972a8-b39d-4b23-ac9d-36aff85aa4b8.png">



## Deliverable 2: Create a Customer Travel Destinations Map 
In this second deliverable, we used input statements to retrieve customer weather preferences, then use those preferences to identify potential travel destinations and nearby hotels. We then showed those destinations with pop-up markers on a layer map to display said information.

### Succesful DF and Marker Layers Map
Both of these images show options for vacation destinations with a minimum temperature of 67 and a maximum temperature of 69.

<img width="793" alt="Vacation Search DF" src="https://user-images.githubusercontent.com/103979087/181343879-2cb6d4ff-6e1d-4b6c-bf9e-ac19942006aa.png">

<img width="1023" alt="WeatherPy_vacation_map png" src="https://user-images.githubusercontent.com/103979087/181344589-1d6d29b5-1ced-49d8-9082-aee2cf4ff979.png">


## Deliverable 3: Create a Travel Itinerary Map
In this deliverable, we use Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. We then created a map with a pop-up markers for each chosen city on the itinerary.
