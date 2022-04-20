#include<iostream>
using namespace std;
	int main(){
		int c [10] , z  , i = 0;
		
		do {
			cout << "Enter Number (-1 to end input ) " << endl;
			cin >> z;
			
			if ( z != -1 ){
				c [ i ] = z;
			}
			i++;
		}
		while ( z != -1 && i < 100 );
		cout << "The Total Number of positive integers by user is " << i -1;
		
	}
