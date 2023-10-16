# Pencerdasan ILITS 2024

## BPH & Staffli

Kadiv: Ainun </br>
Wakadiv: Agnes </br>
Sekben: Farrell </br>

Lead Frontend: Reynaldi </br>
Staffli Frontend: Bhisma, Dzaky, Farrell </br>

Lead Backend: Jasmine </br>
Staffli Backend: Unedo, Zharif, Rio </br>

Lead UI/UX: Shinta </br>
Staffli UI/UX: Dian, Hafiz, Yuma </br>

## Workflow

Workflow ILITS 2024 menggunakan sistem agile project management yang terdiri dari sprint dan scrum.

## Tech Stack

### Next JS

Next.js adalah kerangka kerja JavaScript sumber terbuka (open source) yang digunakan untuk membuat aplikasi web dengan cepat dan mudah menggunakan React. Next.js dirancang untuk mempercepat proses pengembangan aplikasi web dengan menyediakan fitur-fitur seperti server-side rendering (SSR), pre-rendering, dan optimasi performa.

Fitur-fitur Next.js seperti server-side rendering dan pre-rendering memungkinkan aplikasi web untuk lebih cepat dimuat dan lebih mudah diakses oleh pengguna. Selain itu, Next.js juga menyediakan fitur-fitur seperti hot module replacement (HMR) dan code splitting, yang membantu pengembang untuk mempercepat proses pengembangan dan meningkatkan performa aplikasi web.

Next.js juga memiliki integrasi dengan beberapa teknologi terbaru seperti GraphQL, TypeScript, dan styled-components, yang membuatnya menjadi pilihan yang populer bagi banyak pengembang web.

#### Data Fetching

Data Fetching:
Next.js menyediakan dua cara untuk melakukan data fetching pada aplikasi web, yaitu server-side rendering (SSR) dan client-side rendering (CSR). SSR memungkinkan data diambil sebelum halaman di-render, sedangkan CSR memungkinkan data diambil setelah halaman di-render.

Next.js menyediakan API getServerSideProps dan getStaticProps untuk melakukan SSR, dan API useEffect atau useSWR untuk melakukan CSR. getServerSideProps digunakan untuk mengambil data pada setiap permintaan server, sedangkan getStaticProps digunakan untuk mengambil data saat build aplikasi web.

Data fetching pada Next.js sangat membantu dalam mempercepat performa aplikasi web, karena dapat mengurangi waktu load data pada aplikasi web dan membuat pengalaman pengguna menjadi lebih baik.

#### SSR dan CSR

CSR atau juga dikenal sebagai client-side rendering, adalah teknik rendering dimana semua proses rendering dilakukan pada sisi klien atau di browser. Dalam CSR, setelah HTML dan JavaScript diunduh dari server, JavaScript akan menangani rendering dan membangun tampilan website di sisi klien. Hal ini dapat menghasilkan tampilan website yang sangat interaktif, namun proses rendering akan memakan waktu di sisi klien, terutama jika website memiliki banyak konten yang kompleks.

SSR atau juga dikenal sebagai server-side rendering, adalah teknik rendering dimana sebagian besar proses rendering dilakukan pada sisi server. Dalam SSR, server akan melakukan proses rendering HTML yang siap untuk diunduh oleh browser dan membangun tampilan website sebelum dikirim ke klien. Hal ini mengurangi waktu pemuatan website karena tidak ada proses rendering yang dilakukan di sisi klien, namun dapat mengurangi interaktivitas website karena tidak semua proses rendering dilakukan di sisi klien.

