1.2. Understanding how it works.
![alt text](image.png)
<br>
Pada gambar di atas terlihat bahwa text tambahan "love you!" di print duluan baru dilanjut dengan text async. Ini dikarenakan text tambahan tersebut tidak masuk ke dalam fungsi async, saat fungsi async menggunakan future. Makanya text barunya keluar terlebih dahulu karena tidak menunggu future.

