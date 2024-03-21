Git dari repository yang sudah ada

1. buka terminal

2. pindah ke folder khusus untuk coding misal : c:/code/

3. clone project dari github : git clone https://github.com/amiruddinid/FSW-4.git

   git clone = command git untuk mengeclone / download project dari remote repository

4. buka folder tersebut dengan code editor,

   tips buka vscode dari terminal : masuk ke folder project, terus ketikan code.

5. - silahkan buat 1 folder dengan nama panggilan masing2
   - di dalamnya beri satu file bernama README.md
   - di dalam file tersebut beri pesan2 bebas
   - simpan

6. git status = untuk mengecheck status dari project git

7. git add = untuk memindahkan folder/file ke staging area / mentrack sebuah file untuk siap di commit

   git add nama_file

   git add .

8. git commit -m "commit message"

9. git push

   - kalau error karena di remote repository sudah lebih baru
   - lakukan synchronize dengan command git pull

10. git pull

    - untuk keluar dari text editor vim / di terminal klik di keyboard ctrl + c
      kemudian ketik :qa! untuk menyimpan dan keluar dari kode editor tersebut

11. kalau tidak ada error bisa lakukan git push lagi

PR :

Git Flow

Membuat repository dari awal
