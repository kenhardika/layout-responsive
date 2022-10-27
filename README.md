# layout-responsive
Layout Grid and Responsive, basic task for MEA

Dalam task kali ini, kita menggunakan element main yang berisi beberapa section.
Ketika viewing width ditarik lebar, maka section akan melebar mengikuti ruang kosongnya, hal ini terjadi karena kita menggunakan auto-fit dan minmax.

## Auto-fit + minmax
Auto fit akan mengisi space kosong dengan memaksimalkan semua elemen dengan space yang dimiliki, elemen bisa pindah ke row selanjutnya jika space penuh dan elemen bisa membesar jika space kosong. Minmax bertanggung jawab atas besar kecilnya value height & width elemen, kali ini minmax diisi dengan dua value, satu fixed value dan satu relative agar dapat memaksimalkan space kosong yang ada. 

## nth:child(2n) 
Memilih selector dengan nth:child(2n) maka memilih semua elemen dengan kelipatan dua. Maka child element dengan urutan angka genap akan terpilih.

## nth:child(2n+1) 
Memilih selector dengan nth:child(2n+1) maka memilih semua elemen dengan kelipatan dua plus satu. Maka child element dengan urutan angka ganjil akan terpilih.
