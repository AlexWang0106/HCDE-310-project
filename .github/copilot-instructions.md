# Context for Copilot

## Who we are

We're a pair of design students in HCDE 310, learning Python and Flask.

## How we work with AI (Stage 4: spec first)

- Don't write specs or checks for us. Before writing code, ask us for what it should do, its inputs and outputs, and 2 or 3 checks, then wait for our answer. After we write them, you may point out what's missing.
- Build in small pieces. Before you change files, tell us which ones. Don't commit.

## How we like to work

- Work on one feature at a time instead of generating the entire application at once.
- Explain the purpose of each function and the important parts of the code in simple language.
- Keep code readable and avoid unnecessary complexity.
- Use Python and Flask for the backend, HTML and CSS for the interface, and JSON for saved data.
- Allow us to review and test each change before continuing.
- When debugging, explain the cause of the problem and suggest a clear solution.

## Our project

Project name: What's in My Fridge?

Our application is designed for college students who cook for themselves but have limited ingredients, time, or cooking experience.

Users can enter ingredients they already have at home, search for matching recipes, view missing ingredients, and save their favorite recipes.

The application uses Python and Flask to manage the logic.

External data sources:
- TheMealDB API: Provides recipe information, including ingredients, instructions, and images. The free ingredient filter supports one ingredient per request.
- Open Food Facts API: Provides packaged food names and brands through product-name searches. Users select a result and confirm a generic ingredient name; some products or fields may be missing.

Depth item: Many Lenses.

The application combines recipe data, packaged food information, and the user's saved pantry to help users decide what they can cook with their available ingredients.

Data storage:
- pantry.json stores available ingredients.
- favorites.json stores saved recipes.

The application should handle empty inputs, missing results, and API failures without crashing.

## Not decided yet

- Final interface layout and visual styling.
- Whether advanced recipe filters will be included.
- Whether ingredient quantities will be used in recipe matching.
- How expiration dates will be handled.
- Whether the application will be deployed online.
- Final usability testing arrangements.

## Wrap up

When we say "wrap up": add an entry to ai_use.md with the date and the files and functions you wrote or changed, one line each, starting with "AI draft: check me." Leave "Reflection:" blank. Suggest a commit message. Don't commit until we say yes.