
<h1>那些年你用过的表示论：</h1>

<h2>嘉当矩阵，素根与表示的权：</h2>
<p>对于性质足够好的李代数，他有着嘉当子代数（最大的阿贝尔子代数）{H<sub>i</sub>}
</p>
<body>
<code mkd>
  [H_i,H_j]=0
  [E_{\alpha},H_i]=\alpha^i\cdot E_{\alpha}
</code>
<script src="https://cdn.jsdelivr.net/npm/marked@3.0.0/marked.min.js"></script>
<script> // 21年那时代码写得比较烂，献丑了，现在重写一版
var m = document.querySelectorAll('code[mkd=""], pre[mkd=""]');
for(var i = 0; i < m.length; i++){
  var e = m[i];
  var div = document.createElement('div');
  div.className = 'mkd';
  div.innerHTML = marked(e.innerHTML.trim());
  e.parentNode.insertBefore(div, e);
  e.setAttribute('mkd', 1); // 此处用标记防止重复解析
}
</script>
<style>
div.mkd + code[mkd], div.mkd + pre[mkd]{
  display: none;
}
</style>
</body>

作者：知乎用户
链接：https://www.zhihu.com/question/53311539/answer/1837760394
来源：知乎
著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。
