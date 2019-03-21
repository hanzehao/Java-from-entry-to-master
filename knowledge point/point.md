左移最低位补0，右移最高位补最高位，无符号右移>>>最高位补0

###### 字符串 

 length()和lastIndexOf("")作用相同

substring() 截取制定的字符串  参数可以为一个起始或加上结束

trim() 返回去掉字符串前后的空格的字符串的副本

==比较运算符是比较两个对象的地址是否相同，字符串比较需要使用equals() ，equalsIgnoreCase()不区分大小写

使用compaeTo来比较两个字符串在字符字典中的顺序大小

string 少量字符串操作快

StringBuilder 线程不安全，单线程字符串操作优选

StringBuffer 多线程安全

