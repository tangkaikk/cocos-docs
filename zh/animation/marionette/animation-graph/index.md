
# 动画系统

在 V3.4 中，Creator 引入了一个全新的动画系统，实现了由状态机控制的动画流程。

> V3.4 之前使用了以动画组件、动画状态为核心的动画系统。为了区分两种动画系统，有时称此动画系统为木偶（Marionette）动画系统，称“旧的”动画系统为旧式动画系统。

## 动画图资源

动画图资源通过状态机描述动画的流程。

### 创建

动画图资源有以下几种创建入口：

- 在资源创建菜单中，选择 “动画图”。

### 编辑

动画图在动画图编辑器中编辑。

### 概念

见 [动画图基础](./basics.md)。

## 使用动画控制器

动画图需要放置到动画控制器组件上运行。注意，动画控制器组件不能与动画组件或者骨骼动画组件共存。添加后需要移除。
