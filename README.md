# UGCFramework（Unity Game Client Framework）
unity-xlua客户端框架1.0版(UGUI+C#+protocol+xlua)</p>
<b>注：因UGCF-ILRuntime版更改过大，所以该版本暂未优化，建议使用UGCF-ILRuntime分支的版本，UGC-Xlua2.0版后续会补上</b></p>

这是一个基于C＃语言的unity客户端框架，少部分工具基于UGUI，大部分工具不限制UI类型</p>
代码热更新方面使用的是xlua热补丁技术</p>
通信采用socket+tcp方式，协议采用protocol buffer</p>

框架包括几个部分：</p>
  1、Bundle资源管理器（包括所有资源更新）</p>
  2、音频管理器</p>
  3、UI管理器</p>
  4、对象池管理器</p>
  5、第三方sdk管理器（第三方登录、分享、支付，复制，电池电量等）</p>
  6、提示窗口管理器</p>
  7、socket+ProtoBuf通信</p>
  8、组件式工具（动画、事件封装、定时器等）</p>
  9、实用性工具（图片处理、图片置灰、文件下载、定位、文件和字符串加密）</p>
  10、UGUI扩展组件(Tab、RadioButton等)</p>
  11、xlua热补丁机制</p>
