# 半月两题编程题答案及测试数据

## 目录结构

+-- Round x: 第 x 次的题  
&nbsp;&nbsp;&nbsp;&nbsp;+-- Solution.c: 参考实现  
&nbsp;&nbsp;&nbsp;&nbsp;+-- Test: 测试数据  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;+-- in: 输入  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;+-- x.txt: 第 x 组输入  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;+-- out: 输出  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;+-- x.txt: 第 x 组输出

## 使用方法

由于某些输入很大，请使用 FILE*/freopen()/fstream  
例：

    freopen("in/x.txt", "r", stdin);
    freopen("out/x.txt", "w", stdout);

    FILE * input = fopen("in/x.txt", "r");
    FILE * output = fopen("out/x.txt", "w");

    ifstream fin("in/x.txt");
    ofstream fout("out/x.txt");

参见：  
<https://zh.cppreference.com/w/c/io/freopen>  
<https://zh.cppreference.com/w/c/io/fopen>  
<https://zh.cppreference.com/w/cpp/io/basic_ifstream>  
<https://zh.cppreference.com/w/cpp/io/basic_ofstream>  