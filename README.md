# Menghitung Bilangan terbesar dari n yang di inputkan user dan mencari  <br>
# bilangan terbesarnya      <br>
<br>
terbesar = 0<br>
<br>
while True:         <br>
    angka = int(input("Masukan Bilangan : "))   <br>
    if terbesar<angka:          <br>
        terbesar=angka          <br>
    if angka==0:            <br>
        break           <br>
print("Bilangan terbear adalah : ", terbesar)       <br>
        


 Penjelasan:        <br>
 1. Membuat sebuah variabel yg bernama <bold>terbesar = 0 </bold>       <br>
    variabel ini kita gunakan untuk mencari bilangan terbesarnya.       <br>
 2. Lalu kita gunakan perulangan <bold> while True: </bold> 
 3. Kemudian kita buat sebuah input dari user dimana bilangan tersebut bertipe integer      <br>
 4.Lalu membuat kondisi <bold> if terbesar < angka  </bold> <br>
   <bold>terbesar=angka </bold> maksudnya jika variabel dari terbesar lebih     <br>
   kecil dari input user maka variabel terbesar itu berubah nilainya menjadi nilai dari     <br>
    variabel angka tersebut.                                                            <br>
 5.<bold> if angka==0:  <br>        
            break                                           <br>
    Maksud dari sintaks ini adalah jika user memasukan angka 0 maka program akan berhenti lalu mengeluarkan angka       <br>
    terbesarnya dengan sintaks <br>
    print("Bilangan terbesar adalah :", terbesar)   <br>
<br>
<br>
Hasilnya seperti berikut: <br>
![img](input.png)

