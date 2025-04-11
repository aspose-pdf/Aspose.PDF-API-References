---
title: Class ILSElement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.ILSElementクラス。論理構造におけるインラインレベルの構造要素の基底クラスを表します。
type: docs
weight: 6390
url: /ja/net/aspose.pdf.logicalstructure/ilselement/
---
## ILSElementクラス

論理構造におけるインラインレベルの構造要素の基底クラスを表します。

```csharp
public abstract class ILSElement : StructureElement
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | 構造要素の実際のテキストを取得または設定します。 |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | 構造要素の代替テキストを取得または設定します。 |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | StructureAttributeCollectionオブジェクトを取得します。 |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Elementオブジェクトの子コレクションを取得します。 |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | AttributeOwnerStandardオブジェクトを取得します。 |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | 構造要素の拡張テキストを取得または設定します。 |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | 構造要素のIDを取得します。 |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | 構造要素の言語を取得または設定します。 |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | 一部またはすべての子要素が描画されるページを取得します。 |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | 親要素を取得します。 |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | 構造要素のタイプを取得します。 |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | 構造要素のタイトルを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | 子のコレクションにElementを追加します。 |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | 現在の構造要素の親要素を変更します。 |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | すべての子をクリアします。 |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | 構造要素のIDをクリアします。 |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | 指定されたタイプの要素を見つけます。 |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | 構造要素のIDを生成します。 |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | 指定されたインデックスで子のコレクションにElementを挿入します。 |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | 構造から要素を削除し、親オブジェクトからの参照、子オブジェクトからの参照、およびドキュメントからの対応するオブジェクトを削除します。 |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | 構造から要素を削除し、親オブジェクトからの参照、子オブジェクトからの参照、およびドキュメントからの対応するオブジェクトを削除します。削除されたオブジェクトの子オブジェクトを、削除されたオブジェクトのインデックスから始まるその前の親の子オブジェクトコレクションに挿入します。 |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | 指定された位置の子を削除します。 |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | 構造要素のIDを設定します。 |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | 構造要素のカスタムタグを設定します。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | 構造要素をAnnotationにバインドします。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | 構造要素をArtifactにバインドします。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | 構造要素をコンテンツストリームBDCオペレーターにバインドします。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | 構造要素をコンテンツストリームXFormにバインドします。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | 構造要素をXImageにバインドします。 |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | 現在のオブジェクトを表す文字列を返します。 |

### 参照

* クラス [StructureElement](../structureelement/)
* 名前空間 [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* アセンブリ [Aspose.PDF](../../)