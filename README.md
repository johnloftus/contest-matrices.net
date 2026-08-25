# Contest Matrices

Contest Matrices is a browser-only app for analysing Cabrillo contest logs.

It helps contest operators review and compare:

- countries and entities worked by band
- CQ zones worked by band
- selected-zone activity over 30-minute UTC bins
- broad path activity over a full contest period
- contest score summary components
- two callsigns, stations, or contest years side by side

The app runs locally in the browser. Cabrillo logs are read from the user's computer and are not uploaded to a server.

## Public Site

https://contest-matrices.net

## Main Files

- `index.html` - landing page
- `contest-matrix.html` - browser app
- `contest-userguide.html` - user guide
- `Images/` - user guide screenshots
- `site.css` - shared page styling
- `favicon.svg` - browser tab icon

## Data Notes

Contest Matrix uses Cabrillo QSO lines and CTY.DAT-style prefix rules embedded in the browser app. Counts are useful for contest planning and review. Official contest results may differ after adjudication.
