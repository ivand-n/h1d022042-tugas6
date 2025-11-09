# Tugas 6 Pertemuan 8
Ivan Darmawan<br>
H1D022042<br>
Shift I => B<br>

## Penjelasan Program
Proses input data pada aplikasi ini diorganisir menggunakan tiga TextEditingController terpisah, yaitu _namaController, _nimController, dan _tahunController, yang masing-masing dipasang pada widget TextFormField yang relevan (seperti yang ditunjukkan pada contoh input Tahun Lahir). Ketika pengguna menekan tombol "Simpan" (ElevatedButton), nilai teks dari ketiga controller tersebut (nama, nim, dan tahun) diambil dan disimpan sebagai variabel String. Data ini kemudian dikirim (passed) ke halaman tujuan (MhsDetail) menggunakan Navigator.of(context).push dan MaterialPageRoute. Halaman tujuan, MhsDetail, dirancang untuk menangkap data tersebut melalui tiga parameter wajib (nama, nim, dan tanggal) yang didefinisikan dalam constructor-nya. Akhirnya, di dalam widget MhsDetail, data tersebut ditampilkan kepada pengguna dalam sebuah Text yang telah diformat, merangkum informasi dengan kalimat: "Nama saya [nama] dengan NIM [nim]. saya lahir di tahun [tanggal]"

<img width="309" height="678" alt="image" src="https://github.com/user-attachments/assets/065dca9d-1c60-461f-bb66-c6a8080e1998" />
<img width="312" height="675" alt="image" src="https://github.com/user-attachments/assets/ae57093b-5e15-499b-93d1-112570c50890" />


