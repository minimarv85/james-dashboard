# James Dashboard

A simple, static task dashboard.

## Usage

1. Open `dashboard.html` in your browser
2. Lists are loaded from `dashboard-data.json`

## Updating Lists

To add items, edit `dashboard-data.json`:

```json
{
  "lists": [
    {
      "id": 1,
      "name": "My List Name",
      "items": [
        { "id": 1, "text": "Task item", "completed": false }
      ]
    }
  ]
}
```

## GitHub Pages

This site is designed for GitHub Pages hosting:
1. Push to a GitHub repository
2. Enable GitHub Pages in Settings → Pages
3. Site available at: `https://yourusername.github.io/repo-name/`

## Files

- `dashboard.html` - Main dashboard UI
- `dashboard-data.json` - List data (edit this to update lists)
