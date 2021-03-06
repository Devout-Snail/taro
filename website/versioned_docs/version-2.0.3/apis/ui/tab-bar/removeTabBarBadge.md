---
title: Taro.removeTabBarBadge(option)
sidebar_label: removeTabBarBadge
id: version-2.0.3-removeTabBarBadge
original_id: removeTabBarBadge
---

移除 tabBar 某一项右上角的文本

> [参考文档](https://developers.weixin.qq.com/miniprogram/dev/api/ui/tab-bar/wx.removeTabBarBadge.html)

## 类型

```tsx
(option: Option) => Promise<CallbackResult>
```

## 参数

### Option

| 参数 | 类型 | 必填 | 说明 |
| --- | --- | :---: | --- |
| index | `number` | 是 | tabBar 的哪一项，从左边算起 |
| complete | `(res: CallbackResult) => void` | 否 | 接口调用结束的回调函数（调用成功、失败都会执行） |
| fail | `(res: CallbackResult) => void` | 否 | 接口调用失败的回调函数 |
| success | `(res: CallbackResult) => void` | 否 | 接口调用成功的回调函数 |

## API 支持度

| API | 微信小程序 | H5 | React Native |
| :---: | :---: | :---: | :---: |
| Taro.removeTabBarBadge | ✔️ | ✔️ |  |
