#include <iostream>

using namespace std;

int main()
{
    //Logical Operators
    
    //AND
    bool a = true && true;
    bool b = true && false;
    bool c = false && true;
    bool d = false && false;
    
    cout << "AND" << endl;
    
    cout << a << endl;
    cout << b << endl;
    cout << c << endl;
    cout << d << endl;
    
    //OR
    bool e = true || true;
    bool f = true || false;
    bool g = false || true;
    bool h = false || false;
    
    cout << "OR" << endl;
    
    cout << e << endl;
    cout << f << endl;
    cout << g << endl;
    cout << h << endl;
    
    //COMPARISON
    bool i = 30 > 39;
    bool j = 69 < 70;
    bool k = 50 >= 49;
    bool l = 70 <= 70;
    bool m = 50 == 50;
    bool n = 99 != 20;
    
    cout << "COMPARISON" << endl;
    
    cout << i << endl;
    cout << j << endl;
    cout << k << endl;
    cout << l << endl;
    cout << m << endl;
    cout << n << endl;
    
    //CONDITIONALS
    cout << "CONDITIONALS" << endl;
    
    int baon = 150;
    if (baon >=200){ //200 up
        cout << "Papasok" << endl;
    }
    else if (baon >= 100){
        cout << "Papasok pero magkacutting" << endl;
    } 
    else{
        cout << "Tambay" << endl;
    
    }
    int choice = 3;
    switch(choice){
        case 1:
            cout << "Hello" << endl;
            break;
        case 2:
            cout << "Love" << endl;
            break;
        case 3:
            cout << "Goodbye" << endl;
            break;
        case 4:
            cout << "Red Horse" << endl;
            break;
        default: cout << "Ngeks" << endl;
        
    }
    
    
    return 0;
}
