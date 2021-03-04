#include <iostream>
using namespace std;

int main(){
	int n,i;
	int angka[10];

	cout << "Menentukan angka yang diinput Positif, Negatif, atau 0" << endl;
	cout << "------------------------------------------------------" << endl;
	cout << "Masukkan angka = ";
	cin >> n;

	cout << endl;

	for (i=0;i<n;i++)
	{
		cout<<"Masukan angka =";
		cin>>angka[i];
		cout<<"\n";
	}

	cout<<"\n Bilangan Positif: ";
	
	for(i=0;i<n;i++)
	{
		if(angka[i]>0)
		{
			cout<<angka[i]<<"      ";
		}
	}
		
	cout<<"\n Bilangan Negatif : ";

	for(i=0;i<n;i++)
	{
		if(angka[i]<0)
		{
			cout<<angka[i]<<"       ";
		}
	}
}
