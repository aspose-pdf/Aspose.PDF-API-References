---
title: Class StructTreeRootElement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.StructTreeRootElement クラス。論理構造における StructTreeRoot オブジェクトを表します。
type: docs
weight: 6660
url: /ja/net/aspose.pdf.logicalstructure/structtreerootelement/
---
## StructTreeRootElement クラス

論理構造における StructTreeRoot オブジェクトを表します。

```csharp
public sealed class StructTreeRootElement : Element
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Element オブジェクトの子コレクションを取得します。 |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | 親要素を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Element を子コレクションに追加します。 |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | すべての子をクリアします。 |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | 指定された型の要素を見つけます。 |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | 指定されたインデックスで子コレクションに Element を挿入します。 |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | 指定された位置の子を削除します。 |
| override [Tag](../../aspose.pdf.logicalstructure/structtreerootelement/tag/#tag_2)(Annotation) | 構造要素を Annotation にバインドします。 |
| override [Tag](../../aspose.pdf.logicalstructure/structtreerootelement/tag/#tag)(Artifact) | 構造要素を Artifact にバインドします。 |
| override [Tag](../../aspose.pdf.logicalstructure/structtreerootelement/tag/#tag_1)(BDC) | 構造要素をコンテンツストリーム BDC 演算子にバインドします。 |
| override [Tag](../../aspose.pdf.logicalstructure/structtreerootelement/tag/#tag_3)(XForm) | 構造要素をコンテンツストリーム XForm にバインドします。 |
| override [Tag](../../aspose.pdf.logicalstructure/structtreerootelement/tag/#tag_4)(XImage) | 構造要素を XImage にバインドします。 |
| override [ToString](../../aspose.pdf.logicalstructure/element/tostring/)() | 現在のオブジェクトを表す文字列を返します。 |

### 参照

* クラス [Element](../element/)
* 名前空間 [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* アセンブリ [Aspose.PDF](../../)