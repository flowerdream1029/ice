---
title: 自定义模板
order: 10
category: ICE Design Pro
---

# 自定义模板

在 Iceworks 2.2.0 之前的版本，可以通过 `新建页面` 时选择默认提供的 4 套布局去替换已有项目的布局，也可以通过布局列表的`自定义布局`功能进行自定义，然后添加到项目。

![iceworks](https://img.alicdn.com/tfs/TB1ecZexQyWBuNjy0FpXXassXXa-1909-1368.png)

然而，这些都是基于已经生成好的项目添加新的布局。那有没有一种可能，完全从零开始去自定义一个模板，答案是有的，你可以先从自定义布局开始初始化一个项目，甚至是自定义布局之后，在自定义选择 Router，Eslint，Redux，Mbox 等等，这都是有可能的。我们还是脚踏实地，先从第一步开始，来了解下 Iceworks 全新的自定义布局功能，如何从自定义布局开始初始化一个模板。

![](https://img.alicdn.com/tfs/TB17Virx_tYBeNjy1XdXXXXyVXa-862-572.gif)

## 自定义创建流程

在 `模板` 界面选择 `自定义模板`，点击新建弹窗如下，左边是属性配置面板，右边是配置的实时效果图，目前自定义主要包含以下四部分配置

- 基础配置
- 导航配置
- 侧边栏配置
- 页脚配置

#### 基础配置

基础配置主要包含`布局容器配置`、`主题配置`、`定制皮肤`三部分，其中：

- 布局容器配置有全屏和固宽两个选项，全屏即 100% 宽度的布局，固宽默认是 1200px
- 主题配置有深色和浅色两个选项，对应的是 Layout 部分的主题配置
- 定制皮肤主要是指配置基础组件的样式，可以选择主色和辅色，详细可以查看[修改主题配色
  ](https://alibaba.github.io/ice/docs/advanced/custom-theme)

![基础配置](https://img.alicdn.com/tfs/TB10iEqxKuSBuNjy1XcXXcYjFXa-1909-1368.png)

#### 导航配置

导航配置主要包含 `启用`、`定位`、`是否通栏` 三部分。只有在启动的前提下才能配置对应的导航属性。在某些情况下，可能不需要导航，只要不勾选启用，则默认不会生成导航部分。

![导航配置](https://img.alicdn.com/tfs/TB1YhXXx9BYBeNjy0FeXXbnmFXa-1909-1368.png)

#### 侧边栏配置

侧边栏配置主要包含 `启用`、`折叠`、`定位` 三部分。只有在启动的前提下才能配置对应的侧边栏属性。在某些情况下，可能不需要导航，只要不勾选启用，则默认不会生成导航部分。折叠则是指默认生成的布局侧边栏是否折叠。

![侧边栏配置](https://img.alicdn.com/tfs/TB1DOSnx_tYBeNjy1XdXXXXyVXa-1908-1368.png)

#### 页脚配置

页脚配置与导航配置一样，主要包含 `启用`、`定位`、`是否通栏` 三部分。

![页脚配置](https://img.alicdn.com/tfs/TB1lHVnx21TBuNjy0FjXXajyXXa-1909-1368.png)

#### 创建项目

配置完成后点击保存，可以看到刚刚配置的模板列表，接下来，你可以基于该模板初始化创建项目。

![创建项目](https://img.alicdn.com/tfs/TB1yVfrxMmTBuNjy1XbXXaMrVXa-1909-1368.png)
