# Kitchen AF

A meal planning and recipe management system for Obsidian, built with DatacoreJSX components.

## Features

- **Recipe Management** - Store recipes with nutritional data and smart frontmatter
- **Meal Planning** - Interactive weekly meal planner with drag-and-drop
- **Shopping Lists** - Auto-generated shopping lists from your meal plans
- **Nutrition Tracking** - Track macros (calories, protein, carbs, fat) against daily goals
- **Mobile-Friendly** - Touch-optimized components for planning on any device

## Workflow

### 1. Add Recipes

**Option A: Web Clipper**
Use the Obsidian Web Clipper to save recipes from your favorite sites. The clipper extracts recipe data automatically.

**Option B: Manual Entry**
Create a new note using the Recipe Template (`System/Templates/Recipe Template.md`).

**Recipe Frontmatter:**
```yaml
categories:
  - "[[Recipes]]"
cuisine: Italian
type: [dinner, meal-prep]
servings: 4
calories: 450
protein: 35
carbs: 40
fat: 18
author: []
url: https://example.com/recipe
rating: 4
created: 2026-01-14
last-cooked:
```

### 2. Plan Your Meals

Open the **Meal Planner** (`System/Planners/Meal Planner.md`):

- Assign recipes to each day (breakfast, lunch, dinner)
- View weekly nutrition totals
- Save meal plans for future use
- Filter recipes by cuisine, type, or diet

### 3. Generate Shopping List

The Shopping List widget automatically aggregates ingredients from your planned meals:

- Combines duplicate ingredients
- Groups by category (produce, dairy, meat, etc.)
- Check off items as you shop

### 4. Configure Goals

Edit your nutrition goals in `System/Settings.md`:

```yaml
activities:
  - id: calories
    name: Calories
    goal: 2500
    unit: kcal
  - id: protein
    name: Protein
    goal: 150
    unit: g
```

## Folder Structure

```
Kitchen AF/
├── System/
│   ├── Categories/      # Recipe categories
│   ├── Dashboards/      # Component showcase
│   ├── Meal Plans/      # Saved meal plans
│   ├── Planners/        # Meal Planner widget
│   ├── Scripts/         # DatacoreJSX components
│   ├── Templates/       # Recipe & Meal Plan templates
│   │   └── Bases/       # Obsidian Bases views
│   ├── Themes/          # UI themes
│   └── Settings.md      # Nutrition goals config
├── Examples/            # Example recipes
└── README.md
```

## Requirements

- Obsidian v1.0+
- Datacore plugin
- Minimal Theme by Kepano (recommended)
- Style Settings plugin (for theme customization)

## Quick Start

1. Install required plugins (see INSTALLATION.md)
2. Open `System/Planners/Meal Planner.md`
3. Add some recipes using the Recipe Template
4. Start planning your meals!

## Credits

Part of the AF Vault Capsule series by Rice AF.

---

<a href='https://ko-fi.com/M4M11S2NNW' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://storage.ko-fi.com/cdn/kofi6.png?v=6' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>
