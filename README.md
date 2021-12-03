/this is a unary operator program in cpp
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
this is a binary operator in cpp
  #include<iostream>
  class A
  {
  int x;
  public:
  a(){}
  A(int i)
  {x=i; }
  void operator +(A)
  void display();
  };
  void A::operator+(A a)
  {
  int m=x+a.x;
  cout<<"the result of the addition of two objects is:"<<m;
  }
  void main()
  {
  A a1(5);
  A a2(4);
  a1+a2;
  getch();
  }
