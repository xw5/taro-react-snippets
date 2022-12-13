# Taro React开发常用代码段插件
>根据缩写快速提供代码模板，提高开发速度，代码段持续更新中......
<br />

## 使用建议
>考虑到用户的记忆成本，用户无需记忆所有代码段的缩写，输入特殊开头字符则会带出当前类别下的代码段，优化使用体验，定义如下使用规则：
>- 在js/jsx下输入taro就带出taro特有的代码段
>- 支持不带特殊符号的输入形式：如taronavigate和navigate都能带出taro路由跳转代码段
>- 代码段匹配字段都会尽量使用语义化的字段,如tarosetstorage:获取缓存，这样可以让用户记忆不再有太大记忆负担

<br />

## 目前支持的模板

### Javascript代码模板

|  缩写  |  模板  
|  ----  |  ----
|  tarohide  |  taro toaset loading隐藏
|  taronavigate  |  taro的路由跳转api代码段
|  tarorequest  |  Request接口请求代码段
|  tarocliboard  |  剪贴板操作api
|  tarosetstorage  |  设置key:data本地缓存
|  tarogetstorage  |  获取指定key的本地缓存
|  tarosetstoragesync  |  同步方式设置key:data本地缓存
|  tarogetstoragesync  |  同步方式获取指定key的本地缓存
|  taroremovestoragesync  |  同步方式删除指定key的本地缓存
|  taroremovestorage  |  异常方式删除指定key的本地缓存
|  taroshowtoast  |  taro showToast显示消息提示框
|  taroshowmodel  |  taro showModel显示模态对话框
|  taroshowloading  |  taro showLoading显示消息提示框 
|  tarogetsysteminfo  |  getSystemInfo获取系统信息代码段 
|  tarogetsysteminfosync  |  getSystemInfoSync同步获取系统信息代码段 
<br />

### jsx代码模板
> Javascript代码模板一样可以使用

|  缩写  |  模板  
|  ----  |  ----  
|  taropage  |  taro page模板函数形式
|  taropageclass  |  taro page模板class形式
|  tarocomponent  |  taro component模板
|  taropageconfig  |  taro page配置模板
|  tarousehook  |  taro 特有hooks
|  taroview  |  View组件代码段
|  tarotext  |  Text组件代码段
|  taroimage  |  Image组件代码段
|  taroscrollview  |  ScrollView组件代码段
|  taroswiper  |  Swiper组件代码段
|  tarobutton  |  Button组件代码段
|  tarocheckbox  |  Checkbox组件代码段
|  taroradio  |  Radio组件代码段
|  taroinput  |  Input组件代码段
|  tarotextarea  |  Textarea组件代码段
|  tarowebview  |  Webview组件代码段
|  tarocanvas  |  Canvas组件代码段
|  taroad  |  Ad组件代码段
<br />

### 全局代码段

|  缩写  |  模板  
|  ----  |  ----  
|  gbdoc  |  taro文挡地址
|  gbapi  |  Taro Api文挡地址