# Hello-Word
前端开启我的新世界
<h3>第一次学习使用GitHub</h3>
<form action="#"  method="get ">
    <fieldset>
        <legend>Personal Resume</legend>
    <input type="hidden" name="info" value="regist">
    <p> 用户名:<input type="text" name="username"
                   value="请用邮箱或者QQ登录" size="30px" maxlength="10" readonly="readonly"></p>
    <p>用户密码：<input type="password" name="pwd"></p>
    <p>用户性别：<input type="radio" name="sex" id="male"><label for="male">男</label>
        <input type="radio" name="sex" checked="checked" id="female"><label for="female">女</label></p>
    <p>用户爱好：<input type="checkbox" name="爱好" value="1" checked="checked">阅读
        <input type="checkbox" name="爱好" value="2">美食
        <input type="checkbox" name="爱好" value="3">打豆豆
    </p>
    <p>上传简历：<input type="file" name="resume"></p>
    <p>所在城市：
        <select name="citys">
            <option value="1" selected="selected">长沙</option>
            <option value="2">株洲</option>
            <option value="3">南宁</option>
            <option value="4">北海</option>
            <option value="5">重庆</option>
        </select>
    </p>
    <p>个人简介：
        <textarea name="" id="" cols="30" rows="10">我要成为前端大神</textarea>
    </p>
    <p>
        <input type="submit" value="提交" >
        <input type="image" src="images/login.gif">
        <input type="reset" value="重填">
    </p>
    <p></p>
    <!--<p><input type="button" value="这是一个button"></p>-->
    </fieldset>
</form>
</body>
