# Refleksi

Nama: Emir Mohamad Fathan <br>
NPM: 2206081982

<hr>
<hr>

- Screenshot for 1.2
![image](https://github.com/brofathan/grpc-tutorial/assets/45114836/0a8af0a0-fd2d-44c1-9d6c-93ea02432964)
- Terlihat bahwa string "hey hey!" di-print terlebih dahulu setelah itu baru kedua string di dalam method spawner. Hal ini karena spawner dijalankan secara asinkronus di mana baris-baris kode di bawah spawner akan dijalankan saat spawner dijalankan. Setelah menunggu 2 detik, barulah "howdy" di-print.

<br>

- Screenshot for 1.3 (without drop)
![image](https://github.com/brofathan/grpc-tutorial/assets/45114836/0344e8fb-fbb0-4196-9716-fce34af736b1)
- Tanpa method drop, maka spawner tidak berhenti dan terus menunggu jika ada program selanjutnya yang ingin dieksekusi spawner. Untuk urutan pada multiple spawn, jelas program akan menjalankan spawn yang lebih dulu. Setelah itu masing-masing spawner menunggu 2 detik untuk print "done".

- Screenshot for 1.3 (with drop)
![image](https://github.com/brofathan/grpc-tutorial/assets/45114836/7b6a9045-4add-4d18-b654-c1e191b9379e)
- Dengan method drop, spawner berhenti setelah tidak ada lagi kode yang dieksekusi.