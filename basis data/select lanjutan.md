# AND
 select and ini akan menampilkan data dengan "nilai1" dan "nilai2".
 contoh:
 
 ```mysql
 select warna,pemilik from mobil where warna="hitam" and pemilik="ibrahim";
```

![[IMG_20240227_145125.jpg]]
## OR
select or ini akan menampilkan data dengan "nilai1" atau "nilai2".
contoh:

```mysql
select warna, pemilik from mobil where warna="hitam" or pemilik="Ibrahim";
```

![[IMG_20240227_145533.jpg]]

# BETWEEN- AND
select between-and ini akan menampilkan data antara "nilai1" dan "nilai2".karena didukung dengan AND.
CONTOH:

```mysql
select * FROM mobil WHERE harga_rental BETWEEN 100000 AND 200000;
```

![[IMG_20240227_150451.jpg]]
# NOT BETWEEN
## <=
untuk <= ini akan menampilkan "data" yang lebih kecil atau sama dengan "nilai_data yang telah ditentukan.
CONTOH:

```mysql
SELECT * FROM mobil WHERE harga_rental <= 50000;
```

![[IMG_20240227_151052.jpg]]
# >=
untuk >= ini akan menampilkan "data" yang lebih besar atau sama dengan "nilai_data yang telah ditentukan.
CONTOH:

```mysql
SELECT * FROM mobil WHERE harga_rental >= 50000;
```

![[IMG_20240227_151323.jpg]]
# <> atau !=
untuk <>atau != ini akan menampilkan "data" yang tidak sama dengan "nilai_data yang telah ditentukan.
CONTOH:

```mysql
SELECT * FROM mobil WHERE harga_rental <> 50000;
```

![[IMG_20240227_151707.jpg]]