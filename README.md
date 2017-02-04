# little-program-demo
小程序的demo
### 关于微信的小程序的几点注意
- 数据不是双向绑定的，不像Vue.js等框架，在绑定input标签之后，输入数值之后，在数据层进行访问，获取的是原始值。this.setData：是把数据层的数据下发到渲染层，this.data.param 是直接修改数据层的数据。
