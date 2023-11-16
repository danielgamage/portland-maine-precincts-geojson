# Portland, ME Precinct GeoJSON

Includes GeoJSON for the council (and voting) precincts of Portland, ME as `portland-precincts.geojson`. Voting data is reported by precinct, so you may find the GeoJSON useful for representing political outcomes as they relate to geographic areas of the city.

Precinct keys are noted in the metadata, e.g.:

```json
{
  "properties": {
    "name": "4-1"
  }
}
```

> [!NOTE]
> The key `1-2` is included in three separate polygons

## Sources

- [Official PDF](https://content.civicplus.com/api/assets/86d4fb4a-dfa5-49d4-9418-d6f203b75065?cache=1800), converted to SVG and then GeoJSON with additional adjustments
