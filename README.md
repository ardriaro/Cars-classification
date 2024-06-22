# Tugas Pengenalan Pola - Klasifikasi Mobil
## Deskripsi Project
   - Dataset yang digunakan adalah dataset pengenalan mobil yang diambil dari platform Kaggle. Dataset tersebut berisikan lebih dari 8000 gambar yang mencakup 196 jenis mobil yang berbeda. Dataset disimpan di Google Drive, berikut link drive dataset klasifikasi mobil : https://drive.google.com/drive/folders/1qWa2Pth80jyy9oBJwyZ8099dFGp_cVuT?usp=sharing
![Dataset Mobil](https://github.com/ardriaro/image/blob/3c0933f7c771dcf100f55130c916c8a42a60fc6f/dataset.png)

   - Pre-processing dataset tersebut menggunakan beberapa modul yang diperlukan yaitu **numpy** untuk operasi numerik, **cv2** untuk manipulasi gambar, dan **torch** untuk operasi tensor dengan tipe **float32**.

   - Pre-processing yang dilakukan berupa :
     - Mengubah ukuran gambar dan konversi ke skala abu-abu.
     - Normalisasi gambar.
     - Pembuatan tensor untuk digunakan dalam pelatihan model dengan PyTorch
     - Berikut hasil pre-processing dataset :
![Pre-processing](https://github.com/ardriaro/image/blob/5d8d270e3d6476cfa0fa65ae8ca10d729f3349f6/image.png)

   - Training model menggunakan GPU sebagai runtime program tersebut karena GPU dapat memproses data secara paralel untuk mempercepat komputasi.
     
   - Training model menggunakan dataset yang telah dilakukan pre-processing, training tersebut dilakukan dalam batch sebesar 32 sampel dan akan berlangsung selama 30 epoch. Adapun argumen **verbose=true** menunjukkan informasi training (seperti loss dan akurasi) akan ditampilkan selama proses training.
   - Berikut hasil training model yang dilakukan :
     ![Dataset Mobil](https://github.com/ardriaro/image/blob/712cfe08fdfd5631eca00064dbbe77d9d7c56875/image.png)

   - Evaluasi model dilakukan dengan menguji model tersebut, disini kami menggunakan dataset pre-processing untuk melakukan prediksi dari beberapa gambar.
   - Berikut hasil predict klasifikasi:
     ![Dataset Mobil](https://github.com/ardriaro/image/blob/7255b8d5887bb04627f6ae09f3c1e58ecbd08ee8/image.png)

     
## Anggota Kelompok
1. Handiyudha Dwiky Dharmawan (21102234)
2. Fandy Ardiansyah (21102244)

## Kontribusi Anggota
1. Handiyudha Dwiky Dharmawan (21102234)
   - Mencari dataset
   - Membuat model classifikasi
2. Fandy Ardiansyah (21102244)
   - Pre-processing dataset
   - melakukan push git hub
