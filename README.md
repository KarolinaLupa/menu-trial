# menu-trial
//menu trial
#include <iostream>


using namespace std;

int option;
int main()
{ 
    // menu with planets
    cout<<"Menu"<<endl;
    cout<<"Option 1- Sun"<<endl;
    cout<<"Option 2- Mercury"<<endl;
    cout<<"Option 3- Venus"<<endl;
    cout<<"Option 4- Earth Home"<<endl;
    cout<<"Option 5- Mars"<<endl;
    cout<<"Option 6- Jupiter"<<endl;
    cout<<"Option 7- Saturn"<<endl;
    cout<<"Option 8- Uranus"<<endl;
    cout<<"Option 9- Neptun"<<endl;
    cout<<"Option 10- Quit"<<endl;
    cin>>option;
    
    if(option ==1)
    {
        system("cls");
        cout<<"Sun"<<endl;
        system("pause");
        return 0;
    }
    if(option ==2)
    {
        system("cls");
        cout<<"Run kid run"<<endl;
        system("pause");
        return 0;
    }
    if(option ==10)
    {
        return 0;
        }
        else
        {
            cout<<"Incorrect Number"<<endl;
            system("pause");
        }
            
}
