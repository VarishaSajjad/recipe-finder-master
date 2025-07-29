🍜 Recipe Finder

Recipe Finder is a Flutter-based mobile app that helps users discover delicious recipes by simply entering available ingredients. Users can explore detailed recipe instructions, browse through dish images, and save their favorites for later.

📱 Screenshots

| Ingredient Entry | Search Recipes | Browse Dishes | Recipe Details |
|:----------------:|:--------------:|:--------------:|:---------------:|
| <img src="https://github.com/nixtomalon/Recipe-Finder/blob/master/assets/screenshots/1.png" width="185"/> | <img src="https://github.com/nixtomalon/Recipe-Finder/blob/master/assets/screenshots/2.png" width="185"/> | <img src="https://github.com/nixtomalon/Recipe-Finder/blob/master/assets/screenshots/3.png" width="185"/> | <img src="https://github.com/nixtomalon/Recipe-Finder/blob/master/assets/screenshots/4.png" width="185"/> |

✨ Features

- Search by Ingredients – Input available ingredients and get recipes that match.
- Detailed Recipes – Each recipe includes title, image, and ingredients list.
- Favorites – Save your favorite recipes (feature can be extended).
- Fast and responsive Flutter UI.

🔌 API Used

This app uses the Spoonacular API to fetch recipe suggestions and ingredient details.

Note:  
To use the API, create a free account on https://spoonacular.com/food-api, get your API key, and replace the placeholder key in the project.

🚀 Getting Started

Installation

git clone https://github.com/nixtomalon/recipe-finder.git
cd recipe-finder
flutter clean
flutter pub get
dart run build_runner build
flutter run
