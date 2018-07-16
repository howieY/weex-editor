# 画布状态

画布包含 设计编辑、组件编辑、样式组件编辑、组件临时编辑 三种状态，可以在设计编辑状态和其他状态间切换。



### 设计编辑状态

该状态为画布默认状态，提供项目界面编辑

{% page-ref page="hua-bu.md" %}



### 组件编辑状态

在设计编辑状态，右键选择编辑源组件，跳转到该状态；点击 “返回设计” 返回到设计编辑

![&#x7F16;&#x8F91;&#x6E90;&#x7EC4;&#x4EF6;](../../.gitbook/assets/zu-jian-bian-ji.png)

该状态下，可以添加、修改、编辑组件

组件编辑状态下，画布中每一个画布对应一个组件



### 样式组件编辑状态

TODO

### 组件临时编辑状态

![&#x7EC4;&#x4EF6;&#x4E34;&#x65F6;&#x7F16;&#x8F91;](../../.gitbook/assets/image%20%2838%29.png)

  
该状态下，只能编辑元素的内容和样式，不能添加和删除元素

编辑后的样式会覆盖源组件，源组件修改后不再同步

可以“重置”之前覆盖的编辑，重新同步源组件
