1 算法分析
如何来评价一个算法的好坏
   1.1 复杂度分析
    最好，最坏，最平均       
    int sum(int i){
        int sum = 0;
        for(int j=0; j < i; j++){
            sum+=sum
        }
        return sum
    }
    
   指出 T(n) = O(f(n))
   T(n)它表示代码执行的时间；
   n表示数据规模的大小；f(n)表示每行代码执行的次数总和。
   因为这是一个公式，所以用f(n)来表示。
   公式中的O，表示代码的执行时间T(n)与f(n)表达式成正比
1.1.1时间复杂度分析
  1.只关注循环执行次数最多的一段代码
  2.加法法则：总复杂度等于量级最大的那段代码的复杂度
  3.乘法法则：嵌套代码的复杂度等于嵌套内外代码复杂度的乘积
 O(1)  
 
 O(n^2)
 
 O(logn)   
 
    i = 1;
    while(i <= n){
       i = i * 2   
    }
 O(nlogn)
 
1.1.2 空间复杂度 均摊时间复杂度

java 中一个对象占用的空间