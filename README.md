# Switch-statement #
```C++
#include <iostream>
using namespace std;
string dayoftheweek(int daynumber)
{
    string dayname;
    switch(daynumber)
    {
        case 0 : dayname= "Sunday";
        break;

        case 1 : dayname= "Monday";
        break;

        case 2 : dayname= "Tuesday";
        break;

        case 3 : dayname= "Wednesday";
        break;

        case 4 : dayname= "Thursday";
        break;

        case 5 : dayname= "Friday";
        break;

        case 6 : dayname= "Saturday";
        break;

        default:
            dayname= "Invalid Day Number";
    }

    return dayname;
}

int main()
{
    cout<<"Enter day number : ";
    int m;
    cin>>m;
    cout << dayoftheweek(m);
    return 0;
}
```
