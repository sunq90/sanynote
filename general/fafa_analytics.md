# 三一发发路径对应的说明

使用Ctrl+F搜索核心词语可以快速找到解释

【首页】pages/index/index/index.html

【个人中心】pages/user/person/index.html

【动态详情】pages/index/detail/index.html

【用户登录】pages/user/login/index

【用户消息中心首页】pages/notice/index/index

【用户名片】pages/user/card/index

【赞通知消息详情】pages/notice/likes/index

【短文内容发布】pages/user/publish/index

【话题动态列表】pages/topic/detail/index

【Webview承载页】pages/search/webUrl/index

## 普通二维码

#### 如何创建带参数的二维码

1. 登录[草料二维码首页](https://cli.im/)，账号密码找管理员索要；

2. 点击【我的二维码】进入后台；

3. 在左侧分别选择【活码>网址码】；

4. 点击右上角【新建活码】，选择【页面跳转】；

5. 在地址栏输入需要跳转的地址，点击【生成二维码】；

6. 这时候二维码就会生成成功，但是一定要点击上方的修改标题，把标题修改了！

   二维码生成完毕！下载即可！

#### 如何修改带参数二维码地址？

直接在【网址码】的列表页面选择对应的二维码，点击【编辑】就可以进入和创建一模一样的页面了，在里面把网址修改掉，不需要替换原来的二维码，就可以修改链接了。

#### 如何查看统计？

直接在网址码里面就可以查看

## 小程序二维码

### 生成小程序二维码

点击下方链接，进入相关的生成页面：

#### [扫码后进入首页](http://cli.im/mina/qrcode/?tpl_id=23879&time=1566895535&publickey=4fbe1862abbfd829d92155157ed1454a)

媒介（edium）：传播媒介，如朋友圈海报、行业网站海报、线下物料

名称（name）：活动名称，如微挖大会，路机新品发布会

时间（time）：创建时间，用于区分同一活动不同时间发布的相同媒介物料，如190328

#### [扫码后进入动态详情](http://cli.im/mina/qrcode/?tpl_id=23880&time=1566895573&publickey=412870c37a87cf8baa269618adde8133)

动态ID（scene=id）：动态详情的ID号，可以在小程序后端管理面板查看

其他字段与进入首页的解释一致

#### [扫码后进入话题详情](http://cli.im/mina/qrcode/?tpl_id=24590&time=1566895589&publickey=5425f2f1a4b3a80104bcde17f352ec04)

话题ID（hid）：话题ID号，可以在小程序后台管理中查看

其他字段与进入首页的解释一致

注意：所有的UTM字段，均使用非中文的方式进行标注。

### 如何查看二维码统计

之前想的是用百度统计，这样就可以直观的看到带参数二维码了，但是百度统计貌似有些问题。

大家现在只能够通过[微信小程序的管理面板](https://mp.weixin.qq.com/)来进行查看。

分别点击【统计>使用分析>页面分析】，然后往下使劲儿拉，拉到最低价，就可以看到二维码访问数据了。

