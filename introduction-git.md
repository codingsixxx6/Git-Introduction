Git for development colaboration :

1. Project harus di intialize dengan command "git init"

2. Ketika coder sudah melakukan "git init" maka coder akan otomatis masuk kedalam branch main/master. branch main/master bisa dibilang virtual working directory yang merupakan branch utama untuk nge-develop project.

3. Proses "git init" tadi akan membuat semua file code yang ada didalam working di rectory atau root project berubah statusnya menjadi untracked dengan simbol "U" pada filenya. dan coder harus menjalankan command "git add ." untuk merubah smeua status untracked pada file code tadi menjadi added dengan simbol "A" pada file nya. 

4. Setelah command git add . dijalankan, seterusnya coder bisa menjalankan command untuk commit "git commit -m 'coder message'". dan ketika commit sudah dijalankan, secara otomatis semua file yang statusnya added akan hilang ( file sudah berhasil ter-commit). dan ketika coder melakukan perubahan pada file yang sudah di commit, maka statusnya akan berubah menjadi modify "M" yang artinya file yang sudah di commit tadi di modifikasi oleh coder dan perlu di add ulang dan commit ulang. secara best practicenya, commit di lakukan ketika suatu fitur telah selesai di kerjakan.

5. Untuk tahap selanjutnya, coder bisa membuat repository di github sebagai tempat untuk menyimpan project secara online. ini memungkinkan para developer untuk bekerja sama dalam proses development sebuah software. 

6. Ketika coder/developer sudah berhasil membuat repository project, seterusnya mereka bisa menghubungkan file project mereka dengan repository yang dibuat tadi dengan command di terminal "git remote add origin 'specific link repository'".

7. Coder harus menjalankan command untuk upload file dari local ke repository yang sudah kehubung tadi dengan code "git push -u origin 'specific nama branch'"

8. Ini yang paling penting, dan banyak developer yang blunder karena kurang fokus. ketika coder/developers sedang dalam proses development dan nge-handle task masing-masing, untuk mengerjakan task itu, coder/developers ga boleh mengerjakannya didalam branch main/master secara langsung. karena branch main/master itu merupakan branch utama yang ga boleh di otak-atik dan digunakan ketika code sudah tidak ada lagi yang harus di perbaiki dan sudah siap masuk kedalam tahap production. dan solusinya, coder/developers harus membuat barnch terlebih dahulu dengan command "git chekout -b 'nama branch yang kita inginkan'".