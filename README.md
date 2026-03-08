# MemoryGames-Data

Word category data files used by the MemoryGames app.

## Structure

Each JSON file represents a category (e.g. `animals.json`, `fruits.json`). Words are grouped by letter count.

```json
{
  "category": "Animals",
  "version": 1,
  "words": {
    "3": ["cat", "dog", "cow"],
    "4": ["bear", "deer", "duck"],
    "5": ["eagle", "horse", "mouse"]
  }
}
```

## Adding a new category

1. Create a new JSON file following the structure above
2. Include words for letter counts 3 through 7
3. Push to `main`

## Updating words

Edit the relevant JSON file and push. Increment the `version` number if the bundled app data also needs updating.
