jquery-bgiframe
===============

针对flash(wmod=window)使用的iframe背景插件
+/*!
+ * iframe背景层级插件，基于jQuery
+ * 
+ * 使用实例：
+ * $('#div').bgiframe()
+ * $('#div').bgiframe({left: 12})
+ * 
+ * flash因性能，文字输入等问题必需使用模式<param name="wmode" value="window">时，需使用iframe解决层级问题
+ * 注意：
+ *   1.iframe和目标定位必需为absolute。
+ * 	2.目标顶级div层级必需比flash的大
+ * 已知Bug:
+ *  IE7:需要特别注意外层容器(不一定是直接父容器)的z-index值，若外层任意定位过的容器的层级值不对会导致该插件失效。
+ * 浏览器兼容性：
+ * 	正常：FF,搜狗,IE7+
+ * 	不正常：
+ * @author esky
+ * @date 2012-03-26
+ */
