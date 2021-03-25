# CSS_style
关于一些好玩的css特效学习和分享.


### 关于Loading的注意事项：
   [CSDN博客地址:](https://blog.csdn.net/qq_45906219/article/details/115210433)
  - 给标签加上style: -- 前缀 我们就可以是用 var(--) 或者 冒号对应的后面的值
    然后通过cacl来计算对应的数值
    比如 style="--i:1"  var(--i)  = 1
  - box-shadow 可以设置多个阴影区域
  - transform 如果需要覆盖 可能会出现问题 所以需要把之前的样式 重新进行覆盖的写,
    否者会出现一些其他的问题, 依然是先位移 然后进行其他的转换 2D  3D
  - 动画的延迟时间也是可以通过calc来进行插值计算  值的获取通过var来获取标签里面的stle设置
    初始
  - calc() 的计算确实很不错.