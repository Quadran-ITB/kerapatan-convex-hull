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

## Milestone
- [ ] memberi rekomendasi GD baru nyambung ke GI mana
- [ ] kerapatan paling bagus berapa? (terkait dengan kapasitas daya GI)
- [ ] penentuan GI berdasarkan peningkatan GD
  - [ ] lokasi dimana
  - [ ] luas area GI baru
  - [ ] berapa jarak ke GI lama
  - [ ] GD mana nyambung ke GI baru atau lama
  - [ ] GI baru tidak terlalu jauh dari 150 kV line
  - [ ] letak GI berdasarkan cost dan jarak, (perlu disiapkan variable pengali untuk cost)

