# Form 4L vs A3D

Interactive dashboard comparing the productivity and printing costs of the **Formlabs Form 4L** (8 hours a day) and the **HeyGears UltraCraft A3D** (24 hours a day) for Fast Model 160 µm models.

Change the resin price and discount, resin use in ml, print times, models per plate, working hours and the daily and yearly targets. Charts, key figures and the table update instantly.

## How to use

Open `index.html` in a browser, or publish the repository with GitHub Pages. Nothing to install: it is a single HTML file with CSS and JavaScript included.

## Starting values

- Form 4L: 32 models per plate, 10 minutes of printing, 5 minutes of operator time, 8.62 ml per model, resin at €445 per 5 L, investment €7,125, labour €18/h, target 60,000 models in 220 days.
- A3D: 720 models per day per printer (HeyGears), 8 models per plate, automatic part removal 90 s and automatic resin refill 150 s (A3D brochure), resin at €85 per litre.
- Formlabs resin volume discounts for a single order: 15% from 30 L, 20% from 60 L, 25% from 120 L, 30% from 240 L, 35% from 1,000 L, 40% from 2,000 L, 45% from 3,000 L. The calculation assumes one order with a year of resin.

All values can be changed on the page.

## Structure

```
index.html   the dashboard
README.md    this file
```
