# Meal Finder

Meal Finder is a web application that helps users find meals by searching for specific ingredients or meal names. It fetches data from TheMealDB API to display meal details, including images, names, and recipes.

## Features

- Search meals by name or ingredient.
- Randomize button that displays a random meal.
- View meal details, including:
  - Meal name
  - Meal image
  - Intructions for preparation
  - Category and cuisine
  - Ingredients and measurements

## Technologies Used

- **HTML**: Structuring the application's content.
- **CSS**: Styling the user interface.
- **JavaScript**: Implementing interactivity and API calls.
- **TheMealDB API**: Providing meal data.

## Installation

To run the project locally, follow these steps:

1. Clone the repository

```bash
git clone https://github.com/ericstober/meal-finder.git
```

2. Navigate to the project directory

```bash
cd meal-finder
```

3. Open `index.html` in your web browser or use live server to view the project.

## Usage

1. Enter a keyword (meal name or ingredient) in the search bar.
2. Click the search button.
3. Browse the results displayed below the search bar.
4. Click on a meal to view its details, including the recipe and ingredients.

## API Refernce

This project uses [TheMealDB API](https://www.themealdb.com/) to fetch meal data.

### Endpoints Used:

- **Search Meal by Name**: `https://www.themealdb.com/api/json/v1/1/search.php?s=<term>`
- **Search Meal by ID**: `https://www.themealdb.com/api/json/v1/1/lookup.php?i=<id>`
- **Get Random Meal**: `https://www.themealdb.com/api/json/v1/1/random.php`

## Project Structure

```
meal-finder/
├── css/
│   └── style.css       # Stylesheet for the application
├── js/
│   └── script.js       # Main JavaScript file
├── index.html          # Main HTML file
└── README.md           # Project documentation
```

## License

This project is licensed under the MIT License.

## Acknowledgements

- [TheMealDB API](https://www.themealdb.com/) for providing meal data
- Inspiration from web development tutorials and projects.
