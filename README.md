# Refleksi

Nama: Emir Mohamad Fathan <br>
NPM: 2206081982

- Screenshot for 1.2
![image](https://github.com/brofathan/grpc-tutorial/assets/45114836/0a8af0a0-fd2d-44c1-9d6c-93ea02432964)
- Terlihat bahwa string "hey hey!" di-print terlebih dahulu setelah itu baru kedua string di dalam method spawner. Hal ini karena spawner dijalankan secara asinkronus di mana baris-baris kode di bawah spawner akan dijalankan saat spawner dijalankan. Setelah menunggu 2 detik, barulah "howdy" di-print.