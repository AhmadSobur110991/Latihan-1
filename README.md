#Tutorial Penggunaan GIT
- Buka direktory aktif lalu klik kanan dan pilih Git Bash Here
![1](https://user-images.githubusercontent.com/56815154/69341047-5d1f0680-0c9b-11ea-9ebb-277fd389b0b6.jpg)
- Buatkan direktory project, ketik: mkdir Latihan1

![2](https://user-images.githubusercontent.com/56815154/69341048-5db79d00-0c9b-11ea-86ef-e6fe2419227f.jpg)
- Masuk kedalam direktory yang baru dibuat, ketik: cd Latihan1
![3](https://user-images.githubusercontent.com/56815154/69341049-5db79d00-0c9b-11ea-8cbe-679deb5eaebf.jpg)
- Buatkan repository lokal, ketik: get init
![4](https://user-images.githubusercontent.com/56815154/69341050-5db79d00-0c9b-11ea-95c5-627fea0c82c7.jpg)
  nanti akan muncul directory hidden dengan nama .git
![5](https://user-images.githubusercontent.com/56815154/69341051-5e503380-0c9b-11ea-8d09-c5203114a532.jpg)
- Buatkan file README.md menggunakan notepad
![6](https://user-images.githubusercontent.com/56815154/69341052-5ee8ca00-0c9b-11ea-9530-cb06331837e4.jpg)
- Tambahkan file README.md,
  ketik: git add README.md
![7](https://user-images.githubusercontent.com/56815154/69341054-5f816080-0c9b-11ea-93ed-fa0b1d460b16.jpg)
- Simpan perubahan kedalam database repository local, 
  ketik: git commit -m "File Latihan 1"
![8](https://user-images.githubusercontent.com/56815154/69341056-6019f700-0c9b-11ea-833e-97d4271f1f24.jpg)
- Upload ke server GITHUB agar bisa diakses oleh banyak user
  ketik: git remote add origin https://github.com/AhmadSobur110991/Latihan-1.git
![9](https://user-images.githubusercontent.com/56815154/69341057-60b28d80-0c9b-11ea-9057-b8109631ca8a.jpg)
- Untuk mengirim perubahan pada local reporitory ke server 
  ketik: git push -u origin master
![10](https://user-images.githubusercontent.com/56815154/69341059-614b2400-0c9b-11ea-8d89-5cb8561b53c4.jpg)
