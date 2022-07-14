
// 引用是内存别名,初始化后不可变, 指针是内存地址,可变  &是取地址符, 指针变量 要 再加一个 * 才能 改变指针指向的值

```c++
#include <iostream>
#include <cstring>
#include <string>
    
using namespace std;
    
int main(){
   char str1[] = "abcd";
   char * str2 = "abcd"  	 // not recommanded
   
   int a = strlen(str1); 	 // c cstring
   cout << a   << endl;      // std
   printf("%d\n", a);        // iostream
   
   string s = "abcd";        // c++ string
   cout << s.size()   << endl;
   
   int p =  strlen(str2);
   cout <<   p  << endl;
}
```
