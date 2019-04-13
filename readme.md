# css 命名规范 BEM

- WEUI
  微信UI规范，内嵌公众号，小程序，调起webview,为了让用户体验一致，让用户有认同感。
  mobile web app
  前端界面框架 weui.css
- 组件
  大部分的项目，70%都是通用组件构成的，组件，拿来就用。
  1. tabber
  .tabbar>a.item>(span>img+span.badge)+p
  词汇量 组件词汇tabbar、badge 一般词汇item
  良好的结构和语义化标签
  flex 1:1:1 父元素等分
  2. Block
     页面是由多个Block 构成的，跟其它的Block区分开来，tabbar
    Element__
     在区块中担负的职责，取唯一性的名字
     并不是简单的父子关系
       Element__label
       Element__icon
    Modifier
      状态的修改
      __item_on