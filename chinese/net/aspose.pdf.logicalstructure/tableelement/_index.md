---
title: Class TableElement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.TableElement 类。表示逻辑结构中的表结构元素
type: docs
weight: 6780
url: /zh/net/aspose.pdf.logicalstructure/tableelement/
---
## TableElement class

表示逻辑结构中的表结构元素。

```csharp
public sealed class TableElement : BLSElement, IAdjustPosition
```

## Properties

| Name | Description |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | 获取或设置结构元素的实际文本。 |
| [Alignment](../../aspose.pdf.logicalstructure/tableelement/alignment/) { get; set; } | 获取或设置表的对齐方式。 |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | 获取或设置结构元素的替代文本。 |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | 获取 StructureAttributeCollection 对象。 |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tableelement/backgroundcolor/) { get; set; } | 获取或设置表的背景颜色。 |
| [Border](../../aspose.pdf.logicalstructure/tableelement/border/) { get; set; } | 获取或设置表的边框。 |
| [Broken](../../aspose.pdf.logicalstructure/tableelement/broken/) { get; set; } | 获取或设置表的垂直断裂； |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | 获取 Element 对象的子集合。 |
| [ColumnAdjustment](../../aspose.pdf.logicalstructure/tableelement/columnadjustment/) { get; set; } | 获取或设置表的列调整。 |
| [ColumnWidths](../../aspose.pdf.logicalstructure/tableelement/columnwidths/) { get; set; } | 获取表的列宽。 |
| [CornerStyle](../../aspose.pdf.logicalstructure/tableelement/cornerstyle/) { get; set; } | 获取或设置边框角的样式 |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | 获取 AttributeOwnerStandard 对象。 |
| [DefaultCellBorder](../../aspose.pdf.logicalstructure/tableelement/defaultcellborder/) { get; set; } | 获取默认单元格边框。 |
| [DefaultCellPadding](../../aspose.pdf.logicalstructure/tableelement/defaultcellpadding/) { get; set; } | 获取或设置默认单元格内边距。 |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tableelement/defaultcelltextstate/) { get; set; } | 获取或设置默认单元格文本状态。 |
| [DefaultColumnWidth](../../aspose.pdf.logicalstructure/tableelement/defaultcolumnwidth/) { get; set; } | 获取或设置默认列宽。 |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | 获取或设置结构元素的扩展文本。 |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | 获取结构元素的 ID。 |
| [IsBordersIncluded](../../aspose.pdf.logicalstructure/tableelement/isbordersincluded/) { get; set; } | 获取或设置列宽中是否包含边框。 |
| [IsBroken](../../aspose.pdf.logicalstructure/tableelement/isbroken/) { get; set; } | 获取或设置表是否断裂 - 将被截断到下一页。 |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | 获取或设置结构元素的语言。 |
| [Left](../../aspose.pdf.logicalstructure/tableelement/left/) { get; set; } | 获取或设置表的左坐标。 |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | 获取某些或所有子元素将被渲染的页面。 |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | 获取父元素。 |
| [RepeatingColumnsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingcolumnscount/) { get; set; } | 获取或设置表的最大列数。 |
| [RepeatingRowsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingrowscount/) { get; set; } | 获取在多个页面上重复的第一行数。 |
| [RepeatingRowsStyle](../../aspose.pdf.logicalstructure/tableelement/repeatingrowsstyle/) { get; set; } | 获取重复行的样式。 |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | 获取结构元素的类型。 |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | 获取或设置结构元素的标题。 |
| [Top](../../aspose.pdf.logicalstructure/tableelement/top/) { get; set; } | 获取或设置表的顶部坐标。 |

## Methods

| Name | Description |
| --- | --- |
| [AdjustPosition](../../aspose.pdf.logicalstructure/tableelement/adjustposition/)(PositionSettings) |  |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | 将 Element 附加到子集合。 |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | 更改当前结构元素的父元素 |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | 清除所有子元素。 |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | 清除结构元素的 ID。 |
| [CreateTBody](../../aspose.pdf.logicalstructure/tableelement/createtbody/)() | 创建 [`TableTHeadElement`](../tabletheadelement/) 并将其添加到当前表。 |
| [CreateTFoot](../../aspose.pdf.logicalstructure/tableelement/createtfoot/)() | 创建 [`TableTFootElement`](../tabletfootelement/) 并将其添加到当前表。 |
| [CreateTHead](../../aspose.pdf.logicalstructure/tableelement/createthead/)() | 创建 [`TableTHeadElement`](../tabletheadelement/) 并将其添加到当前表。 |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | 查找给定类型的元素 |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | 为结构元素生成 ID。 |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | 在指定索引处将 Element 插入到子集合中。 |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | 移除：从结构中移除一个元素，从父对象中移除对它的引用，从子对象中移除对它的引用，从文档中移除相应的对象。 |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | 从结构中移除一个元素，从父对象中移除对它的引用，从子对象中移除对它的引用，并从文档中移除相应的对象。将被移除对象的子对象插入到其前父对象的子对象集合中，从被移除对象的索引开始。 |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | 移除子元素。 |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | 为结构元素设置 ID。 |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | 为结构元素设置自定义标签。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | 将结构元素绑定到注释。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | 将结构元素绑定到工件。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | 将结构元素绑定到内容流 BDC 操作符。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | 将结构元素绑定到内容流 XForm。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | 将结构元素绑定到 XImage。 |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | 返回表示当前对象的字符串。 |

### See Also

* class [BLSElement](../blselement/)
* interface [IAdjustPosition](../../aspose.pdf.tagged/iadjustposition/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)