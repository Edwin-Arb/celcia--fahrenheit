#include<stdio.h>
#include<iostream>
using namespace std;

int main(int nNumveroArgs, char* pszArgs[])
{
	setlocale(LC_ALL, "ru");
	int nNCelsius;
	cout << "Введите температуру по Цельсию: " << endl;
	cin >> nNCelsius;

	int nNFactor;
	nNFactor = 212 - 32;

	int nFahrenheit;
	nFahrenheit = nNFactor * nNCelsius / 100 + 32;

	cout << "Температура по Фаренгейту: " << endl;
	cout << nFahrenheit;
	return 0;
}
