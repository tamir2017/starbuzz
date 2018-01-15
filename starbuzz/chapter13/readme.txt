1、html表格与css表格显示联系：html表格可以让你使用html标记制定表格的结构，而css表格显示（display：table，table-row，table-cell）则提供了一种方法，可以用一种类似表格的表现方式显示块级元素。HTML表格可以使用css来指定样式。另外，建立布局的古老方法可以使用表格建立布局，该方法很难建立正确的布局，而且还很难维护，实际上使用css表格显示会好很多，故建立布局建议采用html加css的方法。

2、html表格中可以添加<caption>标签来制定表格的title。

3、盒模型与表格的属性对比：盒模型和表格属性中均有内边距和边框，但是不同点是，与盒模型中的外边距不同的是，表格中使用border-spacing来表示边框边距的，定义该值是设置整个表格中边框之间的距离，注意不能为单个表格单元设置外边距。除了设置border-spacing外，还可以设置border-collapse值，该属性是折叠俩个相邻的cell。

4、CSS nth-child伪类，它用来设置奇偶数行的颜色。

tr:nth-child(odd){
  background-color: #fcba7a;
}

上述代码意思是奇数行的背景色为#fcba7a;

