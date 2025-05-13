
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body> <form action="D:\250305\test.html" method="post" enctype="multipart/form-data">
    <h1>欢迎登录</h1>
    <p>账号：<input type="text" name="account"></p>
    <p>密码：<input type="password" name="password"></p>
    <p>姓名：<input type="text" name="name"></p>
    <p>性别：<input type="radio" name="gender" value="male">男<input type="radio" name="gender" value="female">女</p>
    <p>年龄：<input type="text" name="age"></p>
    <p>电话：<input type="text" name="tel"></p>
    <p>邮箱：<input type="text" name="email"><select name="邮箱" id="">
        <option value="qq">.qq.com</option>
        <option value="163">.163.com</option>
        <option value="gmail">.gmail.com</option>
    </select></p>
    <p>地址：<input type="text" name="address"></p>
    <p>照片：<input type="file" name="photo"></p>
    <p>兴趣爱好：<input type="checkbox" name="hobby[]" value="reading" size="300">阅读<input type="checkbox" name="hobby[]" value="swimming">乒乓球<input type="checkbox" name="hobby[]" value="running">篮球</p>
    <p>个人简介：<br><textarea type="textarea" name=introduction rows="5" cols="50"></textarea></p>
    <p><h6>立即注册<input type="button" value="submit"></h6></p>
  <p><input type="submit" value="提交"></p>
    </form>
    
</body>
</html>
