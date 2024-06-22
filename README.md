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
![Pre-processing](https://github.com/ardriaro/image/blob/3c0933f7c771dcf100f55130c916c8a42a60fc6f/dataset.png)


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
