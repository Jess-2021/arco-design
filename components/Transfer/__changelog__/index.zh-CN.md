## 2.21.0

2021-08-20

### 🆕 功能升级

- `simple` 属性支持传入对象 `{ retainSelectedItems: true }` 以在左侧面板保留被选中的项目。

## 2.19.0

2021-07-16

### 🆕 Feature

- `Transfer` 组件 `CustomListProps` 新增 `onItemRemove` 回调。
- `Transfer` 组件自定义头部渲染函数 `titleTexts` 新增 `checkbox` 参数。

## 2.18.0

2021-07-02

### 🆕 Feature

- `Transfer` 组件 `titleTexts` 允许传入函数以自定义标题栏渲染。

## 2.13.2

2021-04-01

### 🐛 Bugfix

- 修复 `Transfer` 组件结合分页表格混用时，每次选中项目都会使表格回到第一页的 bug。

## 2.11.0

2021-03-12

### 🆕 Feature

- `Transfer` 组件 `showFooter` 支持传入 `ReactNode` 自定义节点。

### 🐛 Bugfix

- 修复 `Transfer.Item` 的 key 可能重复的 bug。