Untuk memahami lebih detail tentang Next JS, silahkan kunjungi [https://nextjs.org/docs](https://nextjs.org/docs) untuk melihat dokumentasi lengkapnya.

### TypeScript

TypeScript adalah bahasa pemrograman open-source yang dikembangkan oleh Microsoft. TypeScript adalah `superset` dari JavaScript, yang berarti semua sintaksis dan fitur JavaScript juga tersedia di TypeScript, tetapi dengan penambahan kemampuan `tipe` (type) yang lebih kuat.

Kelebihan TypeScript antara lain:

1. Kemampuan tipe yang lebih kuat, sehingga kode menjadi lebih terstruktur dan mudah dipahami, serta memungkinkan untuk mendeteksi kesalahan pada saat kompilasi.
2. Meningkatkan produktivitas pengembang dengan memungkinkan otomatisasi refaktorisasi kode, dukungan untuk refactor yang lebih aman, dan fitur editor IntelliSense yang canggih.
3. TypeScript menawarkan fitur-fitur modern seperti async/await, dekorator, dan banyak lagi.
4. Lebih mudah untuk melakukan debugging kode TypeScript.

Kekurangan TypeScript antara lain:

1. Tidak semua pengembang atau tim pengembangan mengerti TypeScript, sehingga membutuhkan waktu belajar yang lebih lama.
2. Kode TypeScript memerlukan waktu kompilasi lebih lama daripada kode JavaScript biasa, karena memerlukan tahap kompilasi tambahan.
3. Kurangnya dukungan untuk beberapa pustaka JavaScript, terutama pustaka yang belum ditingkatkan ke TypeScript atau pustaka yang kurang populer.

#### Perbedaan TypeScript dan JavaScript

TypeScript dan JavaScript adalah dua bahasa pemrograman yang saling terkait, namun memiliki perbedaan-perbedaan berikut ini:

1. Tipe Data</br>
   JavaScript merupakan bahasa pemrograman yang bersifat dinamis, sehingga tipe data variabel bisa berubah-ubah sepanjang program berjalan. Sementara itu, TypeScript merupakan bahasa pemrograman yang statis, sehingga tipe data variabel harus didefinisikan pada saat penulisan kode.
2. Kompilasi </br>
   JavaScript dieksekusi secara langsung oleh browser atau runtime environment lainnya, sedangkan TypeScript harus dikompilasi terlebih dahulu menjadi JavaScript sebelum bisa dijalankan.
3. Fitur Baru </br>
   TypeScript memiliki fitur-fitur baru yang belum tersedia pada JavaScript, seperti interface, generic, union type, dan lain-lain.

Untuk memahami lebih detail tentang TypeScript, silahkan kunjungi [https://www.typescriptlang.org/docs/](https://www.typescriptlang.org/docs/) untuk melihat dokumentasi lengkapnya.
Atau bisa juga kunjungi
https://youtube.com/playlist?list=PLNqp92_EXZBJ4CBroxVBJEpAXoz1g-naZ untuk melihat video tutorial lengkapnya.

### React Hook Form

React Hook Form adalah pustaka (library) formulir (form) open-source untuk React yang memungkinkan pengembang untuk membuat formulir yang fleksibel, mudah dipelajari, dan mudah diimplementasikan. React Hook Form memanfaatkan React Hooks untuk mengelola keadaan formulir dan ketergantungan input yang dikumpulkan dari pengguna. Dengan React Hook Form, pengembang dapat dengan mudah mengambil nilai input, melakukan validasi, menampilkan pesan kesalahan, dan mengirimkan data formulir tanpa perlu menulis banyak kode boilerplate. React Hook Form juga memiliki dukungan untuk integrasi dengan pustaka validasi lainnya, seperti Yup dan Joi.

#### Kelebihan React Hook Form

- Performa yang baik: React Hook Form hanya melakukan render ulang pada komponen yang terkait dengan perubahan yang terjadi pada form. Hal ini membuat performa dari aplikasi yang menggunakan React Hook Form menjadi lebih cepat.

- Penggunaan yang mudah: React Hook Form memiliki API yang sangat sederhana dan mudah dipahami, sehingga memudahkan penggunaannya.

- Dukungan TypeScript: React Hook Form telah dioptimalkan untuk digunakan dengan TypeScript sehingga membantu para pengembang dalam menulis kode yang lebih aman dan terstruktur.

- Ukuran kode yang kecil: Ukuran kode dari React Hook Form sangat kecil sehingga mempercepat proses loading aplikasi.

- Validasi form yang fleksibel: React Hook Form menyediakan banyak pilihan validasi form yang dapat digunakan, seperti required, pattern, minLength, dan sebagainya.

Dengan kelebihan-kelebihan tersebut, React Hook Form dapat menjadi pilihan yang tepat untuk manajemen form di aplikasi React, terutama untuk aplikasi yang kompleks dan memerlukan performa yang cepat.

Dokumentasi lengkap React Hook Form dapat dilihat di [https://react-hook-form.com/](https://react-hook-form.com/). Untuk mempelajari lebih lanjut tentang React Hook Form, silahkan kunjungi [https://youtube.com/playlist?list=PL03g4H_exuTppOgtY-45oWvN79rvJIKzf](https://youtube.com/playlist?list=PL03g4H_exuTppOgtY-45oWvN79rvJIKzf) untuk melihat video tutorial lengkapnya.

### Zustand

Zustand adalah sebuah library state management untuk React yang memiliki beberapa kelebihan seperti:

- Performa yang baik: Zustand mengoptimalkan performa state management pada aplikasi React dengan memanfaatkan fitur Context API yang sudah disediakan oleh React.

- Mudah digunakan: Zustand memiliki API yang sangat sederhana dan mudah dipahami sehingga memudahkan penggunaannya.

- Dukungan TypeScript: Zustand telah dioptimalkan untuk digunakan dengan TypeScript sehingga membantu para pengembang dalam menulis kode yang lebih aman dan terstruktur.

- Ukuran kode yang kecil: Ukuran kode dari Zustand sangat kecil sehingga mempercepat proses loading aplikasi.

- Mudah diintegrasikan: Zustand dapat diintegrasikan dengan React Hooks sehingga memudahkan penggunaan dalam aplikasi React.

Dengan kelebihan-kelebihan tersebut, Zustand dapat menjadi pilihan yang tepat untuk state management pada aplikasi React, terutama untuk aplikasi yang kompleks dan memerlukan performa yang cepat.

Dokumentasi lengkap Zustand dapat dilihat di https://zustand-demo.pmnd.rs/. Untuk mempelajari lebih lanjut tentang Zustand, silahkan kunjungi https://youtu.be/sqTPGMipjHk untuk melihat video tutorial lengkapnya.

### React Query

React Query adalah sebuah library untuk mengelola data pada aplikasi React dengan cara yang mudah, intuitif, dan performant. Beberapa kelebihan dari React Query antara lain:

- Performa yang cepat: React Query menyediakan fitur caching dan pagination untuk mengoptimalkan performa aplikasi.

- Mudah digunakan: React Query memiliki API yang sangat sederhana dan mudah dipahami, sehingga memudahkan penggunaannya.

- Dukungan TypeScript: React Query telah dioptimalkan untuk digunakan dengan TypeScript sehingga membantu para pengembang dalam menulis kode yang lebih aman dan terstruktur.

- Kompatibilitas dengan berbagai jenis data: React Query dapat digunakan dengan berbagai jenis data seperti REST APIs, GraphQL, dan Firebase.

- Mendukung penggunaan hooks: React Query menggunakan hooks sehingga mempermudah integrasinya dengan aplikasi React.

Dengan kelebihan-kelebihan tersebut, React Query dapat menjadi pilihan yang tepat untuk mengelola data pada aplikasi React, terutama untuk aplikasi yang kompleks dan memerlukan performa yang cepat.

https://tanstack.com/query/latest/ untuk melihat dokumentasi lengkapnya. Untuk mempelajari lebih lanjut tentang React Query,

## Layouting

Dasarnya, layouting yang dilakukan oleh frontend adalah slicing design yang dibuat oleh tim UI/UX. Layouting yang dilakukan frontend harus responsive dan mirip dengan design dari UI/UX.

Langkah-langkah yang harus diperhatikan saat ingin mengerjakan task layouting adalah:

1.  Memikirkan bagaimana cara kita mengimplementasikan design tersebut. Contohnya ketika kita melihat design di bawah ini,
    ![contoh](contoh1.jpg)
    kita harus memikirkan apakah kita menggunakan flex atau grid? dan bagaimana susunan markupnya.
2.  Mengaplikasikan analisa design kita ke dalam codingan.

Dengan melakukan langkah-langkah tersebut, kita akan menjadi semakin mudah untuk layouting dan membuat hasil coding kita menjadi lebih rapih dan juga terstruktur.

## Design System

Di workspace frontend, sudah disediakan beberapa komponen yang membuat pengerjaan kita menjadi lebih cepat dan konsisten. Salah satu dari komponen tersebut adalah komponen Typography. Pada komponen Typography, kita bisa memilih variant, font, dan weight yang akan digunakan.

Design system ini bertujuan untuk membuat hasil yang lebih konsisten, karena memiliki dasar komponen yang sama.

## Clean Code

Clean code adalah salah satu aspek penting dalam pengembangan sebuah software/web. Untuk mendapatkan hasil yang maksimal, dan mempermudah orang lain membaca hasil coding kita, sebaiknya clean code ini diterapkan.

Aturan umum clean code yaitu:

1.  Mengikuti standart umum bahasa pemograman
2.  KISS (Keep It Simple Stupid), diusahakan untuk selalu meminimal mungkin dalam mengimplementasikan kode.
3.  Cari akar permasalahan, jangan hanya bagian-bagian sekitar yang terkena dampak kode tersebut.

Tips for writing cleaner code:

1.  Effectiveness, Efficiency and Simplicity
2.  Format and Syntax: Indentation and spacing, Consistent syntax
3.  Reusability
4.  Only Expose and Consume Data You Need

## Git & Github

### Git

Git adalah version control system yang bertugas untuk mencatat setiap perubahan pada file. Git memiliki fungsi untuk mengelola versi source code. Git sangat penting digunakan pada sebuah projek yang dikerjakan oleh banyak orang karena git dapat membuat salinan kode yang dapat dimodifikasi tanpa mengubah dan mengganggu versi utama dari kode tersebut. Karena itu, tim yang bekerja untuk mengembangkan sebuah fitur, atau memperbaiki dapat bekerja secara pisah dan menggabungkannya kembali kepada kode utama

Git commands dasar yang biasa digunakan contohnya adalah add, commit, pull, dan push.

### GitHub

GitHub adalah tempat yang digunakan untuk menyimpan dan mengelola kode suatu project. GitHub dan git saling berhubungan, karena git menyimpan data hanya di local komputer kita saja, sedangkan github bisa menyimpan kode kita yang dapat diakses oleh banyak orang.
