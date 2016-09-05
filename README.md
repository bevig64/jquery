# jquery

//首先  关于js中的闭包问题
//所谓闭包 就是在函数中调用函数外的变量

//而 例如
  （function($){ //code } )(jquery);
  
  jquery 是实参    $是形参
  
  可以看作：
  function tmp($){ //code }
  
  tmp(jquery);
  
  
