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
    cout<<"Option 4- Earth Means Home"<<endl;
    cout<<"Option 5- Mars"<<endl;
    cout<<"Option 6- Jupiter"<<endl;
    cout<<"Option 7- Saturn"<<endl;
    cout<<"Option 8- Uranus"<<endl;
    cout<<"Option 9- Neptun"<<endl;
    cout<<"Option 10- Quit"<<endl;
    cin>>option;
    
    if(option ==1) //sun
    {
        system("cls");
        cout<<"Any ideas how to come back"<<endl;
        system("pause");
        return 0;
    }
    if(option ==2) //mercury
    {
        system("cls");
        cout<<"Run kid run"<<endl;
        system("pause");
        return 0;
    }
    
    //venus
    if(option ==3)
    {
        system("cls");
        cout<<"Can you hear this music"<<endl;
        system("pause");
        return 0;
    }
    
    
    if(option ==4) //earth
    { 
        system("cls");
        cout<<"I can see my house! Let's land"<<endl;
        system("pause");
        return 0;
    }
    if(option ==5) //Mars
    {
        system("cls");
        cout<<"Why is this planet red?"<<endl;
        system("pause");
        return 0;
    }
    if(option ==6) // jupiter
    { 
        system("cls")
        cout<<"Can you spot that red spot?"<<endl;
        system("pause")
        return 0;
    }
    if(option ==7) //saturn
    {
        system("cls");
        cout<<"Awsome! Planet with a ring"<<endl;
        system("pause")
        return 0;
    }
    if(option ==8) // Uranus
    {
        system("cls");
        cout<<"We are now approaching... smurfs ice cream cone"<<endl;
        system("pause")
        return 0;
    }
    if(option ==9) // Neptune
    { 
        system("cls");
        cout<<"Can feel that wind"<<endl;
        system("pause")
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
