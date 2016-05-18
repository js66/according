# according
一个可以折叠的手风琴jquery组件

#插件演示[演示效果Demo](http://js66.github.io/according/)

#用法


##step1 引用jquery
```
	<script src="js/jquery-1.9.1.min.js"></script>
```
##step2 引用插件according
`<script src="js/jquery.according.js"></script>`

##step3 调用插件
```
$(function(){
				var unload=true;
				$("#acc,#acc2").according({"start":0});
				
			});
```

###step3  html格式书写
```
<div class="acc" id="acc">
			<h3>header</h3>
			<div class="content">wo 是内容</div>
			<h3>header2</h3>
			<div class="content">wo 是内容2</div>
			<h3 id="loadbtn">header3</h3>
			<div class="content">wo 是内容3</div>
		</div>
```




