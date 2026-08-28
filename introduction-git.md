Git for development :

1. Project harus di intialize dengan command "git init"

2. Ketika kita sudah melakukan "git init" maka kita akan otomatis masuk kedalam branch main/master.
branch main/master bisa dibilang virtual working directory yang merupakan branch utama untuk nge-develop project.

3. Proses git init tadi akan membuat semua file yang ada didalam working di rectory atau root      project berubah statusnya menjadi untracked dengan simbol "U" pada filenya. dan coder harus menjalankan command git add . untuk merubah status untracked tadi menjadi added dengan simbol "A" pada file nya. 

4. Setelah command git add . dijalankan, seterusnya coder bisa menjalankan command untuk commit "git commit -m 'coder message'"