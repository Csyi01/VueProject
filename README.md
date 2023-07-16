# VueProject
## Project setup

```
npm install
```

### Compiles and hot-reloads for development

```
npm run serve
```
### Login account and password（The login account and password are consistent）
```
administrators：
admin

Ordinary users：
staff
```
### Main technologies
```
Vue2+Vue-cli+Vue-router+Element UI+ECharts+less+Vuex+axious二次封装+mock
```
### Technical Description
```
1.使用Vue-cli搭建整体后台管理项目，采用Element UI的按需引入和模块化思想实现后台首页，员工管理和其他页面等组件布局。封装ECharts组件，实现商品可视化图表的信息展示。
2.使用Vue-router实现后台管理项目内不同页面的跳转，并展示相应的页面内容。
3.使用Vuex的集中式存储管理对页面的数据进行管理，实现跨组件间的数据通信。如项目中首页头部面包屑，标签栏和左侧菜单栏数据的共享。结合Vuex中的辅助函数，如mapState,mapMutations帮助Vuex的开发。
4.在页面异步请求数据的时候使用axious的二次封装。借助mock拦截Ajax请求，对后端的数据进行模拟。
5.使用tooken和cookie缓存，路由守卫，动态路由对系统的用户权限和菜单权限进行设置。
```
