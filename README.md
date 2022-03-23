# Lab2Web
Praktikum 2
1. Membuat Dokumen HTML
![image](https://user-images.githubusercontent.com/101643559/159711222-ad634724-1f80-4ebf-8a07-8b5ceefb1b6a.png)
Hasil pada Browser
![image](https://user-images.githubusercontent.com/101643559/159709308-1d6fc266-0494-4c7e-9a06-fcb8591b88c6.png)
2. Mendeklarasikan CSS Internal
![image](https://user-images.githubusercontent.com/101643559/159710605-f60ff98b-7bf2-4efa-a683-38178556d91e.png)
Tampilan pada Browser
![image](https://user-images.githubusercontent.com/101643559/159711776-48e2d848-552c-416d-b36a-4938ecd78b36.png)
3. Menambahkan Inline CSS 
![image](https://user-images.githubusercontent.com/101643559/159712274-5b989cd8-37a0-404b-9670-58207b158a5a.png)
Hasil pada browser
![image](https://user-images.githubusercontent.com/101643559/159712522-c6b1e938-d41d-4e2e-910e-408f1d44f5ba.png)
4. Membuat CSS Eksternal
![image](https://user-images.githubusercontent.com/101643559/159713441-a10d1959-3144-4095-abe5-846890355472.png)
menyisipkan link css pada head
![image](https://user-images.githubusercontent.com/101643559/159713560-10a152c0-701c-4593-9637-4fad43b6bdec.png)
Tampilan pada browser
![image](https://user-images.githubusercontent.com/101643559/159713691-5f86e4ae-629f-4616-a98e-473594741a45.png)
5. Penambahan CSS Selector
![image](https://user-images.githubusercontent.com/101643559/159715882-7c7a7468-2799-4744-a4dd-c4cce24b7541.png)
Tampilan pada browser 
![image](https://user-images.githubusercontent.com/101643559/159715994-2138e657-bad8-4574-a53f-4e64187f2265.png)


Jawaban Pertanyan Praktikum 2
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
eksperimen dengan cara mengubah beberapa properti dan nilai KODE CSS :
![image](https://user-images.githubusercontent.com/101643559/159720236-8f9d3395-c69b-47a0-8450-56860b6a49ea.png)

![image](https://user-images.githubusercontent.com/101643559/159720164-1a36ae82-fa3a-4bf6-8e07-9bd04e8271ee.png)
2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!
Perbedaannya adalah jika hanya menggunakan h1 maka semua yang ada dalam dokumen akan berubah, namun jika menggunakan #intro h1 yang berubah hanya yang memiliki tag intro tersebut.
3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!
jika ketiga CSS merubah elemen yang sama maka deklarasi tersebut akan mengikuti aturan prioritas dimana prioritas CSS nya seperti berikut :
- inline CSS
- ID selector CSS
- internal CSS
- external CSS
contoh: ini adalah tampilan coding pada html testing dimana terdapat 2 kalimat yang memiliki elemen yang sama yaitu h1:
- terdapat 2 CSS yang merubah warna tect h1
- ![image](https://user-images.githubusercontent.com/101643559/159723777-16f03c93-1284-46e0-9a16-e0d04ad3248c.png)
- Exsternal CSS berupa 
- ![image](https://user-images.githubusercontent.com/101643559/159724812-7bceec44-ec4f-40d0-889d-1f4887cb14e8.png)
tampilan pada browser 
![image](https://user-images.githubusercontent.com/101643559/159724813-efba9bf5-e87b-47c1-acf8-aca241cca117.png)
4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! ( p id="paragraf-1" class="text-paragraf" )
intinya semakin spesifik css  maka akan semakin tinggi prioritas css tersebut.
contoh :
![image](https://user-images.githubusercontent.com/101643559/159727828-53dc347b-12d2-44e8-8c8b-bec9361972ac.png)

Disitu bisa dilihat terdapat 2 css yang merujuk ke elemen yang sama tapi 1 merujuk dengan id yang birisi font 100px dan warna aqua sedangkan yang satu lagi merujuk dengan class yang berisi font 10px dan warna beige:
![image](https://user-images.githubusercontent.com/101643559/159727923-5fcee6ab-46bf-4dc2-bc65-3c08af625317.png)
tampilan pada browser 
![image](https://user-images.githubusercontent.com/101643559/159728291-4b5c8820-eeaf-4386-958c-2933e3569eca.png)
Text 3 Anisa Indriani tersebut mengikuti css selector id daripada selector class dikarenakan id lebih spesifik daripada class.

