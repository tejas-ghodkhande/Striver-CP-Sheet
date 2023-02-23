## Link : https://codeforces.com/contest/514/problem/A


```CPP
#include <iostream>
using namespace std;

int main() {
    string x,res="";
    cin>>x;
    for(int i=0;i<x.length();i++)
    {
        int num=x[i]-48;
        int diff=9-num;
        if(i==0)
        {
            if(diff==0)
              res=res+x[i];
            else{
                if(diff>num)
                  res=res+x[i];
                 else
                   res=res+to_string(diff);
            }
        }
        else
        {
             if(diff>num)
                  res=res+x[i];
                 else
                res=res+to_string(diff);
        }
       
            
    }
    cout<<res;

    return 0;
}

```
