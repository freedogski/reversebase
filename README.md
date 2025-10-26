Use this tool if entering only a Base Score out of 20.0 with automatic breakdown into 3 Turns categories

Note: When breaking down into the 3 categories, then split is based on Carving 50%, Abs/Ext 25% and Upper Body 25%  (any extra 0.1 increments always added to the Carving Category)

Subsequently you can then use the 3 sliders for Carving, Abs/Ext and Upper Body to further refine your score


This tool  will work with PC, MAC, Android and Apple and will work in Portrait or Landscape mode.  
Sliders should work just fine with Mouse, Touch screen. 
Arrow Up/Down keys on the screen can be held for fast adjustment, or single press Up/Down for fine-tuning by 0.1 point.  
Alternatively in PC and MAC the PgUp/PgDn  and Left-Arrow, Right-Arrow keys will perform similar adjustments.   

Take and look and give me some feedback.  


You can find the link here https://freedogski.github.io/reversebase/

Alternatively there is a simplified tool here that just takes entery for each of the 3 Turns Categories https://freedogski.github.io/basescore/


----------------------------------------------

# Base Score App

A lightweight, interactive scoring tool for freestyle skiing or similar evaluation systems. This app allows users to set a **Base Score** and fine-tune subscores while providing instant visual feedback on performance categories.

---

## Live Demo

[https://freedogski.github.io/basescore/](https://freedogski.github.io/basescore/)

---

## Features

### 1. Base Score Display & Input
- Inline editable Base Score field: `Base Score = [editable box]`.
- Supports **decimal input** (period `.` or comma `,` accepted).
- Large **up/down arrow buttons** to adjust Base Score by 0.1.
- Two-way linking with sliders:
  - Editing Base Score redistributes values:
    - Carving: 50% (max 10)
    - Abs/Ext: 25% (max 5)
    - Upper Body: 25% (max 5)
  - Slider updates override Base Score afterward.

### 2. Sliders for Subscores
- Three sliders: **Carving**, **Abs/Ext**, **Upper Body**.
- Each slider includes:
  - Editable **value box**
  - Large **up/down arrows**
  - **Gradient track** (red → yellow → green, height ~80% of value box)
  - Dynamic **category labels**: Poor, Managing, Adequate, Good, Excellent
- Moving sliders updates Base Score instantly.

### 3. Category Feedback
- Dynamic **Low / Mid / High** split within each category.
- **Fade animation** when category text changes.
- Category text hides when:
  - Base Score = 0
  - Slider value = 0

### 4. Total/Base Score Category
- Displays category below Base Score with ranges:
  - Poor: 0.1–4.0
  - Managing: 4.1–8.0
  - Adequate: 8.1–12.0
  - Good: 12.1–16.0
  - Excellent: 16.1–20.0
- Each category split into Low / Mid / High:
  - Example: Excellent 16.1–20 → Low 16.1–17.3, Mid 17.4–18.6, High 18.7–20.0

### 5. Arrow Button Interactivity
- Continuous increment/decrement when holding arrow buttons.
- Both sliders and Base Score respond to up/down arrows.
- Step size: 0.1, respecting min/max limits.

### 6. Responsive Design
- Fully responsive layout with **flexbox** and **grid**.
- Category labels adapt for smaller screens using short names (P, M, A, G, E).

### 7. Visual Enhancements
- White card container with **shadow and rounded corners**.
- Gradient slider tracks provide intuitive performance visualization.
- Consistent styling for buttons, value boxes, and sliders.

### 8. Footer Link
- Centered link in the same white card:
  [https://freedogski.github.io/basescore/](https://freedogski.github.io/basescore/)
- Styled in **small text**, visually consistent.

### 9. Miscellaneous
- Prevents invalid input (negative or above max values).
- Handles rounding errors gracefully.
- Works in all modern browsers.

---

## Usage

1. Adjust the **Base Score** directly by typing or using arrow buttons.
2. Move the sliders for **Carving**, **Abs/Ext**, and **Upper Body** to fine-tune.
3. Observe instant updates to:
   - Subscore values
   - Total/Base Score
   - Category feedback
4. Category text fades in/out automatically as values change.

---

## License

This project is open-source and free to use.
