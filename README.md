# Foodie Khek Telegram Bot
## About
What shall we eat today? What good food can I find in this area? 

Sounds familiar? To solve this problem, I decided to spend my winter break building a simple telegram bot that generate food choices from my preferred location.
The list of food choices were scrapped from [**DanialFoodDiary**](https://danielfooddiary.com/) using Python. As DanialFoodDiary does not provide the option to zoom into places nearby a particular MRT station, I had to map the addresses to the nearest MRT Station and this was done through [**OneMapSG**](https://www.onemap.gov.sg/main/v2/).

5 places are randomly selected to avoid choice paralysis. The user is free to re-select and generate new set of choices if they are not satisfied with the suggestions.

## Demo
![foodie_khek](https://user-images.githubusercontent.com/53141849/145506508-8cb49207-3e11-49a5-8374-9a585dc50e2d.gif)

## Future Work
I plan to incorporate other food blogs to expand the current database
