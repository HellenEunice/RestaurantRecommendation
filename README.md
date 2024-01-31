# RestaurantRecommendation
This Data Science project aims to create a restaurant recommendation system based on the user's location.

![Restaurant recommendation](https://github.com/HellenEunice/RestaurantRecommendation/assets/145653265/fe9d37fd-292d-4de3-ac82-4f683e4c74ae)

## Objetive
- Develop a restaurant recommendation system that suggests top restaurants based on the user's geographical location.

## Tecnologías Usadas
- `Programming Language:` Python
- `Libraries:` Numpy, Pandas, Scikit-Learn, Folium, Geopandas
- `Visualization:` Matplotlib, Seaborn, Plotly Express
- `Models:` K Means

## Data
This project utilizes the Yelp Business Public Dataset. The dataset contains various types of businesses in the USA, with a focus on restaurants for this project.

## EDA
The exploratory data analysis provides insights into the top restaurants and highlights cities with the best restaurants. Additionally, there is a map visualizing the geographical distribution of the restaurants in the dataset.

![estrellas vs reviews](https://github.com/HellenEunice/RestaurantRecommendation/assets/145653265/c805c162-b728-4235-b048-ef364b7ef3e9)

![cities](https://github.com/HellenEunice/RestaurantRecommendation/assets/145653265/fc9d129d-d911-4d17-8af6-1ec2e3cfc105)

![map](https://github.com/HellenEunice/RestaurantRecommendation/assets/145653265/2da6278f-a6c9-4a42-ac2c-40d16509d4f1)

## K means
The project implements a clustering method using K Means based on the top restaurants in Las Vegas. The restaurants are grouped into 5 clusters for better analysis and recommendation.

![clusters Las vegas](https://github.com/HellenEunice/RestaurantRecommendation/assets/145653265/8811c375-fcb6-435a-9e60-07372b6f1ea8)

## Recommendation based on location
The recommendation system functions as follows:
1. **User Input:** Users provide their geographical coordinates (longitude and latitude).
2. **Cluster Assignment:** The system uses K Means clustering to assign the user to a specific cluster based on their location.
3. **Top Restaurant Recommendations:** The system recommends five top-rated restaurants from the cluster assigned to the user.
4. **Map Visualization:** The recommended restaurants are plotted on a map for users to explore visually.

![recommendation by location](https://github.com/HellenEunice/RestaurantRecommendation/assets/145653265/4e5296bd-75bf-453a-adf2-96f2f67b639f)

