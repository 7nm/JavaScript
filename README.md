# JavaScript 常用效果和样式
## attached 引用方式
    引用方式：
	<link rel="stylesheet" href="../attached.min.css">
	<script type="text/javascript" src="../attached.min.js"></script>

# attached 属性
#### alert 属性：
    alert("内容", //  可传入html 例如："<div>我是attached.alert 框！</div>"
    {
        className:"className",//最外层样式类名称 ，默认 "attached-wrap"
        title:"我是标题",// 默认 “消息”
        txt:"好",// 按钮名字，默认“确定”
    })；
#### msg 属性：
    attached.msg("内容", //  可传入html 例如："<div>我是attached.msg 框！</div>"
    {
        className:"className",//最外层样式类名称 ，默认 "attached-wrap"
        time:1000,// 显示的时间,默认 1500
    });
#### confirm 属性：
    attached.confirm("内容", //  可传入html 例如："<div>我是attached.confirm 框！</div>"
    {
        className:"className",//最外层样式类名称 ，默认 "attached-wrap"
        txts:["同意","不同意"],// 按钮名字，默认[“确定”，“取消”]
        title:"我是标题",// 默认 “消息”
        sure:function(){},//按钮事件
        cancel:function(){},//按钮事件
    });
    
