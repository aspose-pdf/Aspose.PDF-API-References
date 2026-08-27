---
title: "类 TableTRElement"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.LogicalStructure.TableTRElement 类。表示表格逻辑结构中的 TR 结构元素"
type: docs
weight: 6990
url: /zh/net/aspose.pdf.logicalstructure/tabletrelement/
---
## TableTRElement class

表示表格逻辑结构中的 TR 结构元素。

```csharp
public sealed class TableTRElement : TableChildElement
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | 获取或设置结构元素的实际文本。 |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | 获取或设置结构元素的替代文本。 |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | 获取 StructureAttributeCollection 对象。 |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tabletrelement/backgroundcolor/) { get; set; } | 获取或设置行的背景颜色。 |
| [Border](../../aspose.pdf.logicalstructure/tabletrelement/border/) { get; set; } | 获取或设置行的边框。 |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | 获取 Element 对象的子集合。 |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | 获取 AttributeOwnerStandard 对象。 |
| [DefaultCellBorder](../../aspose.pdf.logicalstructure/tabletrelement/defaultcellborder/) { get; set; } | 获取默认单元格边框。 |
| [DefaultCellPadding](../../aspose.pdf.logicalstructure/tabletrelement/defaultcellpadding/) { get; set; } | 获取或设置行单元格的默认边距。 |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tabletrelement/defaultcelltextstate/) { get; set; } | 获取或设置行单元格的默认文本状态 |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | 获取或设置结构元素的展开文本。 |
| [FixedRowHeight](../../aspose.pdf.logicalstructure/tabletrelement/fixedrowheight/) { get; set; } | 获取固定行高 - 行可能具有固定高度。 |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | 获取结构元素的 ID。 |
| [IsInNewPage](../../aspose.pdf.logicalstructure/tabletrelement/isinnewpage/) { get; set; } | 获取固定行是否在新页面 - 具有此属性的页面应打印到下一页，默认值为 false。 |
| [IsRowBroken](../../aspose.pdf.logicalstructure/tabletrelement/isrowbroken/) { get; set; } | 获取行是否可以在两页之间断开。 |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | 获取或设置结构元素的语言。 |
| [MinRowHeight](../../aspose.pdf.logicalstructure/tabletrelement/minrowheight/) { get; set; } | 获取行的高度。 |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | 获取将渲染部分或全部子元素的页面。 |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | 获取父元素。 |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | 获取结构元素的类型。 |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | 获取或设置结构元素的标题。 |
| [VerticalAlignment](../../aspose.pdf.logicalstructure/tabletrelement/verticalalignment/) { get; set; } | 获取或设置垂直对齐方式。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | 将 Element 添加到子集合中。 |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | 更改当前结构元素的父元素 |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | 清除所有子项。 |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | 清除结构元素的 ID。 |
| [CreateTD](../../aspose.pdf.logicalstructure/tabletrelement/createtd/)() | 创建 [`TableTHElement`](../tablethelement/) 并将其添加到当前表中。 |
| [CreateTH](../../aspose.pdf.logicalstructure/tabletrelement/createth/)() | 创建 [`TableTHElement`](../tablethelement/) 并将其添加到当前表中。 |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | 查找给定类型的元素 |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | 为结构元素生成 ID。 |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | 在指定索引处将元素插入子集合中。 |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | 移除：结构中的元素、父对象对它的引用、子对象对它的引用以及相应的 Document 对象。 |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | 从结构中移除元素、父对象对它的引用、子对象对它的引用以及相应的 Document 对象。将被移除对象的子对象插入到其原父对象的子集合中，起始索引为被移除对象的索引。 |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | 移除指定位置的子对象。 |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | 设置结构元素的 ID。 |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | 为结构元素设置自定义标签。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | 将结构元素绑定到 Annotation。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | 将结构元素绑定到 Artifact。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | 将结构元素绑定到内容流 BDC 操作符。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | 将结构元素绑定到内容流 XForm。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | 将结构元素绑定到 XImage。 |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | 返回表示当前对象的字符串。 |

### 另请参见

* class [TableChildElement](../tablechildelement/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)


