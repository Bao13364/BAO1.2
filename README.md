//Page 84 question 8
#include<iostream>
using namespace std;
int main(){

double a=15.95,b=24.95,c=6.95,d=12.95,e=3.95;
double Subtotal;
double SalesTax;
double sub;
Subtotal=a+b+c+d+e;
SalesTax=0.07*Subtotal;
sub=Subtotal-SalesTax;
cout<<"price of item 1=$"<<a<<endl;
cout<<"price of item 2=$"<<b<<endl;
cout<<"price of item 3=$"<<c<<endl;
cout<<"price of item 4=$"<<d<<endl;
cout<<"price of item 5=$"<<e<<endl;
cout<<"subtotal= "<<Subtotal<<endl;
cout<<"SalesTax= "<<SalesTax<<endl;
cout<<"sub= "<<sub<<endl;

return 0;
}

//page 84 question 9
#include <iostream>
using namespace std;
int main() {
    cout << "char 所占字节为（the byte of char are）" << sizeof(char) << endl;
    cout << "int 所占字节为（the byte of int are）" << sizeof(int) << endl;
    cout << "float所占字节为（the byte of float are）" << sizeof(float) << endl;
    cout << "double 所占字节为（the byte of double are）" << sizeof(double) << endl;

    return 0;
}


P84 question 10

#include <iostream>
using namespace std;

double MPG(double MilesDriven, double GallonUsed) {
    double num = MilesDriven / GallonUsed;
    return num;
}

int main() {
    double a = 0, b = 0;

    cout << "Enter the miles driven: ";
    cin >> a;
    cout << "Enter the gallons of gas used: ";
    cin >> b;

    double mpg = MPG(a, b);

    cout << "Your MPG is " << mpg << endl;

    system("pause");
    return 0;
}
 question 12
#include<iostream>
using namespace std;
int main() {
	double acre, squareFeet,N;
	N = 1.0/43560;
	cout << "enter square feet";
	cin >> squareFeet;
	cout << endl;
	cout << squareFeet << " is equal to " << N * squareFeet << " acre" << endl;

}

question 13

#include<iostream>
using namespace std;
float SellingPrize()
{
	float cost;
	cout << "enter your cost: " ;
	cin >> cost;
	float prize;
	prize = cost/0.65;
	cout << "prize is " << prize;
	return prize;
}
int main(){
	float cost, prize;
	prize = SellingPrize();
	return 0;
}
question 15
#include<iostream>
using namespace std;
int main() {
	int n=5,i,j;
	cout << "enter the rows: \n";
	for (i = 1; i < n;i++) {
		for (j = 0; j < 4 - i;j++) {
			cout << " ";
		}
		for (j = 0; j < 2 * i -1;j++) {
			cout << "*";
		}
		cout << endl;
	}
}

question 16
#include<iostream>
using namespace std;
int main()
{
	int n = 4, i, j;

	for (i = 1; i <= n; i++) {
		for (j = 0; j < 4 - i; j++) {
			cout << " ";
		}
		for (j = 0; j < 2 * i - 1; j++) {
			cout << "*";
		}
		cout << endl;
	}


	for (int a = 1; a <= 3; a++)
	{
		for (int j = 0; j < a; j++)
		{
			cout << " ";
		}
		for (int j = 0; j < ( - 2 * a) +7; j++)
		{
			cout << "*";
		}
		cout << endl;
	}
}

