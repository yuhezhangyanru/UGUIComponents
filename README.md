# UGUIComponents
 UGUI Optimization or Costumized Components easy to use.
 

# 资源说明：

-  ScrollRectOptimizationPackage.unitypackage:
ScrollRect组件的优化，限制了惯性滚动的时间，避免刷新太久，并且添加了滚动停止时执行的事件：stopScrollCallback，因为 OnDragEnd 并不可靠，OnDragEnd 只是手停止拖动时的执行，如果带惯性滚动的话，OnDragEnd响应后实际上还会自由滑动一段时间！

网络请求重要的地方加锁和IF1保持一致

1.表现不太满意，好多时候发现问题但卡在自己的技术水平上，还是自己的技术有待提升，