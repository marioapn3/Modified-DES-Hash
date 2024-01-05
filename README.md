## Modified
======================================================================================================================
Proses                 |  Before Modified                       |  After Modified
======================================================================================================================
GENERATE KEYS          |	Shifting ke kiri                      |  Shifting ke kanan
GENERATE KEYS          |  "# Jumlah pergeseranround_shifts =    |  # Jumlah pergeseran (contoh: urutan Fibonacci) 
                       |  [1, 1, 2, 2, 2, 2, 2, 2, 1, 2, 2,     |  round_shifts = [1, 1, 2, 3, 5, 8, 13, 21,
                       |  2, 2, 2, 2, 1]"	                      |  34, 55, 89, 144, 233, 377, 610, 987]
GENERATE KEYS	         |  Kunci ada 16 ( k1 - k16 )	            |  Kunci ada 16 ( k1 - k24)
GENERATE KEYS	         |                                        |  Penmbahan Tabel PC - 3
ENKRIPSI  DAN DEKRIPSI |	Rounds alur sebanyak 16 x             |  Rounds alur sebanyak 24 x
ENKRIPSI  DAN DEKRIPSI |	Menggunakan fungsi XOR	              |  Menggunakan fungsi xnor
