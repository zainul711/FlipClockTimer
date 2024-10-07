# Untuk variable targetDate untuk mendapatkan timer waktu yang akan menjadi acuan pada saat memulai atau tampilan awal.

# Pada sebuah function getTimrSegmentElements kita membuat beberapa variable untuk memilih satu elemen html yang cocok yang berisikan selektor css kemudian dikembalikan dengan fungsi return untuk disimpan kembali didalam variable kemudian nanti akan menjadi acuan selanjutnya.

# function updateSegmentValues dengan diikuti 3 parameter bertanggung jawaba dalam memperbarui nilai yang akan dihasilkan oleh 2 elemen yang berbeda pada paramenter kemudian menghasilkan nilai yang sama.

# updateTimeSegment() ini digunakan untuk memperbarui tampilan angka pada suatu segmen digital.

# untuk 3 parameter yaitu segment digital yang akan diperbarui dan ditampilkan

# pada getTimeSegmentElements untuk mendapatkan elemen html yang terkait dengan segment digital untuk menampilkan angka serta elemen overlay untuk animasi flip

# Kelas flip ditambahkan ke elemen overlay, memicu animasi flip untuk mengubah tampilan angka.

# updateSegmentValues dipanggil untuk memperbarui nilai pada bagian masing2 sesuai perintah

# finishAnimation dan kelas flip diahapus dari element oberlay untuk menghentikan animasi

# updateTimeSection untuk memperbarui tampilan waktu pada suatu bagian secrion dari sebuah tampilan digital, kemudian diikuti 2 parameter. sectionID mewakili bagian waktu yang akan diperbarui dan timeValue yaitu nilai numerik yang akan ditampilkan pada bagian tersebut

# Nilai timeValue dibagi oleh 10 dan dibulatkan ke bawah untuk mendapatkan angka pertama.

# Sisa pembagian dari timeValue oleh 10 diambil untuk mendapatkan angka kedua. Jika timeValue adalah 0, maka kedua angka akan menjadi 0.

# Fungsi updateTImeSegment untuk memperbarui segmen pertama dan kedua dengna nilai firstNumber dan secondNumber
