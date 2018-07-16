# 项目协同

当多人开发一个项目的时候，协同开发就显得很重要了。

### 项目成员管理

每个项目都有一个发起者，发起者创建项目后，可以打开成员协作面板（按照下图操作，成员那里输入成员的昵称即可，角色可以随便选，也可进行修改），该面板提供了对成员的增删改查操作，拉进项目后，新的成员在首页的项目列表中就可以查看到这个协同项目了。

![](../.gitbook/assets/image%20%2810%29.png)

  


![](../.gitbook/assets/image%20%2823%29.png)

当拉了新人进来之后，我们就可以协同开发了。

![&#x6210;&#x5458;&#x64CD;&#x4F5C;](../.gitbook/assets/image%20%2832%29.png)

通过上图的菜单，可以对成员进行管理，包括角色的更换，以及赋予权限，移除成员。当给成员赋予权限后，改成员也会拥有修改其他成员信息的能力。

### 项目数据管理

大家都可以在页面设计之后把页面上传到云端，点击右上方的小圆圈，他会确认你是否是最新的版本，如果是最新的版本，直接点击上传即可。

![](../.gitbook/assets/image%20%2815%29.png)

当A上传之后，B在上传，就会有一个问题，B的修改可能和A修改的冲突了，所以B上传的时候，会提示先拉取合并本地再上传。

![](../.gitbook/assets/image%20%2820%29.png)

B在上传代码前，只能先下载同步，如果是直接下载同步，那么会覆盖自己修改的内容，为了能让冲突时的风险减低，我们在拉取代码后，提供了样式组件合并面板，组件合并面板，页面合并面板，B用户需要自行选择本地和云端应该保留哪种组件和页面。这一个步骤是很重要且严肃的，应当谨慎操作，否则很可能自己修改的内容被云端内容覆盖掉。

![](../.gitbook/assets/image%20%2833%29.png)

#### PS: 开发的时候，为了尽量少的产生冲突，协同作业的时候，应该尽量不同人员设计不同的最小单元（组件，页面..）
