# Responsive  Web Design  
Responsive Web Design (RWD) adalah bertujuan membuat desain website kita dapat diakses dalam deice apapun.  

</br>

#### Viewport  
Viewport adalah area web yg dpt diakses oleh user.   
view port bisa disetting dengan sebuah meta yang ada di html.  

<img src="re1.jpeg" width="200" height="100">   

Teknik selanjutnya adalah buat gbr jd responsive  

<img src="re2.jpeg" width="200" height="100">  

>setting max width : ukuran mu 100% dr ukuran layar  

ketika layar dikecilin, gbr menyesuaikan dgn ukuran gambar  

<img src="re3.jpeg" width="200" height="100">  

>syntax yg lain  

<img src="re4.jpeg" width="200" height="100">   

>contoh, rem lebih besar  

<img src="re5.jpeg" width="200" height="100">   

>Berbeda  

<img src="re6.jpeg" width="200" height="100">   

>Padahal sma aukurannya 2  

Kenapa beda karena rem bergantung pada font size root nya  
default html font size adalah 16px  
klau set 2 rem berarti dikali 2, 16 x 2 makanya 32 px  
kalau em font size yg terdekat  

<img src="re7.jpeg" width="200" height="100">   

>em ada di container, container 20px, parent nya adalah 20 px, maka 2 x 20 makanya 40 px  

kebanyakan ukuran root font size adalah 16 px  
maka ketika mengaktifkan rem maka akan nyaru ukuran font size dr root nya, semisal rootnya adalah html  
kalau em, mencari ukuran font size tp yg terdekat, semisal dr parent nya  

<img src="re8.jpeg" width="200" height="100">   

>ukuran yang lainnya  

kalau vh langsung nembak ukuran layar  
vw akan mengikuti dr ukuran view port nya  
rem dan em kadang dipake untuk padding dan margin  
% cuman mnegikuti div
vw nembah ukuran view port nya  
vh tinggi layar  
vw lebar layar  
max width buat gambar  

</br>

Jenis-jenis responsive
<img src="re9.jpeg" width="200" height="100">   

**Media Querry**  
DIgunakan untuk membuat beberapa styles tergantung pada jenis device  

Contoh :  

<img src="re10.jpeg" width="200" height="100">  

>kalau layar di bawah 500 px maka yg dipake set di bawah  

<img src="re11.jpeg" width="200" height="100">   

>ketika di bawah 500 warnya berubah  

<img src="re12.jpeg" width="200" height="100">    

>padahal awalnya pink  

</br>

**Bootstrap**  
Dapat membuat web lbh cepat, responsive  
Selain itu ada material UI  
Yang berhubungan dengan style, dia berhubungan dengan layout  

<img src="re13.jpeg" width="200" height="100">  

>breakpoint boostrap  

Containers : layout basic boos mmebutuhkan kalau ingin menggunakan sistem grid  

<img src="re14.jpeg" width="200" height="100">  

>akan menyesuiakan ukurannya  

Menggunakan container untuk mengaur lay dan posisi dr konten  
Dibuat menggunakan flex box