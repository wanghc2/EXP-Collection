##修改navbar的背景颜色

>找到bootstrap.min.css文件,替换navbar-inverse的样式
>.navbar-inverse{background-color:#1A5A05;border-color:#1A5A05}.navbar-inverse

在自定义样式表，如`custom.css`中，使用样式继承的方式修改`navbar-inverse`的样式会更好

```css
.navbar-inverse.mystyle
{
	background-color: #1A5A05;
	border-color:     #1A5A05;
}
```