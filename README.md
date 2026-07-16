# DS-subject
#include <iostream>
using namespace std;
struct book 
{
    string b_name;
    int no_of_pages;
    float price;
    
};
int main() {
    struct book b1,b2;
    b1.b_name="shadow fight trail";
    b1.no_of_pages=200;
    b1.price=300;
    cout<<b1.b_name<<endl;
    cout<<b1.no_of_pages<<endl;
    cout<<b1.price<<endl;

    return 0;
}
