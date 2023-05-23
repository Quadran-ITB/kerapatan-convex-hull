# kerapatan-convex-hull
Pemetaan kerapatan Gardu Induk dengan metode Convex Hull

## API yang dibutuhkan
- [ ] get-gardu: mendapatkan data baru gardu distribsui dalam bentuk json
- [ ] get-gardu-induk: mendapatkan data baru gardu induk dalam bentuk json

## KERAPATAN WILAYAH PELAYANAN GI
- [x] Metode
  - [x] Voronoi
  - [x] Convex Hull 
  - [x] K-means
  - [x] centroid analysis
- [ ] Output Kalkulasi
  - [x] Area pelayanan GI (m2)
    - [x] eksisting
    - [x] update
  - [x] Total titik beban
    - [ ] didapat dari penjumlahan beban semua GD untuk suatu GI
  - [x] Total rekap titik beban (MW/MVA)
  - [ ] Menghitung Kerapatan GI berdasarkan
    - [ ] Beban (MW/MVA)/ m2
    - [ ] Kapasitas Trafo GD (KVA)/ m2
    - [ ] Jumlah Pelanggan / m2
    - [ ] Kapasitas Tersambung Pelanggan (kVA) / m2

## Milestone
- [ ] memberi rekomendasi peletakan GI baru dan kluster baru jika total beban melebihi kapasitas GI 
  - [ ] tidak ada yang overlap, tetap perlu diperhatikan apakah GI masih dapat menampung atau tidak, jika tidak perlu GI baru
  - [ ] distribusi fairness 
  - [ ] dirumusin math nya seperti konsep mesh network
  - [ ] GD baru nyambung ke GI mana
- [ ] kerapatan paling bagus berapa? (terkait dengan kapasitas daya GI)
- [ ] penentuan GI berdasarkan peningkatan GD
  - [ ] lokasi dimana, jarak dengan GI lama
  - [ ] luas area GI baru
  - [ ] berapa jarak ke GI lama
  - [ ] GD mana nyambung ke GI baru atau lama
  - [ ] GI baru tidak terlalu jauh dari 150 kV line
  - [ ] letak GI berdasarkan cost dan jarak, (perlu disiapkan variable pengali untuk cost)
