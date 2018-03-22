<!-- 表头 -->
<!DOCTYPE html>
<html>
<head>
   <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
	<title>制作我的第一个网页</title>
</head>
<body>
<h1>网站一级标题</h1>
<!-- 链接部分 -->
<ul>
    <li><a href="#">导航链接一</a></li>
    <li><a href="#">导航链接二</a></li>
    <li><a href="#">导航链接三</a></li>
    <li><a href="#">导航链接四</a></li>
</ul>
<h2>文章一级标题</h2>
<h2>文章二级标题</h2>
<p>
    文章作者&nbsp;文章发表时间</p><hr />
<p>这是一个很长的段落这是一个很长的段落<br>换行</br>这是一个很长的段落这是一个很长的段落<a href="www.baidu.com" title="百度">点击进入百度</a>这是一个<strong>很长</strong>的<em>段落</em>这是一个很长的段落这是一个很长的段落
<br>这是一个很长的段落<br>这是一个很长的段落<br>这是一个很长的段落<br>这是一个很长的段落</p>
<!-- 开始另一段 -->
<h2>另一篇文章的一级标题</h2>
<h2>文章的二级标题</h2>
<p>文章作者&nbsp;文章发表时间</p>
<p>这是一个很长的段落,这是一个很长的段落,这是一个很长的段落,这是一个很长的段落,这是一个很长的段落,这是一个很长的段落,这是一个很长的段落,这是一个很长的段落,这是一个很长的段落,这是一个很长的段落,这是一个很长的段落.<a href="www.baidu.com" title="百度">点击进入百度</a>这是一个很长的段落.<br>
<img src="https://ss1.bdstatic.com/70cFuXSh_Q1YnxGkpoWK1HF6hhy/it/u=1015130022,2732872721&fm=27&gp=0.jpg" title="女孩">
<!-- 无序列表部分 -->
<ul>
    <li>列表项目一</li>
    <li>列表项目二</li>
    <li>列表项目三</li>
</ul>
<h2>一大波图片</h2>
<!-- 自定义序列部分 -->
<dl>
<dd>小女孩图片<br>
<img src="https://ss1.bdstatic.com/70cFuXSh_Q1YnxGkpoWK1HF6hhy/it/u=1015130022,2732872721&fm=27&gp=0.jpg" alt="小女孩图片" titlr=图片></dd><br>
<dd>小女孩图片<br>
<img src="https://ss1.bdstatic.com/70cFuXSh_Q1YnxGkpoWK1HF6hhy/it/u=1015130022,2732872721&fm=27&gp=0.jpg" alt="小女孩图片" titlr=图片></dd><br>
<dd>小女孩图片<br>
<img src="https://ss1.bdstatic.com/70cFuXSh_Q1YnxGkpoWK1HF6hhy/it/u=1015130022,2732872721&fm=27&gp=0.jpg" alt="小女孩图片" titlr=图片></dd><br>
<dd>小女孩图片<br>
<img src="https://ss1.bdstatic.com/70cFuXSh_Q1YnxGkpoWK1HF6hhy/it/u=1015130022,2732872721&fm=27&gp=0.jpg" alt="小女孩图片" titlr=图片></dd><br>
<dd>小女孩图片<br>
<img src="https://ss1.bdstatic.com/70cFuXSh_Q1YnxGkpoWK1HF6hhy/it/u=1015130022,2732872721&fm=27&gp=0.jpg" alt="小女孩图片" titlr=图片></dd><br>
<dd>小女孩图片<br>
<img src="https://ss1.bdstatic.com/70cFuXSh_Q1YnxGkpoWK1HF6hhy/it/u=1015130022,2732872721&fm=27&gp=0.jpg" alt="小女孩图片" titlr=图片></dd><br>
<dd>小女孩图片<br>
<img src="https://ss1.bdstatic.com/70cFuXSh_Q1YnxGkpoWK1HF6hhy/it/u=1015130022,2732872721&fm=27&gp=0.jpg" alt="小女孩图片" titlr=图片></dd><br>
</dl>
<h2>最后一篇文章一级标题</h2>
<h2>二级标题</h2>
<p>
文章作者&nbsp;文章发表时间
</p>
<!-- 有序列表1部分 -->
<ol>
    <li>排名1</li>
    <li>排名2</li>
    <li>排名3</li>
</ol>
<!-- 表格部分 -->
<table>
<table border="1">
    <tr>
       <th>表头</th>
       <th>表头</th>
       <th>表头</th>
    <tr>
       <td>表内容单元格</td>  
       <td>表内容单元格</td>
       <td><a href="#">操作</td></a>
    <tr>
       <td>表内容单元格</td>
       <td>表内容单元格</td>   
       <td><a href="#">操作</td></a>
     <tr>  
       <td>总计</td>
       <td colspan="2">1000</td>
       <!-- colspan是合并单元格 -->
</table>
<!-- 终于到最下面了 -->
<h2>这里以后是一个侧栏,这是侧栏的标题</h2>
<h2>侧栏注册窗口标题</h2>
<dl>
    <dt>
    <form method="post" action="save.php">
    <!-- 上面一排是给后端的 -->
    请输入邮箱地址:
      <input type="text" name="myName" value="这是一个文本输入栏"><br> 
      <!-- 上面一排就是一个文本框 -->
    </form>
    </dt><br>
     <dt>邮箱地址请按要求格式输入</dt><br>
     <dt>
          <form method="post" action="save.php">
          请输入密码:
          <input type="pass" name="myWord" value="这里输入密码">
          请重复输入密码:
          <input type="pass" name="myWord" value="请重复输入密码">
          </form>
     </dt></br>
      <dt>密码请输入6-16位英文数字</dt></br>
</dl>

     <form method="post" action="save.php">
        <label>性别:</label>
        <label>男</label>
        <input type="radio" value="1" name="gender" checked="checked"/>
        <!-- radio单选checkbox复选 value和name给后台的 checked是默认选中 -->
        <label>女</label>
        <input type="radio" value="2" name="gender" />
       </form>
     <form method="post" action="save.php">
        <label>城市:</label>
        <select>
           <option value="武汉">武汉</option>    
           <option value="上海">上海</option>
           <option value="北京" selected="selected">北京</option>  <option value="深圳">深圳</option>
        </select>
        <label>爱好:</label>
        <input type="checkbox" name="checkbox1" value="运动">运动
        <input type="checkbox" name="checkbox2" value="艺术">艺术
        <input type="checkbox" name="checkbox3" value="科学">科学
        <label>个人简介</label>
        <textarea cols="18" rows="2">这是一个多行输入框,输入您的个人描述</textarea>
        <input type="submit" value="确认提交" name="submit">
        </form>
</body>
</html>
