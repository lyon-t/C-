1 cout
=======
在使用cout的时候，如果输出一个字符串的首地址的时候，他会输出一整个字符串的内容
```
#include "stdafx.h"
#include<iostream>

using namespace std;

int main()
{
	  char *s = "apple";
	  cout<<s;
	  system("pause");
    return 0;
}
out: apple请按任意键继续. . .
```
