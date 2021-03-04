#include <iostream>
using namespace std;

int main(){
	int angka;

	cout << "Menentukan angka yang diinput Positif, Negatif, atau 0" << endl;
	cout << "------------------------------------------------------" << endl;
	cout << "Masukkan angka = ";
	cin >> angka;

	cout << endl;

	if(angka > 0)
	{
		cout << "Angka yang ada masukkan adalah POSITIF" << endl;
	} 
	else if(angka < 0)
	{
		cout << "Angka yang ada masukkan adalah NEGATIF" << endl;
	}
	else if(angka = 0)
	{
		cout << "Angka yang ada masukkan adalah 0" << endl;
	}
	else
	{
		cout << "Yang anda input bukan angka" << endl;
	}

	return 0;
	
	//revisi pertama
}
