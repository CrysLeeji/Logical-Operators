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
    
    
    return 0;
}
