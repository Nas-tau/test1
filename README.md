#include <iostream>
using namespace std;
int main()
{
    int x = 5;
    int y = 10;
    
    int *myPointer;
    
    myPointer = new int;
    *myPointer = 20;

    int *secondPointer = &y;
    
    *secondPointer = *myPointer + x;

    cout << "x = "<< x << endl;
    cout << "y = " << y << endl;
    cout << "myPointer = " << *myPointer << endl;
    cout << "myPointer's address is " << myPointer << endl;
    cout << "secondPointer = " << *secondPointer << endl; 
    
    return 0;
}
//------------------------------------------------------------------------------
// HW1: Triangels 
// HW2: Polygon
// HW3: *Linked List* --> Программада 3 функция болушу кк: бардык маанилерди экранга чыгаруу, жаны элементти кошуу, озгоргон маанилерин экранга чыгаруу 
