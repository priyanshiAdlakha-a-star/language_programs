//unary operator program in cpp
#include<iostream>
using namespace std;
class test
{
private:
int num;
public:
test():num(8){}
void operator ++()
{
num=num+2;
}
void print()
{
cout<<"the count is:"<<num;
}
};
void main()
{
test tt;
++tt;
tt.print();
getch();
}
