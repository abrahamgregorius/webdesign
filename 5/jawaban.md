## Pertanyaan
Sebutkan, jelaskan, dan buatlah contoh kode masing-masing CSS Position?


## Jawaban
CSS memiliki 4 jenis posisi, diantaranya:

1. Static

    Position static adalah posisi default atau standar dari suatu elemen.

    Contoh Kode: 
    ```css
    .content {
        position: sticky;
    }
    ```

2. Relative

    Position relative memudahkan developer untuk membuat acuan dari elemen absolute. Biasanya digunakan sebagai container.

    Contoh Kode: 
    ```css
    .main-container {
        position: relative;
    }
    ```
3. Absolute

    Position absolute dapat digunakan ketika developer ingin mengatur posisi suatu elemen menggunakan satuan dalam screen secara eksplisit.

    Contoh Kode: 
    Contoh Kode: 
    ```css
    .sticker {
        position: absolute;
        top: 100px;
        left: 100px;
    }
    ```
4. Fixed

    Position fixed biasa digunakan pada navbar. Fixed dapat membuat suatu elemen ikut ter-scroll ketika terjadi scrolling oleh user.

    Contoh Kode: 
    Contoh Kode: 
    ```css
    .navbar {
        position: fixed;
        top: 0;
    }
    ```
5. Sticky

    Position sticky memiliki karakteristik yang hampir sama dengan fixed. Tetapi dengan position sticky developer dapat membuat suatu elemen ter-scroll dalam posisi tertentu

    Contoh Kode: 
    ```css
    .advertisement {
        position: sticky;
        top: 200px /* Membuat elemen advertisement berada 200px dibawah awalan halaman */
    }
    ```
