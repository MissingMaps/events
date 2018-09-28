### Adding events

When you edit events.csv events automatically get changed on the main website. To add an event, edit the events.csv.

When updating the csv of events:

- If adding events from the database of submissions via the google form, you will need to add the coordinates manually at the start of the row. This can easily be done by opening the OSM location link and copying the coords from the URL. Make sure lat / long are separated by a comma as the URL will use a "/" instead.

- Use `yyyy-mm-dd` format for date. The year must be 4 digits (may need to adjust display settings in Microsoft Excel). Otherwise, 15 may be interpreted as 1915 instead of 2015.

```
new Date("9/15/15")
Date 1915-09-15T04:00:00.000Z
new Date("9/15/2015")
Date 2015-09-15T04:00:00.000Z
```
- Fields can be left blank if data does not exist or is TBD

- Strings need to be wrapped in these characters `"Event title"` not these `“Event title”`

- Include the two letter country code to include the correct flag

- Double quotes inside strings need to be typed twice (e.g `,"Congress Centre ""Le Manège"", Chambéry, France",`)
