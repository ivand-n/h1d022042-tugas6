# Tugas 6 Pertemuan 8
Ivan Darmawan<br>
H1D022042<br>
Shift I ke B<br>

## Penjelasan Program
Proses input data pada aplikasi ini diorganisir menggunakan tiga TextEditingController terpisah, yaitu _namaController, _nimController, dan _tahunController, yang masing-masing dipasang pada widget TextFormField yang relevan (seperti yang ditunjukkan pada contoh input Tahun Lahir). Ketika pengguna menekan tombol "Simpan" (ElevatedButton), nilai teks dari ketiga controller tersebut (nama, nim, dan tahun) diambil dan disimpan sebagai variabel String. Data ini kemudian dikirim (passed) ke halaman tujuan (MhsDetail) menggunakan Navigator.of(context).push dan MaterialPageRoute. Halaman tujuan, MhsDetail, dirancang untuk menangkap data tersebut melalui tiga parameter wajib (nama, nim, dan tanggal) yang didefinisikan dalam constructor-nya. Akhirnya, di dalam widget MhsDetail, data tersebut ditampilkan kepada pengguna dalam sebuah Text yang telah diformat, merangkum informasi dengan kalimat: "Nama saya [nama] dengan NIM [nim]. saya lahir di tahun [tanggal]"

![WhatsApp Image 2025-11-09 at 23 37 40_0d32b51a](https://github.com/user-attachments/assets/b5d5ff16-0d73-4553-885a-96031cd310f0)
![WhatsApp Image 2025-11-09 at 23 37 40_40e05131](https://github.com/user-attachments/assets/1bfe210c-71b0-4a35-a0f2-260cb02fa149)



