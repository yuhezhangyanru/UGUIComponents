 # UGUIComponents

 UGUI Optimization or Costumized Components easy to use.

 



# 资源说明：

_ _ _



-  ScrollRectOptimizationPackage.unitypackage:

ScrollRect组件的优化，限制了惯性滚动的时间，避免刷新太久，并且添加了滚动停止时执行的事件：stopScrollCallback，因为 OnDragEnd 并不可靠，OnDragEnd 只是手停止拖动时的执行，如果带惯性滚动的话，OnDragEnd响应后实际上还会自由滑动一段时间！

 

_ _ _





- WorldPositiontoScrrenPositionTool.unitypackage:

游戏中有多个摄像机的时候，把场景中对象的坐标转化到画布坐标使用，其实很简单，但还是备忘记录一下吧。
