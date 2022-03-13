在C语言中，动态分配内存用 malloc() 函数，释放内存用 free() 函数。如下所示：
```c++
int *p = (int*) malloc( sizeof(int) * 10 );  //分配10个int型的内存空间
free(p);  //释放内存
```
在C++中，这两个函数仍然可以使用，但是C++又新增了两个关键字，new 和 delete：new 用来动态分配内存，delete 用来释放内存。
