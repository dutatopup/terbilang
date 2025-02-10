# Rumus Terbilang
Add-ins Rumus Terbilang untuk Microsoft Office 2010 keatas

Hanya untuk Microsoft Office 2010 keatas
========================================

Untuk menggunakan rumus terbilang dalam excel harap lakukan langkah sebagai berikut : 
1. Buka Microsoft Excel 
2. Pilih menu File - Options
3. Pilih menu Add-ins
4. Pada menu Add-ins, lihat dipaling bawah ada pilihan Manage: Excel Add-ins dan pilih Go
5. Pilih Browse dan cari dimana letak menyimpan file Terbilang.xlam - OK
6. Centang pada pilihan Terbilang, kemudian klik OK


Penggunaan
==========
Rumus terbilang ada 2 kategori dan 2 bahasa

Misal disini angka berada pada kolom A1 berisi angka 12345

=terbilang(A1)		; menghasilkan bilangan dalam bahasa Indonesia

    : Dua Belas Ribu Tiga Ratus Empat Puluh Lima 
=terbilangen(A1) 	; menghasilkan bilangan dalam bahasa Inggris

    : Twelve Thousand Three Hundred Forty Five
=angka(A1) 		; menghasilkan satuan nilai dari angka secara harfiah dalam bahasa Indonesia

    : Satu Dua Tiga Empat Lima
=angkaen(A1) 		; menghasilkan satuan nilai dari angka secara harfiah dalam bahasa Inggris

    : One Two Three Four Five


Rumus tersebut juga bisa dikombinasikan dengan rumus lainnya misal UPPER dan LOWER

=UPPER(terbilang(A1))

=LOWER(terbilangen(A1))

dan seterusnya
