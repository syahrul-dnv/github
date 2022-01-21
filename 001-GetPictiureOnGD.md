

# Mengambil Gambar dari Google Drive
<li>langkah 1 kita siapkan dulu file gambar di sebuah google drive masing</li>
<li>langkah 2 kita klik kanan lalu pilih `Dapatkan Link` </li>
<li>langkah 3 kita ubah pengaturan izinnya ke `Siapa saja yang memili Link`</li>
<li>langkah 4 lalu kita salin link tersebut</li>
<pre> https://drive.google.com/file/d/1mBr5BYyDOCXVXyHOw6aLuT_V3mJKKAB2/view?usp=sharing</pre>
Diatas adalah link default gambarnya, kita perlu mengambil id nya saja: <pre>1mBr5BYyDOCXVXyHOw6aLuT_V3mJKKAB2</pre>

Dan kita perlu tag html yaitu img untuk membungkus id tersebut.
contoh
<br>
 ```<img src="https://drive.google.com/uc?export=view&id= (masukan id tersebut) "/>```

jadinya seperti ini<br>
```<img src="https://drive.google.com/uc?export=view&id=1mBr5BYyDOCXVXyHOw6aLuT_V3mJKKAB2">```
<div align="center">
 <img src="https://drive.google.com/uc?export=view&id=1fcdVJ9reiad8POwTexvWVoYs9E0JXg6l">
</div>
