# Ujian Akhir Semester 
<br>Mata Kuliah 	: DASAR PEMROGRMAN
<br>Nama :MUHAMAD NOPID ANDRIANSYAH
<br>NIM		:	1227050091
<br>Jurusan		:[Teknik Informatika](http://if.uinsgd.ac.id/) [UIN Sunan Gunung Djati Bandung](https://uinsgd.ac.id/) 

## Deskripsi Umum

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

