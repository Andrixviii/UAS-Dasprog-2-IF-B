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
 int e1,e2;
 cout << "Masukan Elemant ke-1= ";
 cin >> e1;
 cout << "Masukan Elemant ke-2= ";
 cin >> e2;
	
 cout << "\n";
 int arr[e1][e2], baris, kolom;
 
 cout << "baris: "; cin >> baris;
 cout << "kolom: "; cin >> kolom;
 
 cout << "\n";
 for(int i=0; i<baris; i++){
  for(int j=0; j<kolom; j++){
   cout << "["<<i<<j<<"]: ";
   	cin >> arr[i][j];
  }
 }
 
 cout << "\n";
 
 for(int i=0; i<baris; i++){
  for(int j=0; j<kolom; j++){
  	if(arr [i][j]%3==0 || arr [i][j]%5==0 || arr [i][j]%7==0){
  		cout << arr[i][j] << endl;
	  }
   }
 }
  return 0;
}
```
## Output

<img src="output1.2.png">

