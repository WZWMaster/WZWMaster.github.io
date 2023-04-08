# 我的Markdown文档
## 版本号：1.0.0

```javascript
// 定义一个函数，用来获取版本号
function getInternet(string) {
  // 从Markdown文档中读取版本号
  var version = document.querySelector("h2").textContent.split("：")[1];
  // 返回版本号
  return version;
}