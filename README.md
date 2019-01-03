# GlidePages
完美引导页，左右滑动，最后进入主页，完全自定义view，

完全代码实现其逻辑
自定义引导页
高仿雅虎引导页。动画完全自定义，左右滑动。
代码简洁，易懂。
动画效果图：
![image](https://github.com/1136346879/picture_dx/blob/master/image_flod/guideYahu.gif)


SunMoonView  太阳和月亮绕圆心旋转的动画
 * 第二个  太阳和月亮的view
 * 从第一个view进入 顺时针旋转（太阳和月亮）
 * 从第二个view返回 逆时针旋转（太阳和月亮）

Direction	备注
Path.Direction.CCW	counter-clockwise ，沿逆时针方向绘制
Path.Direction.CW	clockwise ，沿顺时针方向绘制

 //虚线
  DashPathEffect dashPath = new DashPathEffect(new float[]{4, 5}, (float) 1.0);
  mPaint.setPathEffect(dashPath);
  
  
  绘制常规图形
  
  //绘制圆
addCircle(float x, float y, float radius, Direction dir) 
 //绘制椭圆
addOval(RectF oval, Direction dir)
addOval(float left, float top, float right, float bottom, Direction dir) 
//绘制矩形
addRect(RectF rect, Direction dir) 
addRect(float left, float top, float right, float bottom, Direction dir) 
//绘制圆角矩形
addRoundRect(RectF rect, float rx, float ry, Direction dir) 
addRoundRect(float left, float top, float right, float bottom, float rx, float ry,Direction dir)
addRoundRect(RectF rect, float[] radii, Direction dir)
addRoundRect(float left, float top, float right, float bottom, float[] radii,Direction dir)





