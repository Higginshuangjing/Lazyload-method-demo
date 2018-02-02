# Lazyload-method-demo
懒加载的原理就是: 

1) offsetTop < inneHeight + scrollTop 再去加载图片
2) img标签的src初始属性为空,需要加载的时候再将图片地址放到src属性里面

注: 
offsetTop: 当前元素距离document顶部的距离
inneHeight: 当前显示屏幕的高度
scrollTop: 滚动条滚动高度
