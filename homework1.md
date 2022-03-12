# web-
仅供学习参考，严禁直接用于商业或者学术活动，copy所带来的一切后果由copy者个人承担
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>蛋糕商城</title>
    <style>
div{float: right}
    </style>
</head>
<body>
<nav>
        <a href="/index">首页</a>
        <a href="dropdown-toggle"data-toggle="dropdown">商品分类<b class="caret"></b> </a>
        <a href="#">热销</a>
        <a href="#">新品</a>
        <a href="#"class="active">注册</a>
        <a href="#">登录</a>
    <div align="right"><input type="text"class="form-control"name="keyword">
        <button type="submit"class="btn btn-default">搜索
            <!--            <c:if test="${param.flag==7}">active</c:if>-->
            <!--            <aria-label></aria-label>-->
        </button>
        <button type="submit"class="btn btn-default">购物车</button></div>
<!--    <ul class="dropdown-menu multi-column columns-2">-->
<!--        <div class="row"><div class="col-sm-12">-->
<!--            <h4>商品分类</h4>-->
<!--            <ul class="multi-colum-dropdown">-->
<!--                <li><a class="list" href="/goods_list">全部系列</a> </li>-->
<!--&lt;!&ndash;                <c:forEach items="${typeList}" var="t">&ndash;&gt;-->
<!--&lt;!&ndash;                    <li><a class="list"href="/goods_list?typeid=${t.id}"> ${t.name}</a></li>&ndash;&gt;-->
<!--&lt;!&ndash;                </c:forEach>&ndash;&gt;-->
<!--            </ul>-->
<!--        </div>-->
<!--        </div>-->
<!--    </ul>-->
</nav>
<form action="/usr_rigister" method="post">
<center>
    <h3 style="color: coral">
        注册新用户
    </h3>
    <p class="input">
        <span>用户名<label style="color: red">*</label> </span>
        <input type="text" name="username" placeholder="请输入用户名" required="required">
    </p>
    <p class="input">
        <span>邮箱<label style="color: red">*</label> </span>
        <input type="text" name="email" placeholder="请输入邮箱" required="required">
    </p>
    <p class="input">
        <span>密码<label style="color: red">*</label> </span>
        <input type="password" name="password" placeholder="请输入密码" required="required">
    </p>
    <p class="input">
        <span>收货人<label style="color: red">*</label> </span>
        <input type="text" name="name" placeholder="请输入收货人">
    </p>
    <p class="input">
        <span>收获电话<label style="color: red">*</label> </span>
        <input type="text" name="phone" placeholder="请输入收获电话">
    </p>
    <p class="input">
        <span>收获地址<label style="color: red">*</label> </span>
        <input type="text" name="address" placeholder="请输入收获地址">
    </p>
    <p class="clearfix"></p>
</center>
    <center>
        <p class="register-but text-center">
            <input type="submit" value="提交"><p class="clearfix"></p>
        </p>
    </center>
</form>
<footer>
    <center>
<!--    <div class="footer">-->
<!--        <div class="container">-->
<!--            <div class="text-center" align="center">-->
                <p>heima www.itcast.cn ⓒ ALL right Reseverd</p>
<!--        </div> </div>--></center>
</footer>
</body>
</html>
