# abd2uhyouronlinecoach

A simple **static website** for online gym coaching that generates:
- a **gym split** (3–6 days/week)
- a **7-day meal plan** with **exact portions** (eggs, grams of bread, grams of chicken/rice, etc.)
- a built-in **calorie & macro tracker**

It runs fully in the browser (no backend).

---

## Features

### 1) Program Generator
Users enter:
- Age
- Gender (male / female)
- Weight (kg)
- Height (cm)
- Goal (build muscle / lose weight / gain weight)
- Training days per week (3–6)
- Optional: activity level + diet preference

The website generates:
- Estimated maintenance calories + target calories
- Daily macros (protein/carbs/fats)
- Gym split plan (sets + reps)
- 7-day weekly food program with exact amounts

### 2) Gender-based images
- If **male** is selected → male hero image
- If **female** is selected → female hero image

### 3) Weekly meal plan with exact values
Meal plan includes realistic portions like:
- number of **eggs**
- grams of **bread**
- grams of **chicken / rice / pasta / potatoes**
- vegetables + olive oil suggestions
And it varies across 7 days for more diversity.

### 4) Calorie Tracker
Users can log food daily:
- choose from common foods (eggs, oats, chicken, rice, etc.)
- input grams (or units for eggs)
- optional “custom calories” item
Shows:
- total calories + macros
- progress bars vs targets
Data is saved in the browser (localStorage), per day.

### 5) Personal Coaching Offer
Pricing section contains **one offer**:
- **Personal Coaching via Instagram or WhatsApp — €80/month**

### 6) Contact the coach
Included contact methods:
- Instagram: @abd2uhyouronlinecoach
- WhatsApp: +358408145114
- Email: abd2uhyouronlinecoach@gmail.com

---

## Tech Stack
- HTML + CSS + Vanilla JavaScript
- No server / no database
- Runs offline

---

## Run Locally

### Option 1 (fastest)
Just open:
`index.html`

### Option 2 (recommended local server)
```bash
cd abd2uhyouronlinecoach
python -m http.server 8080
