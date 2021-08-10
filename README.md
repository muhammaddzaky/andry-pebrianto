Simple Anime API
Apa itu Simple Anime API?
Simple Anime API adalah sebuah Restful API sederhana tentang Anime yang dibangun menggunakan Express.js. Restful API ini menggunakan mysql sebagai DBMS-nya dan Sequelize sebagai ORM-nya.

Cara instalasi Simple Anime API
Pastikan Nodejs dan NPM terinstall dengan benar.
Clone repository ini.
Jalankan npm install.
Buat database bernama simple-anime-api lalu import file sql yang sudah disediakan pada repository ini. Anda juga bisa mengubah konfigurasi database pada file src/v1/config/database/mysql.js.
Jalankan npm run start untuk memulai server. Server akan berjalan di port 7000, namun anda dapat menyesuaikannya.
Kunjungi http://localhost:7000/v1/api/anime/api-docs untuk membuka dokumentasi dari Restful API ini.
Username dan Password untuk Authorization: admin : password.
