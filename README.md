# json-to-go
将json生成go的数据结构。generating data structure of go languages with JSON.


## 本地开发

> 强烈建议使用 `pnpm` !!!

- 安装 `pnpm install`

- 调试 `pnpm dev`

- 构建 `pnpm build`

- 部署到github `pnpm page`

## 自定义tag

- 格式

> tag名字:命名方式:是否添加omitempty

- 命名方式

0. 原样返回
1. abcDef 小驼峰 - 默认
2. AbcDef 大驼峰
3. abc_def 下划线
4. Abcdef 
5. abcdef

- 例子

`json`

`form`

`json:1:true`

`json:3:false,form:2:true,query:1:false`


## 参考

- [UI框架](https://primefaces.org/primevue/showcase/#/setup)
- [ace](https://ace.c9.io/#nav=api)
- [全局事件总线](https://vue3.chengpeiquan.com/communication.html#eventbus-new)