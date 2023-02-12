# Homework_mapreduce

Cara menjalankan Mapreduce
a) Siapkan data yang akan diproses dan letakkan pada folder yang sama dengan code
    sebagai contoh gunakan file 'benda.txt'
b) Gunakan '$ cat benda.txt' untuk melihat data pada terminal
c) Untuk menjalankan proses Map, gunakan '$ cat benda.txt | mapper.py'
![image](https://user-images.githubusercontent.com/122470555/218298122-7cc2d1b5-abb2-4ed5-8c73-bd0d11e699ab.png)

     Pada proses Map akan terlihat data,value. Untuk merapikan dan mengurutkan data dapat ditambah command 'sort'
d) Untuk menjalankan proses MapReduce
  Gunakan command ini 'cat country.txt | python mapper.py | sort | python reducer.py'
  ![image](https://user-images.githubusercontent.com/122470555/218298272-f5d59596-9bb5-41f9-88d9-85c90bf7f978.png)
   
   Pada proses Reduce, data harus dilakukan Map terlebih dahulu dan data yang sudah diproses Map
   akan diproses Reduce menjadi seperti digambar.
