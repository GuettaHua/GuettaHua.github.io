---
layout: post
title: linux command
date: 2017-12-10 00:00:00 +0300
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: # Add image post (optional)
---

 ## ？
 ```
 a=10
 (( t=a<50?8:9 ))
 echo $t
 ```
  `$ : > test.sh `  # 文件“test.sh”现在被清空了
  
  val=\`expr $a + $b`  
  
  val=\`expr $a \\* $b`
  
  
  原生bash不支持简单的数学运算，但是可以通过其他命令来实现，例如 awk 和 expr，expr 最常用。
expr 是一款表达式计算工具，使用它能完成表达式的求值操作。
注意使用的反引号（esc键下边）
表达式和运算符之间要有空格$a + $b写成$a+$b不行
条件表达式要放在方括号之间，并且要有空格[ $a == $b ]写成[$a==$b]不行 乘号（*）前边必须加反斜杠（)才能实现乘法运算

-eq -ne -gl -lt -ge -le

## string operator
1. =
2. !=
3. -z length=0? true
4. -n length!=0? true
5. str empty?true

## file operator
1. -e
2. -f 
3. -d directory

