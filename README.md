#Tutorial Penggunaan GIT
- Buka direktory aktif lalu klik kanan dan pilih Git Bash Here
- Buatkan direktory project, ketik: mkdir Latihan1
- Masuk kedalam direktory yang baru dibuat, ketik: cd Latihan1
- Buatkan repository lokal, ketik: get init
  nanti akan muncul directory hidden dengan nama .git
- Buatkan file README.md menggunakan notepad
- Tambahkan file README.md,
  ketik: git add README.md
- Simpan perubahan kedalam database repository local, 
  ketik: git commit -m "File Latihan 1"
- Upload ke server GITHUB agar bisa diakses oleh banyak user
  ketik: git remote add origin https://github.com/AhmadSobur110991/Latihan-1.git
- Untuk mengirim perubahan pada local reporitory ke server 
  ketik: git push -u origin master
