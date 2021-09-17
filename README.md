#include <iostream>
#include <conio.h>


using namespace std;
  
int main(){
	int FirstNum;
	int SecondNum;
	char CalSymbol;
  	cout << "Hello Alien! Please Enter Numbers to calculate: ";  
  	cin >> FirstNum;
	cin >> SecondNum;
	
	int check = 0;
	while(check != 1){
		cout << "\nPlease enter the Calculation Symbol that you want(+,-,*,/): ";  
		cin >> CalSymbol;
		if(CalSymbol == '+'){
			cout << FirstNum+SecondNum;
			check = 1;
		}else if(CalSymbol == '-'){
			cout << FirstNum-SecondNum;
			check = 1;
		}else if(CalSymbol == '*'){
			cout << FirstNum*SecondNum;
			check = 1;
		}else if(CalSymbol == '/'){
			cout << FirstNum/SecondNum;
			check = 1;
		}else{
			check = 0;
		}
	}
  	getch();
}
  

  
