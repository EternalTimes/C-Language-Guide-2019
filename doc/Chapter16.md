<!--

字符数组和字符串

用来存放字符的数组称为字符数组。字符数组的各个元素依次存放字符串的各字符,字符数组的数组 名代表该数组的首地址,这为处理字符串中个别字符和引用整个字符串提供了极大的方便。 字符数组的定义形式与前面介绍的数值数组相同。例如: 
char c[10];

   


字符数组也允许在定义时进行初始化赋值。例如: 
char c[6]={'c', ' h ', 'i', 'n', 'a' , '\0' };

   


对字符数组的各个元素逐个赋值后,各元素的值为: 
c[0]= 'c',c[1]= 'h',c[2]= 'i',c[3]= 'n',c[4]= 'a',c[5]= '\0';

   


其中,‘\0’为字符串结束符。如果不对 c[5]赋任何值,‘\0’会由系统自动添加。 
字符数组也可采用字符串常量的赋值方式,例如: 
char a[]={"china"};


   -->