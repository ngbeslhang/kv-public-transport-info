# Kelana Jaya LRT Line

## Duration

All recorded durations start/stop roughly when the train doors are closing (specifically, doors-closing light indicators flashes, or when the doors-closing announcement starts playing).

This chart emulates Singapore's SMRT duration chart shown in each of the stations, which means each station's page will also have their own duration chart for each directions. This section intends to serve both as a reference to how to construct the chart as well as the duration from each terminal stations (from which you can subtract the time taken to your destination station from the time taken to your origin station).

For each direction, the actual time taken to reach each station is added, before rounded up or down depending on whether the time / 60 is above or below .5 decimal places.

The logic here is that any underestimations will be balanced out by the overestimations.

The time measured for each stations will be available soon in a separate spreadsheet.

TIPS: Use the browser's search function to find your origin and destination stations and calculate from there.

### Towards Gombak (Northbound)

```
  PUTRA HEIGHTS |  0 min
                     🠟
    SUBANG ALAM |  3 min (2m44s/164s)
                     🠟
     ALAM MEGAH |  5 min (2m16s/136s)
                     🠟
         USJ 21 |  8 min (3m13s/193s)
                     🠟
        WAWASAN | 10 min (1m58s/118s)
                     🠟
         TAIPAN | 12 min (2m08s/128s)
                     🠟
          USJ 7 | 14 min (1m48s/108s)
                     🠟
          SS 18 | 18 min (3m29s/209s)
                     🠟
          SS 15 | 19 min (1m38s/98s)
                     🠟
    SUBANG JAYA | 22 min (2m39s/159s)
                     🠟
      GLENMARIE | 24 min (2m45s/165s)
                     🠟
  ARA DAMANSARA | 27 min (2m37s/157s)
                     🠟
  LEMBAH SUBANG | 29 min (1m45s/105s)
                     🠟
    KELANA JAYA | 32 min (2m54s/174s)
                     🠟
  TAMAN BAHAGIA | 34 min (1m51s/111s)
                     🠟
TAMAN PARAMOUNT | 36 min (2m04s/124s)
                     🠟
      ASIA JAYA | 38 min (2m15s/135s)
                     🠟
     TAMAN JAYA | 40 min (1m32s/92s)
                     🠟
     UNIVERSITI | 43 min (3m49s/229s)
                     🠟
       KERINCHI | 46 min (2m13s/133s)
                     🠟
 ABDULLAH HUKUM | 48 min (2m05s/125s)
                     🠟
        BANGSAR | 50 min (2m07s/127s)
                     🠟
     KL SENTRAL | 52 min (2m24s/144s)
                     🠟
     PASAR SENI | 55 min (2m52s/172s)
                     🠟
   MASJID JAMEK | 58 min (2m29s/149s)
                     🠟
     DANG WANGI | 59 min (1m54s/114s)
                     🠟
   KAMPUNG BARU | 61 min (1m39s/99s)
                     🠟
           KLCC | 64 min (2m48s/168s)
                     🠟
    AMPANG PARK | 66 min (1m36s/96s)
                     🠟
          DAMAI | 67 min (1m52s/112s)
                     🠟
  DATO' KERAMAT | 69 min (1m56s/116s)
                     🠟
        JELATEK | 71 min (1m40s/100s)
                     🠟
    SETIAWANGSA | 73 min (1m42s/102s)
                     🠟
     SRI RAMPAI | 77 min (3m49s/229s)
                     🠟
    WANGSA MAJU | 79 min (2m32s/152s)
                     🠟
   TAMAN MELATI | 82 min (3m/180s)
                     🠟
         GOMBAK | 86 min (3m30s/210s)
```

### Towards Putra Heights (Southbound)

```
!!! IGNORE, TO BE FULLY REWRITTEN FROM SCRATCH !!!

      == GOMBAK ==
    4 min 🠉 🠟 4 min
   == TAMAN MELATI ==
    3 min 🠉 🠟 3 min
   == WANGSA MAJU ==
    3 min 🠉 🠟 2 min
   == SRI RAMPAI ==
    4 min 🠉 🠟 4 min
   == SETIAWANGSA ==
    2 min 🠉 🠟 3 min
     == JELATEK ==
    2 min 🠉 🠟 3 min
  == DATO' KERAMAT ==
    2 min 🠉 🠟 3 min
       == DAMAI ==
    2 min 🠉 🠟 3 min
    == AMPANG PARK ==
    2 min 🠉 🠟 2 min
       == KLCC ==
    3 min 🠉 🠟 2 min
   == KAMPUNG BARU ==
    2 min 🠉 🠟 Continue from 2m48s in DJI_0157.mp4
   == DANG WANGI ==
    2 min 🠉 🠟 
   == MASJID JAMEK ==
    3 min 🠉 🠟 
    == PASAR SENI ==
    3 min 🠉 🠟 
    == KL SENTRAL ==
    3 min 🠉 🠟 
      == BANGSAR ==
    3 min 🠉 🠟 
 == ABDULLAH HUKUM ==
    3 min 🠉 🠟 
     == KERINCHI ==
    3 min 🠉 🠟 
    == UNIVERSITI ==
    4 min 🠉 🠟 
    == TAMAN JAYA ==
    2 min 🠉 🠟 
    == ASIA JAYA ==
    3 min 🠉 🠟 
 == TAMAN PARAMOUNT ==
    3 min 🠉 🠟 
  == TAMAN BAHAGIA ==
    2 min 🠉 🠟 
   == KELANA JAYA ==
    3 min 🠉 🠟 
   == LEMBAH SUBANG ==
    2 min 🠉 🠟 
  == ARA DAMANSARA ==
    3 min 🠉 🠟 
     == GLENMARIE ==
    3 min 🠉 🠟 
   == SUBANG JAYA ==
    3 min 🠉 🠟 
       == SS 15 ==
    2 min 🠉 🠟 
       == SS 18 ==
    4 min 🠉 🠟 
       == USJ 7 ==
    2 min 🠉 🠟 
      == TAIPAN ==
    3 min 🠉 🠟 
      == WAWASAN ==
    2 min 🠉 🠟 
      == USJ 21 ==
    4 min 🠉 🠟 
     == ALAM MEGAH ==
    3 min 🠉 🠟 
     == SUBANG ALAM ==
    3 min 🠉 🠟 
     == PUTRA HEIGHTS ==
```
