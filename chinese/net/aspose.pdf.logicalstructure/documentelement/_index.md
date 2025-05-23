---
title: Class DocumentElement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.DocumentElement 类。表示逻辑结构中的文档结构元素
type: docs
weight: 6310
url: /zh/net/aspose.pdf.logicalstructure/documentelement/
---
## DocumentElement 类

表示逻辑结构中的文档结构元素。

```csharp
public sealed class DocumentElement : GroupingElement
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | 获取或设置结构元素的实际文本。 |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | 获取或设置结构元素的替代文本。 |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | 获取 StructureAttributeCollection 对象。 |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | 获取 Element 对象的子集合。 |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | 获取 AttributeOwnerStandard 对象。 |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | 获取或设置结构元素的扩展文本。 |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | 获取结构元素的 ID。 |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | 获取或设置结构元素的语言。 |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | 获取某些或所有子元素将被呈现的页面。 |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | 获取父元素。 |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | 获取结构元素的类型。 |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | 获取或设置结构元素的标题。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | 将 Element 添加到子集合中。 |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | 更改当前结构元素的父元素 |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | 清除所有子元素。 |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | 清除结构元素的 ID。 |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | 查找给定类型的元素 |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | 为结构元素生成 ID。 |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | 在指定索引处将 Element 插入到子集合中。 |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | 从结构中移除：元素、父对象中的引用、子对象中的引用、文档中的相应对象。 |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | 从结构中移除一个元素、父对象中的引用、子对象中的引用，以及文档中的相应对象。将被移除对象的子对象插入到其前父对象的子对象集合中，从被移除对象的索引开始。 |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | 移除指定位置的子元素。 |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | 设置结构元素的 ID。 |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | 设置结构元素的自定义标签。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | 将结构元素绑定到注释。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | 将结构元素绑定到工件。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | 将结构元素绑定到内容流 BDC 操作符。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | 将结构元素绑定到内容流 XForm。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | 将结构元素绑定到 XImage。 |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | 返回一个表示当前对象的字符串。 |

### 另见

* 类 [GroupingElement](../groupingelement/)
* 命名空间 [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* 程序集 [Aspose.PDF](../../)