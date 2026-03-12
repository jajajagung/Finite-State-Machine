Tugas Finite State Machine (FSM) Unity 2D
Nama: Muhammad Afriza Jein
Kelas: GJ24A

Apa itu Finite State Machine (FSM)?

Bayangkan Lampu Lalu Lintas. Lampu itu punya 3 warna: Merah (Berhenti), Kuning (Siap), dan Hijau (Jalan). Lampu ini akan berganti warna sesuai aturan, dan tidak mungkin menyala Merah dan Hijau di saat yang bersamaan.

Nah, FSM adalah sistem seperti lampu lalu lintas tersebut, tapi digunakan untuk menjadi "otak" karakter (misalnya musuh) di dalam game.

Inti dari FSM sangat sederhana:

Fokus Satu Hal: Musuh cuma bisa melakukan satu kegiatan di satu waktu. Dia tidak bisa bengong sambil mengejar orang di saat bersamaan.

Punya Daftar Status (State): Musuh punya daftar kegiatan pasti. Di project ini ada 3 status yaitu Diam, Jalan-jalan (Patroli), dan Mengejar.

Ada Pemicu (Trigger): Musuh tidak ganti kegiatan sesuka hati, harus ada alasannya. Contoh: Kalau dia sedang jalan-jalan lalu melihat pemain, statusnya otomatis berubah jadi mengejar.

Bikin Karakter Tidak "Bodoh": Dengan aturan yang jelas, musuh tahu kapan harus lari mengejar, dan kapan harus menyerah (kembali diam) jika pemain berhasil kabur terlalu jauh.

Singkatnya, FSM adalah "Buku Panduan Aturan" bagi karakter game agar dia tahu kapan harus diam, kapan harus jalan, dan kapan harus marah!
