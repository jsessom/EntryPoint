# EntryPoint
Manipulating an integer array
// ConsoleApplication1.cpp : Defines the entry point for the console application.
//

#include "stdafx.h"


#include <iostream>
using namespace std;
int main() 
{
	/*int x = 0;
	while (x < 10)
	{
		cout << x << "\n";
		x = x + 1;
	}
	*/
	int array[5] = { 10,23,27,76,32 };

	cout << array[0] << endl;

	int arr[4];
	
	for (int i = 0; i < 4; i++)
	{

		arr[i] = 99;
		cout << arr[i] << endl;
	}




	return 0;
	
}
