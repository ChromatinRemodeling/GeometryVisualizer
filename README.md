本脚本旨在可视化椭圆脐方程 $f = x^4 + y^4 + x^3 - 2 x y^2 + a (x^2 + y^2) + \theta_1 x + \theta_2 y$。

运行说明：

单击脚本下方的代码区域，按Shift+Enter运行代码。

参数 $\theta_1,\theta_2,a$ 如以上公式所述， $l$ 调整可视化的范围大小。

可以通过拖动滑块和点击滑条改变数值（可能会卡），也可以通过点击每个滑块右边的"+"号打开动画控件后直接修改数值。

可以通过点击图片并拖动四角来调整大小。

结果说明：

横纵坐标分别为x和y。

左图蓝色为 df/dx>=0 的区域，黄色为 df/dy>=0 的区域，区域边界即为零解线，零解线的交点即为不动点。稳定不动点（稳定结点）用蓝色圆圈标记，不稳定结点用绿色三角形标记，鞍结点用红色叉形标记。

右图的环形曲线为势能面的等高线，箭头为不动点附近的上升或下降方向。

参数说明：一些有趣的参数如下：

-0.3,0,0,1
0.15,0,0,1
-0.3,0,0.3,1
-0.3,0.45,0.45,1.5
-0.3,0.3,0,1.5
