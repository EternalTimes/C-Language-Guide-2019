<!--
函数的调用

主调函数使用被调函数的功能,称为函数调用。在 C 语言中,只有在函数调用时,函数体中定义的功 能才会被执行。C语言中,函数调用的一般形式为: 
函数名(类型 形参,类型 形参...); 
对无参函数调用时则无实际参数表。实际参数表中的参数可以是常数、变量或其他构造类型数据及表 达式,各实参之间用逗号分隔。 

在C语言中,可以用以下几种方式调用函数。 
(1)函数表达式:函数作为表达式中的一项出现在表达式中,以函数返回值参与表达式的运算。这种 方式要求函数是有返回值的。例如: 
z=max(x,y);

   

是一个赋值表达式,把 max 的返回值赋予变量 z。 
(2)函数语句:函数调用的一般形式加上分号即构成函数语句。例如: 

   
printf ("%d",a);
scanf ("%d",&b);

    

都是以函数语句的方式调用函数。 
(3)函数实参:函数作为另一个函数调用的实际参数出现。这种情况是把该函数的返回值作为实参进 行传送,因此要求该函数必须是有返回值的。例如: 


printf("%d",max(x,y));  /*把 max 调用的返回值作为 printf 函数的实参*/

    

在主调函数中调用某函数之前应对该被调函数进行声明。在主调函数中对被调函数进行说明的目的是 
使编译系统知道被调函数返回值的类型,以便在主调函数中按此种类型对返回值进行相应的处理。其一般 
形式为: 
类型说明符 被调函数名(类型 形参,类型 形参...); 
需要注意的是,函数的声明和函数的定义有本质上的不同。主要区别在以下两个方面: 
(1)函数的定义是编写一段程序,应有函数的具体功能语句——函数体;而函数的声明仅是向编译系 统的一个说明,不含具体的执行动作。 
(2)在程序中,函数的定义只能有一次,而函数的声明可以有多次。
-->