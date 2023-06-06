# Web-DisplayImage
Web前端语言显示路径图片
<!DOCTYPE html>：声明文档类型为HTML。
<html>：HTML文档的根元素。
<head>：包含文档的元信息，如标题、引用的样式表和脚本等。
<title>显示路径图片</title>：指定页面的标题为"显示路径图片"。
<body>：HTML文档的主体部分，包含页面的内容。
<img id="image" src="" alt="路径图片">：创建一个<img>元素，设置id为"image"，src属性为空，alt属性为"路径图片"。这个元素用于显示图片。
<script src="script.js"></script>：引入JavaScript文件"script.js"。
  window.onload：当整个页面及相关资源加载完成后执行的事件。
function() { ... }：定义一个匿名函数。
var imagePath = "您的图片文件路径";：将您的图片文件路径存储在imagePath变量中。
var imageElement = document.getElementById("image");：通过id获取到id为"image"的元素，即之前定义的<img>元素。
imageElement.src = imagePath;：将imagePath赋值给imageElement的src属性，即设置<img>元素的图片路径为您的图片文件路径。
