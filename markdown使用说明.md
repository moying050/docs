---
title: markdown使用说明
tags: 说明
grammar_cjkRuby: true
---
[TOC]
# 前言
使用 Markdown可以：
> * 整理知识，学习笔记
> * 发布日记，杂文，所见所想
> * 撰写发布技术文稿（代码支持）

推荐两个markdown编辑器：
- [小书匠](http://markdown.xiaoshujiang.com/)
- [Cmd Markdown](https://www.zybuluo.com/cmd/)

# 什么是Markdown
Markdown使用简单的符号标记不同的标题，分割不同的段落，**粗体** 或者 *斜体* 某些文字，更棒的是，它还可以

## 1. 制作一份待办事宜
- [ ] 支持以 PDF 格式导出文稿
- [ ] 改进 Cmd 渲染算法，使用局部渲染技术提高渲染效率
- [x] 新增 Todo 列表功能
- [x] 修复 LaTex 公式渲染问题
- [x] 新增 LaTex 公式编号功能

## 2. 高亮一段代码
```python
@requires_authorization
class SomeClass:
    pass

if __name__ == '__main__':
    # A comment
    print 'hello world'
```

## 3. 绘制表格

| 项目        | 价格   |  数量  |
| --------   | -----:  | :----:  |
| 计算机     | \$1600 |   5     |
| 手机        |   \$12   |   12   |
| 管线        |    \$1    |  234  |

## 4. 使用链接
对于插入图片可以通过下述方式实现
```
![](图片网址)
```

对于使用网络链接可以通过如下方式
```
[网址说明](网址)
```

## 5. 


**Markdown 在流畅的书写和印刷级的阅读体验之间找到了平衡。** 目前它已经成为世界上最大的技术分享网站 GitHub 和 技术问答网站 StackOverFlow 的御用书写格式。

# 标题设置
1. 标题级别通过#来控制，多少个#代表多少级
2. 级别最深应该是6级，可能不同编辑器不一样

# list相关
list有三种方式：
1. 带序号的方式
    ```
    1. 第一
    2. 第二
    3. 第三
    ```
2. 不带序号的方式
    ```
    - 第一
    - 第二
    - 第三
    ```
3. 带完成标记

