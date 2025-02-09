---
title: TagInput 标签输入框
description: 定义：用于输入文本标签。
isComponent: true
spline: data
---

### 基础标签输入框

使用 `overTagsDisplayType` 控制标签超出时的呈现方式：横向滚动显示和换行显示，默认为横向滚动。

{{ base }}


### 有数量限制的标签输入框

使用 `max` 控制最大标签数量。

{{ max }}

### 可折叠过多标签的标签输入框

- `mincollapsedNum` 用于控制超出这个数量的标签折叠省略显示。
- `collapsedItems` 用于自定义折叠标签呈现方式。

{{ collapsed }}

### 可自定义标签的标签输入框

- `tag` 用于定义单个标签的内容
- `valueDispaly` 用于完全自定义全量标签内容

{{ custom-tag }}


### 不同状态的标签输入框

标签输入框状态可分为：正常、只读、禁用、成功、告警、错误等，其中 成功、告警、错误 等状态一般用于表单验证。此特性继承至 Input 输入框组件。

{{ status }}

### 不同主题的标签输入框

使用 `tagProps` 控制标签的所有属性，如：颜色设置。

{{ theme }}
