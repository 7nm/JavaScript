# JavaScript 常用效果和样式
### mask 引用方式
    引用方式：
	<link rel="stylesheet" href="../mask.min.css">
	<script type="text/javascript" src="../mask.min.js"></script>

### mask 属性
#### alert 属性：
    alert("内容", //  可传入html 例如："<div>我是mask.alert 框！</div>"
    {
        className:"className",//最外层样式类名称 ，默认 "mask-wrap"
        title:"我是标题",// 默认 “消息”
        txt:"好",// 按钮名字，默认“确定”
    })；
#### msg 属性：
    mask.msg("内容", //  可传入html 例如："<div>mask.msg 框！</div>"
    {
        className:"className",//最外层样式类名称 ，默认 "mask-wrap"
        time:1000,// 显示的时间,默认 1500
    });
#### confirm 属性：
    mask.confirm("内容", //  可传入html 例如："<div>我是mask.confirm 框！</div>"
    {
        className:"className",//最外层样式类名称 ，默认 "mask-wrap"
        txts:["同意","不同意"],// 按钮名字，默认[“确定”，“取消”]
        title:"我是标题",// 默认 “消息”
        sure:function(){},//按钮事件
        cancel:function(){},//按钮事件
    });
    
