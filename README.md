# Lab5Web
Nama : Anggita Risqi Nur Clarita

NIM : 312210450

Kelas : TI.22.A.4

## DAFTAR ISI <br>
| No | Description | Link |
|-----|------|-----|
|1|Modul Praktikum 5|[Click Here](https://drive.google.com/file/d/1rKpneqfyb09TWo6HXqnnkIft0mKDj4sm/view)|
|2|Praktikum|[Click Here](#praktikum)|
|3|Pengenalan JavaScript|[Click Here](#pengenalan-javascript)|
|4|JavaScript Dasar|[Click Here](#javascript-dasar)|
|5|Dasar Pemrograman di JavaScript|[Click Here](#dasar-pemrograman-di-javascript)|
|6|Pembuatan Form|[Click Here](#pembuatan-form)|
|7|HTML DOM|[Click Here](#html-dom)|
|8|Pertanyaan dan Tugas|[Click Here](#pertanyaan-dan-tugas)|

## Praktikum
> ### Instruksi Praktikum
> 1. Persiapkan text editor misalnya **VSCode**.
>
> 2. Buat folder baru dengan nama **lab5_javascript**.
>
> 3. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.

## Pengenalan JavaScript
1. ### Membuat Contoh document.write dan cosole.log
    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <title>Mengenal JavaScript</title>
    </head>
    <body>
        <h1>Pengenalan JavaScript</h1>
        <h3>Contoh document.write dan console.log</h3>
        <script>
            document.write("Hello World");
            console.log("Hello World");
        </script>
    </body>
    </html>
    ```

    **Output**
    
    ![image](https://github.com/AnggitaRisqiNC/Lab5Web/blob/main/screenshot/1.png)
    **Keterangan** : Disini diperintahkan untuk membuat file dengan nama `lab5_javascript.html`, kemudian menambahkan script yang telah tersedia. Script HTML tersebut digunakan untuk membuat **Contoh document.write dan cosole.log** sebagai pengenalan awal JavaScript.


## JavaScript Dasar
1. ### Pemakaian Alert sebagai Property Window
    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>alert Box</title>
    </head>
    <body>
        <script language="javascript"> 

            window.alert('ini merupakan pesan untuk anda');
            
        </script>
    </body>
    </html>
    ```

    **Output**
    
    ![image](https://github.com/AnggitaRisqiNC/Lab5Web/blob/main/screenshot/2.png)
    **Keterangan** : Script HTML tersebut digunakan untuk mengetahui pemakaian Alert sebagai Property Window.


2. ### Pemakaian Method dalam Objek
    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Script javascript</title>
    </head>
    <body>
        percobaan pemakaian javascript:<br>
        <script languange="javascript">

            document.write('selamat mencoba javascript<br>');
            document.write('semoga sukses');
            
        </script>
    </body>
    </html>
    ```

    **Output**

    ![image](https://github.com/AnggitaRisqiNC/Lab5Web/blob/main/screenshot/3.png)
    **Keterangan** : Script HTML tersebut digunakan untuk mengetahui pemakaian Method dalam Objek.
   

3. ### Pemakaian Prompt
    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>pemasukan data</title>
    </head>
    <body>
        <script language="javascript">

            var nama = prompt("siapa nama anda?","masukan nama anda: ");
            document.write("hai, " + nama);

        </script>
    </body>
    </html>
    ```

    **Output**

    ![image](https://github.com/AnggitaRisqiNC/Lab5Web/blob/main/screenshot/4.png)

    ![image](https://github.com/AnggitaRisqiNC/Lab5Web/blob/main/screenshot/5.png)


4. ### Pembuatan fungsi dan cara pemanggilannya
    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Contoh program javascript</title>
        <script language="javascript">
            function pesan(){
                alert('memanggil javascript lewat body onload')
            }
        </script>
    </head>
    <body onload=pesan()>
    </body>
    </html>
    ```

    **Output**

    ![image](https://github.com/AnggitaRisqiNC/Lab5Web/blob/main/screenshot/6.png)
    **Keterangan** : Script HTML tersebut digunakan untuk membuat fungsi dan cara pemanggilannya.


## Dasar Pemrograman di JavaScript
1. ### Operasi dasar Aritmatika
    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>contoh program javascript</title>
        <script language="javascript">
            function test (val1, val2)
            {
                document.write("<br>"+"perkalian : val1 * val2"+"<br>")
                document.write(val1*val2)
                document.write("<br>"+"pembagian : val1 / val2"+"<br>")
                document.write(val1/val2)
                document.write("<br>"+"penjumlahan : val1 + val2"+"<br>")
                document.write(val1+val2)
                document.write("<br>"+"pengurangan : val1 - val2"+"<br>")
                document.write(val1-val2)
                document.write("<br>"+"modulus : val1 % val2"+"<br>")
                document.write(val1%val2)
            }
        </script>
    </head>
    <body>
        <input type="button" name="button1" value="arithmetic" onclick=test(9,4)>
    </body>
    </html>
    ```

    **Output**

    ![image](https://github.com/AnggitaRisqiNC/Lab5Web/blob/main/screenshot/7.png)
    
    ![image](https://github.com/AnggitaRisqiNC/Lab5Web/blob/main/screenshot/8.png)


2. ### Seleksi Kondidi (if-else)
    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>contoh if-else</title>
    </head>
    <body>
        <script language="javascript">
            var nilai = prompt('nilai 0 - 100: ',0);
            var hasil = " ";
            if (nilai >= 60)
            hasil = "Lulus";
            else
            hasil = "tidak lulus";
            document.write ('hasil: '+hasil);
        </script>
    </body>
    </html>
    ```

    **Output apabila Tidak Lulus**

    ![image](https://github.com/AnggitaRisqiNC/Lab5Web/blob/main/screenshot/9.png)

    ![image](https://github.com/AnggitaRisqiNC/Lab5Web/blob/main/screenshot/10.png)

    **Output apabila Lulus**

    ![image](https://github.com/AnggitaRisqiNC/Lab5Web/blob/main/screenshot/11.png)

    ![image](https://github.com/AnggitaRisqiNC/Lab5Web/blob/main/screenshot/12.png)


3. ### Penggunaan Operator Switch Untuk Seleksi Kondisi
    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>contoh program javascript</title>
        <script language="javascript">
            function test ()
            {
                val1=window.prompt ('input nilai (1-5):')
                switch (val1)
                {
                    case '1':
                        document.write('bilangan satu')
                        break
                    case '2' :
                        document.write('bilangan dua')
                        break
                    case '3':
                        document.write('bilangan tiga')
                        break
                    case '4' :
                        document.write('bilangan empat')
                        break
                    case '5':
                        document.write('bilangan lima')
                        break
                    default :
                        document.write('bilangan lainnya')
                }
            }
        </script>
    </head>
    <body>
        <input type="button" name="button1" value="switch" onclick=test()>
    </body>
    </html>
    ```

    **Output**

    ![image](https://github.com/AnggitaRisqiNC/Lab5Web/blob/main/screenshot/13.png)

    ![image](https://github.com/AnggitaRisqiNC/Lab5Web/blob/main/screenshot/14.png)

    ![image](https://github.com/AnggitaRisqiNC/Lab5Web/blob/main/screenshot/15.png)


## Pembuatan Form
1. ### Membuat Form Input
    ```html
        <!DOCTYPE html>
    <html lang="en">
    <head>
        <script language="javascript">
            function test () {
                var val1= document.kirim.t1.value;
                if (val1%2==0)
                    document.kirim.t1.value="bilangan genap"
                else
                    document.kirim.t2.value="bilangan ganjil"
            }
        </script>
    </head>
    <body>
        <form method="POST" name="kirim">
            <p>BIL <input type="text" name="t1" size="20"> MERUPAKAN BIL <input type="text" name="t2" size="20"></p>
            <p><input type="button" value="TEBAK" name="B1"onclick=test()></p>
        </form>
    </body>
    </html>
    ```

    **Output**

    ![image](https://github.com/AnggitaRisqiNC/Lab5Web/blob/main/screenshot/16.png)
    
    ![image](https://github.com/AnggitaRisqiNC/Lab5Web/blob/main/screenshot/17.png)


2. ### Membuat Form Button
    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <title>Objek document</title>
    </head>
    <body>
        <script language="javascript">
        function ubahWarnaLB(warna){
            document.bgColor= warna;
        }
        function ubahWarnaLD(warna){
            document.fgColor= warna;
        }
        </script>

        <h1>tes</h1>
        <form>
            <input type="button" value="latar Belakang Hijau" onclick="ubahWarnaLB('green')">
            <input type="button" value="latar Belakang Putih" onclick="ubahWarnaLB('white')">
            <input type="button" value="Teks Kuning" onclick="ubahWarnaLD('yellow')">
            <input type="button" value="Teks Biru" onclick="ubahWarnaLD('blue')">
        </form>
        <script language="javascript">
        
        document.write("Dimodifokasi terakhir pada " + document.lastModified);
        
        </script>
    </body>
    </html>
    ```

    **Output**

    ![image](https://github.com/AnggitaRisqiNC/Lab5Web/blob/main/screenshot/18.png)
    

## HTML DOM
1. ### Pilihan Menggunakan CheckBox Dengan Perhitungan Otomatis
    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <title>Daftar Menu</title>
        <script>
            function hitung(ele){
                var total = document.getElementById('total').value;
                    total = (total ? parseInt(total): 0);
                var harga = 0 ;

                if (ele.checked) {
                    harga = ele.value;
                    total += parseInt(harga);
                } else {
                    harga = ele.value;
                    if (total > 0 )
                        total -= parseInt(harga);
                }
                document.getElementById('total').value = total;
            }
        </script>
    </head>
    <body>
        <h1>Daftar menu Makanan</h1>
        <label><input type="checkbox" value="5000" id="menu1" onclick="hitung(this); "/> Ayam Goreng Rp. 5000</label><br />
        <label><input type="checkbox" value="500" id="menu2" onclick="hitung(this); "/> Tempe Goreng Rp. 500</label><br />
        <label><input type="checkbox" value="2500" id="menu3" onclick="hitung(this); "/> Telur Dadar Rp. 2.500</label><br />
        <strong> Total Bayar: Rp. <input id="total" type="text"/> </strong>
    </body>
    </html>    
    ```

    **Output**

    ![image](https://github.com/AnggitaRisqiNC/Lab5Web/blob/main/screenshot/19.png)


## Pertanyaan dan Tugas

1. **Buat script untuk melakukan validasi pada isian form**
    
    ![image](https://github.com/AnggitaRisqiNC/Lab5Web/blob/main/screenshot/20.png)
    **Keterangan** : Disini saya membuat script untuk melakukan validasi pada isian form seperti berikut dan tampilan websitenya seperti ini, untuk script-nya dapat dilihat langsung pada file [Lab5Web.html](https://github.com/AnggitaRisqiNC/Lab5Web/blob/main/lab5_javascript/Lab5Web.html)

## Finish