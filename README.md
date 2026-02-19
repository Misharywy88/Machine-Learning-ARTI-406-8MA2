# Ramen Ratings Dataset

## Overview

This dataset contains **2,580 ramen noodle product reviews** collected and rated by "The Ramen Rater" (ramenratings.com), one of the most well-known independent ramen review sources.

Each row represents one reviewed ramen product with its brand, flavor/variety name, packaging style, country of origin, star rating (out of 5), and whether it appeared in any annual Top Ten list.

**File name**: `ramen-ratings.csv`  
**Rows**: 2,580  
**Columns**: 7  
**Time span covered**: Approximately early 2000s – mid 2020s (reviews added sequentially)

## Columns

| Column      | Description                                                                 | Data Type    | Notes / Possible Values                              |
|-------------|-----------------------------------------------------------------------------|--------------|-------------------------------------------------------|
| Review #    | Sequential review ID (higher number = more recent review)                  | Integer      | 2580 → newest, 1 → oldest                             |
| Brand       | Name of the ramen brand/manufacturer                                       | String       | Nissin, Samyang, Indomie, MyKuali, Mama, etc.         |
| Variety     | Specific flavor/product name                                               | String       | Very long & descriptive (e.g. "Buldak Bokkeummyun")   |
| Style       | Packaging/format                                                           | String       | Cup, Pack, Bowl, Tray, Box                            |
| Country     | Country where the product is produced/marketed                             | String       | Japan, South Korea, USA, Thailand, Indonesia, etc.    |
| Stars       | Rating given by The Ramen Rater (0–5 scale)                                | Float/String | 0.0–5.0, occasionally "Unrated"                       |
| Top Ten     | Indicates if this product appeared in any annual Top Ten list              | String       | Year & rank (e.g. "2013 #1") or empty/NaN             |

## Key Statistics (approximate – based on full dataset)

- Total reviews: **2,580**
- Missing values:
  - `Style`: ~2 rows
  - `Top Ten`: ~2,539 rows (only ~41 products ever made a Top Ten list)
  - `Stars`: 0 (but a few are string "Unrated")
- Rating distribution:
  - Average rating: ~3.7–3.8 stars
  - Highest ratings (5.0): more common in recent years
  - Lowest ratings (≤1.0): mostly older/cheap products
- Most reviewed countries: Japan, United States, South Korea, Taiwan, Thailand, Indonesia, Malaysia, China, Singapore, Vietnam
- Most common styles: Pack > Cup > Bowl > Tray > Box

## Interesting Observations

- Ratings have generally trended **upward** over time (newer reviews tend to be higher-rated on average).
- Perfect 5.0 scores became much more frequent after ~Review #1800–2000.
- Very low scores (<1.5) are almost nonexistent in the most recent ~800–1,000 reviews.
- Iconic high-rated products often come from: MyKuali (Malaysia), KOKA (Singapore), premium Samyang lines, Indomie Mi Goreng variants.

## Source & License

- Original source: [The Ramen Rater](https://www.theramenrater.com/) database (publicly shared versions widely used in data science projects)
- Commonly found on: Kaggle, GitHub, academic assignments
- License: Public domain / fair use for educational & non-commercial purposes

## Recommended Citations

If you use this dataset in your work:

> The Ramen Rater. (n.d.). Ramen Ratings Dataset. Retrieved from https://www.theramenrater.com/

> (Kaggle version if applicable): https://www.kaggle.com/datasets/residentmario/ramen-ratings

---