# python-api-challenge

This is a two part challenge designed to reinforce API knowledge.

## Weather
In the first part, we use an API to obtain weather information from around the world. We then use that information to look for trends in relation to the equator using matplotlib and scipy.

What we found was that, while there is a strong correlation between temperature and latitude, there is little to no correlation between other aspects of weather and latitude. 

Note:

In order to succesfully run this code, citipy will need to be installed and an api key must be obtained.

## Vacation

For the second part of the challenge, we use weather data to plan a vacation! My favorite weather is overcast with high humdity and temperatures in the 50's to 70's. So these are the parameters I will be using. When you run the code, feel free to change it to your perfect weather conditions (and cross your fingers it will work right!). Because I don't like having too many options, I chose to limit my vacation options to 5 cities. However, this can be easily altered by changing the number of options variable. 

I began by importing the data from the Weatherpy challenge and reading it into a dataframe. I then filtered the dataframe for my preferences regarding humidity, temperature, and cloudiness. From this dataframe of places with perfect weather, I took a sample of 5 and found an hotel in each location. Finally, I marked these locations on a map. 


Note:

In order to succesfully run this code in jupyter notebook, the gmaps extension must be enabled and an api key must be obtained.
