---
tags:
  - settings
  - configuration
cssclasses:
  - dashboard
widget-theme: mewSpin
color-override: redHawk
flashy-mode: true
widget-backgrounds: false
__preview_toggle_on: false
__preview_toggle_off: false
activities:
  - id: calories
    name: Calories
    goal: 2500
    unit: kcal
  - id: protein
    name: Protein
    goal: 150
    unit: g
  - id: carbs
    name: Carbs
    goal: 200
    unit: g
  - id: fat
    name: Fat
    goal: 65
    unit: g
---

# Settings

Configure your component library settings here.

## Theme Settings

| Setting | Value |
|---------|-------|
| Active Theme | `VIEW[{widget-theme}]` |
| Color Override | `VIEW[{color-override}]` |
| Flashy Mode | `VIEW[{flashy-mode}]` |
| Widget Backgrounds | `VIEW[{widget-backgrounds}]` |

Use the **Theme Studio** in the [[Component-Showcase]] to change these settings.

## Nutrition Goals

| Macro    | Daily Goal |
| -------- | ---------- |
| Calories | 2000 kcal  |
| Protein  | 150g       |
| Carbs    | 200g       |
| Fat      | 65g        |

Edit the `activities` in frontmatter or use the Meal Planner goals panel to adjust.
