基于 vue 2.0 + Vuex + VueRouter 全家桶实现方案来模拟网易云音乐WebApp项目
CSS预编译工具使用的是Sass, 音乐上下滚动加载用的是betterscore, 全面采用ES6风格代码。

解决了哪些问题
- 图片懒加载   vue-lazyload
- 前后端分离
  使用node.js  NeteaseCloudMusicAPI  proxy
  8080 + 3000
- fastclick   解决点击300ms延迟 在touchend后   
- 设计了store
  songs  index  song  singer  mode   favoriteList
  searchHistory   playHistory
- iconfont