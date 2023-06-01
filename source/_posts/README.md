# 云呼叫中心

## 开发指南

- 习惯养成：每天上班时，必须 git pull 拉新，下班 git push 推送代码
- 技术选型：vue2.6 + element ui + vue-router + vuex + vuex-persistedstate + axios
- git 管理规范参考：https://alidocs.dingtalk.com/i/nodes/3KLw95QMzkb8gN9BxyO1JAjrymPeEN2q?doc_type=wiki_doc

## 框架设置

```
npm install
npm run serve
npm run build
```

## 框架实现功能

- axios 封装
- store 处理
- vuex 数据持久化
- lodash js 组件库
- uilts 便捷功能封装
- i18n 国际化封装
- vxe-table 按需引入,减小打包体积

## 页面功能备注

- 显示接口动态 msg 使用规则：
  > 当需要使用动态 msg 提示时，在请求封装 request.js 中有配置 a,b,c,d....，只需在 i18n 中对应的国际化字段中加入对应的{a}{b}{c}....
