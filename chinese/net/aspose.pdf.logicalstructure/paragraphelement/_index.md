---
title: Class ParagraphElement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.ParagraphElement 类。表示逻辑结构中的段落结构元素
type: docs
weight: 6540
url: /zh/net/aspose.pdf.logicalstructure/paragraphelement/
---
## ParagraphElement 类

表示逻辑结构中的段落结构元素。

```csharp
public sealed class ParagraphElement : BLSTextElement
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
| [StructureTextState](../../aspose.pdf.logicalstructure/blstextelement/structuretextstate/) { get; } | 获取当前元素的 StructureTextState 对象。 |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | 获取结构元素的类型。 |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | 获取或设置结构元素的标题。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AdjustPosition](../../aspose.pdf.logicalstructure/blstextelement/adjustposition/)(PositionSettings) |  |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | 将 Element 附加到子集合。 |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | 更改当前结构元素的父元素 |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | 清除所有子元素。 |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | 清除结构元素的 ID。 |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | 查找给定类型的元素 |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | 为结构元素生成 ID。 |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | 在指定索引处将 Element 插入到子集合中。 |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | 移除：从结构中移除一个元素，从父对象中移除对它的引用，从子对象中移除对它的引用，从文档中移除相应的对象。 |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | 从结构中移除一个元素，从父对象中移除对它的引用，从子对象中移除对它的引用，并从文档中移除相应的对象。将被移除对象的子对象插入到其前父子对象集合中，从被移除对象的索引开始。 |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | 移除子元素。 |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | 设置结构元素的 ID。 |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | 为结构元素设置自定义标签。 |
| [SetText](../../aspose.pdf.logicalstructure/blstextelement/settext/)(string) |  |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | 将结构元素绑定到注释。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | 将结构元素绑定到工件。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | 将结构元素绑定到内容流 BDC 操作符。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | 将结构元素绑定到内容流 XForm。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | 将结构元素绑定到 XImage。 |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | 返回表示当前对象的字符串。 |

### 另请参阅

* 类 [BLSTextElement](../blstextelement/)
* 命名空间 [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* 程序集 [Aspose.PDF](../../)