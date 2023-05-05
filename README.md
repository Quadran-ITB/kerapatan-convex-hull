# kerapatan-convex-hull
Pemetaan kerapatan Gardu Induk dengan metode Convex Hull

dependencies:
  - python=3.9
  - geopandas
  - ipykernel
  - sqlalchemy
  - geoalchemy2
  - folium
  - scipy
  - numpy
  - pandas

## KERAPATAN WILAYAH PELAYANAN GI
- [x] Metode
  - [x] Voronoi
  - [x] Convex Hull 
  - [x] K-means
  - [x] centroid analysis
- [ ] Output Kalkulasi
  - [ ] Area pelayanan GI (m2)
  - [x] Total titik beban
  - [ ] Total rekap titik beban (MW/MVA)
  - [ ] Kerapatan GI
    - [ ] Beban (MW/MVA)/ m2
    - [ ] Kapasitas Trafo GD (KVA)/ m2
    - [ ] Jumlah Pelanggan / m2
    - [ ] Kapasitas Tersambung Pelanggan (kVA) / m2