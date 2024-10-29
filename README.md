//Page 84 question 8. Total Purchase
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












