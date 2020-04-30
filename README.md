# LAYUI
LAYUI框架组件使用

#form 表单  class="layui-form"

#'<div' class="layadmin-user-login-box layadmin-user-login-body layui-form">
  <form>
    
  #提交的参数定义
  #data: obj.field 比如 name="username" 字段为usrername  lay-verify="required"为必填项
 # 按钮：
'<'button class="layui-btn layui-btn-fluid" lay-submit lay-filter="LAY-user-login-submit1">登 入</button>
  # 提交标志lay-submit
 #  提交对象 
#   forms = layui.form;
#//提交
#forms.on('submit(demo)',function (res) {
#//上面括号的demo 就必须用到lay-filter里的值
#}）


