# Sunway BRT

## Duration

All recorded durations start/stop roughly when the train doors are closing (specifically, doors-closing light indicators flashes, or when the doors-closing announcement starts playing).

This chart emulates Singapore's SMRT duration chart shown in each of the stations, which means each station's page will also have their own duration chart for each directions. This section intends to serve both as a reference to how to construct the chart as well as the duration from each terminal stations (from which you can subtract the time taken to your destination station from the time taken to your origin station).

For each direction, the actual time taken to reach each station is added, before rounded up or down depending on whether the time / 60 is above or below .5 decimal places.

The logic here is that any underestimations will be balanced out by the overestimations.

The time measured for each stations will be available soon in a separate spreadsheet.

TIPS: Use the browser's search function to find your origin and destination stations and calculate from there.

### Towards Sunway-Setia Jaya (Northbound)

```
            USJ 7 |  0 min
                       🠟
       SOUTH QUAY |  3 min (3m18s/198s)
                       🠟
      SunU-MONASH |  6 min (2m50s/170s)
                       🠟
           SunMED |  8 min (2m06s/126s)
                       🠟
    SUNWAY LAGOON | 11 min (2m17s/137s)
                       🠟
          MENTARI | 12 min (1m40s/100s)
                       🠟
SUNWAY-SETIA JAYA | 15 min (2m43s/163s)
```

### Towards USJ 7 (Southbound)

```
SUNWAY-SETIA JAYA |  0 min
                       🠟
          MENTARI |  2 min (1m58s/118s)
                       🠟
    SUNWAY LAGOON |  4 min (1m39s/99s)
                       🠟
           SunMED |  6 min (1m57s/117s)
                       🠟
      SunU-MONASH |  8 min (2m19s/139s)
                       🠟
       SOUTH QUAY | 10 min (2m13s/133s)
                       🠟
            USJ 7 | 14 min (3m33s/213s)
```
