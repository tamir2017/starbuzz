标签选择器与类选择器

考虑元素的继承关系。

子类元素可以覆盖父类元素中的样式值。

一个元素可以继承多个类，样式值取值根据css样式中，要求越严格的（子类优先于父类），要求级别相同的则查看css文件中最后设定的样式值，而不是查看html中的元素继承类的顺序。

border-bottom 属性与text-decoration : underline  对比：border-bottom 属性 会延伸到空间边缘，而text-decoration : underline只会在文字下有横线。