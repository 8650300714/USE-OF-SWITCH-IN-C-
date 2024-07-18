# USE-OF-SWITCH-IN-C-
#include<iostream>
using  namespace std;
int main()
{
    char button;
    cout<<"press the button a,b,c,d,e:-"<<endl
    ;
    cin>>button;
    switch(button)
    {
        case 'a':
        cout<<"Hello"<<endl;
        break;
        case 'b':
        cout<<"Assalamualikum"<<endl;
        break;
        case 'c':
        cout<<"Namastai"<<endl;
        break;
        case 'd':
        cout<<"Adaab"<<endl;
        break;
        case 'e':
        cout<<"Hey"<<endl;
        break;
        default:
        cout<<"note enter between a-e only"<<endl;
        break;
    }
}
