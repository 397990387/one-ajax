# ES:
- 1:变量,常量,声明(解,设)一个变量.变量的命名规则.-(标识符).
- 2:数据类型.(规定了能够存放到变量内的值的种类).
number(3岁会数数),string(5岁写字),boolean(8岁懂道理).
object(18岁找对象),symbol(总觉得自己是最独一无二,一般人配不上自己).
undefined(30岁女朋友还是undefined),null(50挂了).
											
				
			
			
### 3:表达式
- 操作(运算)符:
 >算术,比较, 逻辑,三目,typeof ,instanceof,隐式转换
									
									
				
### 4:语句(控制结构)
- if
- for
- switch
- while
- do...while
- for...in
- for....of
			
### 5:内置对象.Math,Date,String,Array,正则
			
- 6:函数
  >1:声明和函数调用的关系.<br>			
  >2:形参和实参的关系.<br>
  >3:返回值和函数调用.<br>
  >4:作用域,全局变量,局部变量.<br>
  >5:作用域链,变量查找.<br>
  >6:闭包.<br>
  >7:递归....

			
- 7:对象(原型链)
>1:什么是类<br>
>2:什么是实例.<br>
>3:类和实例的关系<br>
>4:类和原型的关系,实例和原型的关系.<br>
>5:原型链.静态方法,原型方法.<br>				
>7:面向对象编程<br>
>处理this.call,apply,bind.<br>
>6:继承.<br>								
	>>子类继承父类的属性<br>
	>>子类继承父类的方法<br>
		
## DOM:			
- 1:什么是DOM树.
- 2:什么是节点.
- 3:节点有什么属性.<br>
 - `1;`nodeType(1是原生,2是属性,3是文本,8是注释,9是document,10是doctype)
- `2;`nodeName(元素节点的nodeName是全大写,#text,#comment,#document)
- `3;` nodeValue(注释节点,文本节点,属性节点才有nodeValue)							
								
## 4:节点的获取和操作:
- 获取
 >`获取子节点`:父节点.childNodes(伪数组)<br>
>`获取子元素`:父节点.children(伪数组)<br>
>`获取父元素`:子节点.parantNode<br>
>`获取兄弟节点`:当前节点.previousSiblings<br>
>`当前节点`.nextSiblings<br>
>获取兄弟元素:当前节点.previousElementSiblings
>当前节点.nextElementSiblings<br>
>`特殊方法`:通过id,标签,类名,选择器获取元素是特殊的获取方法.<br>
				
- ## 操作:
- >`创建`:let oDiv = document.createElement("div");<br>
>let str = document.createTextNode("1111111");<br>
>let oC = document.createComment("22222222");<br>
- `插入`:
>父元素.appendChild(子节点);<br>					
>父元素.insertBefore(新的节点,当前节点);<br>					
- `删除`:
>父元素.removeChild(子节点);						
			
- 事件对象,事件源.
- 事件流.
- 事件委托.
						
- BOM:
- >location
- >navigator
- >history