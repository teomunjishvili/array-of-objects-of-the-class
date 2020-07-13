#include <iostream>
#include <string>
using namespace std;

class Person
{
    /*private variables*/
        string a;
        int b;
        
    public:
        Person (string name, int age)
        {
            a = name;
            b = age;
        }
        
    void display()
    {
        cout<<"Name: "<<a<<endl;
        cout<<"Age: "<<b<<endl;
    }
};

int main ()
{
    Person array[5] = {Person("Teo", 20), Person ("Nick", 19), Person ("Lily", 21), Person ("Natia", 20), Person ("Alex", 25)};
    array[0].display();
    array[1].display();
    array[2].display();
    array[3].display();
    array[4].display();
    
    return 0;
}
