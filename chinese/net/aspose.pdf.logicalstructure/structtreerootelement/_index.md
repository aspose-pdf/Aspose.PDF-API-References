---
title: Class StructTreeRootElement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.StructTreeRootElement 类。表示逻辑结构中的 StructTreeRoot 对象
type: docs
weight: 6660
url: /zh/net/aspose.pdf.logicalstructure/structtreerootelement/
---
## StructTreeRootElement 类

表示逻辑结构中的 StructTreeRoot 对象。

```csharp
public sealed class StructTreeRootElement : Element
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | 获取 Element 对象的子集合。 |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | 获取父元素。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | 将 Element 添加到子集合。 |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | 清除所有子元素。 |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | 查找给定类型的元素 |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | 在指定索引处将 Element 插入到子集合。 |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | 移除指定位置的子元素。 |
| override [Tag](../../aspose.pdf.logicalstructure/structtreerootelement/tag/#tag_2)(Annotation) | 将结构元素绑定到注释。 |
| override [Tag](../../aspose.pdf.logicalstructure/structtreerootelement/tag/#tag)(Artifact) | 将结构元素绑定到工件。 |
| override [Tag](../../aspose.pdf.logicalstructure/structtreerootelement/tag/#tag_1)(BDC) | 将结构元素绑定到内容流 BDC 操作符。 |
| override [Tag](../../aspose.pdf.logicalstructure/structtreerootelement/tag/#tag_3)(XForm) | 将结构元素绑定到内容流 XForm。 |
| override [Tag](../../aspose.pdf.logicalstructure/structtreerootelement/tag/#tag_4)(XImage) | 将结构元素绑定到 XImage。 |
| override [ToString](../../aspose.pdf.logicalstructure/element/tostring/)() | 返回表示当前对象的字符串。 |

### 另见

* 类 [Element](../element/)
* 命名空间 [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* 程序集 [Aspose.PDF](../../)