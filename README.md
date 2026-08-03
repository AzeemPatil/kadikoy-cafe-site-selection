# Retail Site Selection — Café Expansion in Kadıköy, İstanbul

   Where should a new café open in a district that already has 744 of them?

   Using live OpenStreetMap data, I scored 626 candidate locations across
   Kadıköy on two competing signals — local demand and competition — and
   ranked them to surface underserved pockets that still have real foot traffic.

   **Method:** demand proxy from everyday activity · distance-decay competition ·
   percentile normalization · weighted multi-criteria scoring (55% demand / 45% low-competition)

   **Tools:** Python · OSMnx · GeoPandas · NetworkX · Matplotlib

   📓 [Open the full notebook in Colab](https://colab.research.google.com/drive/1peFd-MGG6lSUI4NSZ_kwGiRlR69mbtux)
