# Ujian Akhir Semester 
<br>Mata Kuliah&ensp;&ensp; : Dasar Pemrograman
<br>Nama&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&nbsp;: MUHAMAD NOPID ANDRIANSYAH
<br>NIM&emsp;&emsp;&emsp;&emsp;&nbsp; : 1227050091
<br>Jurusan&emsp;&emsp;&emsp;: [Teknik Informatika](http://if.uinsgd.ac.id/) [UIN Sunan Gunung Djati Bandung](https://uinsgd.ac.id/)d.ac.id/) [UIN Sunan Gunung Djati Bandung](https://uinsgd.ac.id/) 

## Deskripsi Umum
``
Untuk mencetak angka yang habis dibagi 3, 5, dan 7 di C++, Anda dapat menggunakan perulangan for dengan beberapa perubahan pada kondisi perulangan. Berikut ini adalah contoh kode yang dapat Anda gunakan:

Di BAWAH adalah contoh kode yang mencetak angka yang habis dibagi 3, 5, dan 7 dari 1 hingga 100. Pertama, kita menggunakan perulangan for untuk mengelilingi angka dari 1 hingga 100. Kemudian, kita menggunakan operator modulus (%) untuk memeriksa apakah angka tersebut habis dibagi 3, 5, dan 7. Jika iya, maka kita mencetak angka tersebut dengan menggunakan cout.

Anda dapat menyesuaikan kode di atas sesuai dengan kebutuhan Anda, misalnya dengan mengubah jangkauan angka yang akan dicetak atau menambahkan beberapa kondisi lainnya. Semoga membantu!
``
## Source Code
```
#include <iostream>
using namespace std;

int main()
{
	int awal,akhir;
	cout << "Masukan Angka Awal= ";;
	cin >> awal;
	cout << "Masukan Angka Akhir= ";
	cin >> akhir; 
	
    for (int i = awal; i <=akhir; i++) {
        if (i % 3 == 0 || i % 5 == 0 || i % 7 == 0) {
            cout << i << endl;
        }
    }
    return 0;
}
```
## Output

<img src="output1.2.png">

