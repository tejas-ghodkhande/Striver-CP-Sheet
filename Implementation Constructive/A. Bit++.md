## Link : https://codeforces.com/problemset/problem/282/A
```CPP
#include <iostream>
using namespace std;

int main() {
  int n,x=0;
  cin>>n;
  while(n--)
  {
      string exp;
      cin>>exp;
      if(exp.find('+')!=string::npos)
          x++;
      else
        x--;
  }
  cout<<x;
  
    return 0;
}
```
