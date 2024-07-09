---
sidebar_position: 3
---

Secara konsep SWITCH...CASE sama dengan IF...ELSE, hanya saja secara
penulisan lebih rapi dah juga digunakan pada kasus tertentu. Statement Switch
memastikan persamaan antara, nilai 1 dengan nilai yang ada pada case didalam
Switch. Apabila nilai sama, maka operasi akan di eksekusi.

**![](https://lh7-us.googleusercontent.com/docsz/AD_4nXfDS6vcCiGxYyqf8rbr1xQj6kRZcORg24GJTrpWw5oWhCllvKgqDakhEwbry3-5nVhraCEOX8OBVsynGWSSlrT-X_sQvHWPxSq2jtHZAXxd1YCO3yG6p8Oh-8lbBKcOfN5tZeSq7VGgiBbocbUh55n5d6I?key=93UFQwWUByfaXAM7YbD_TA)**

Didalam sebuah pernyataan Switch terdapat beberapa pernyataan case,apabila
variabel yang dituju sama nilainya dengan nilai case maka pernyataan dalam case
akan di eksekusi.
Contoh Program Switch..Case

**![](https://lh7-us.googleusercontent.com/docsz/AD_4nXcUSUCQ1nh_aRtWiOYsf0PH2ShbNhu1TP9o6oob2TnvIVkQmH_wZf0lbJbg5jc7VJ_9eK3_MCh6lvu1P6WFwRtw4_5PKh5UEaCmQ_TfeR2lMsHDkf7B-WiAtuOp_0dn5pQjEtDjJKNd5UxiiGGg-K2Cu3_b?key=93UFQwWUByfaXAM7YbD_TA)**

Perhatikan contoh diatas, kasus diatas memiliki fungsi untuk membandingkan
usia. Namun, statement switch...case adalah pilihan yang tidak tepat, karena
pada switch case tidak bisa menggunakan operator pembanding, sehingga nilai
yang terbaca hanya akan dinilai sama atau tidak sama dengan nilai yang ada,
jadi kita tidak bisa menerapkan range usia.
Saat menggunakan pernyataan Switch jangan lupa menambahkan break pada
akhir case. Didalam pernyataan Switch terdapat kata default, nah apakah
default itu? sama halnya dengan Else pada statement IF, default dapat
difungsikan sebagai penolakan apabila nilai variabel tidak ada yang sama
dengan Case pada statement Switch.