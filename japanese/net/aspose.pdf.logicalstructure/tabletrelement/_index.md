---
title: Class TableTRElement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.TableTRElement クラス。テーブルの論理構造における TR 構造要素を表します。
type: docs
weight: 6850
url: /ja/net/aspose.pdf.logicalstructure/tabletrelement/
---
## TableTRElement クラス

テーブルの論理構造における TR 構造要素を表します。

```csharp
public sealed class TableTRElement : TableChildElement
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | 構造要素の実際のテキストを取得または設定します。 |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | 構造要素の代替テキストを取得または設定します。 |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | StructureAttributeCollection オブジェクトを取得します。 |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tabletrelement/backgroundcolor/) { get; set; } | 行の背景色を取得または設定します。 |
| [Border](../../aspose.pdf.logicalstructure/tabletrelement/border/) { get; set; } | 行の境界線を取得または設定します。 |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Element オブジェクトの子コレクションを取得します。 |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | AttributeOwnerStandard オブジェクトを取得します。 |
| [DefaultCellBorder](../../aspose.pdf.logicalstructure/tabletrelement/defaultcellborder/) { get; set; } | デフォルトのセル境界線を取得します。 |
| [DefaultCellPadding](../../aspose.pdf.logicalstructure/tabletrelement/defaultcellpadding/) { get; set; } | 行セルのデフォルトのマージンを取得または設定します。 |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tabletrelement/defaultcelltextstate/) { get; set; } | 行セルのデフォルトのテキスト状態を取得または設定します。 |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | 構造要素の拡張テキストを取得または設定します。 |
| [FixedRowHeight](../../aspose.pdf.logicalstructure/tabletrelement/fixedrowheight/) { get; set; } | 固定行の高さを取得または設定します - 行は固定の高さを持つことができます。 |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | 構造要素の ID を取得します。 |
| [IsInNewPage](../../aspose.pdf.logicalstructure/tabletrelement/isinnewpage/) { get; set; } | 固定行が新しいページにあるかどうかを取得または設定します - このプロパティを持つページは次のページに印刷されるべきです。デフォルトは false です。 |
| [IsRowBroken](../../aspose.pdf.logicalstructure/tabletrelement/isrowbroken/) { get; set; } | 行が2ページの間で分割できるかどうかを取得または設定します。 |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | 構造要素の言語を取得または設定します。 |
| [MinRowHeight](../../aspose.pdf.logicalstructure/tabletrelement/minrowheight/) { get; set; } | 行の高さを取得または設定します。 |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | 一部またはすべての子要素が描画されるページを取得します。 |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | 親要素を取得します。 |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | 構造要素のタイプを取得します。 |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | 構造要素のタイトルを取得または設定します。 |
| [VerticalAlignment](../../aspose.pdf.logicalstructure/tabletrelement/verticalalignment/) { get; set; } | 垂直方向の配置を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | 子のコレクションに Element を追加します。 |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | 現在の構造要素の親要素を変更します。 |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | すべての子をクリアします。 |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | 構造要素の ID をクリアします。 |
| [CreateTD](../../aspose.pdf.logicalstructure/tabletrelement/createtd/)() | [`TableTHElement`](../tablethelement/) を作成し、現在のテーブルに追加します。 |
| [CreateTH](../../aspose.pdf.logicalstructure/tabletrelement/createth/)() | [`TableTHElement`](../tablethelement/) を作成し、現在のテーブルに追加します。 |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | 指定されたタイプの要素を見つけます。 |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | 構造要素の ID を生成します。 |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | 指定されたインデックスで子のコレクションに Element を挿入します。 |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | 構造から要素を削除し、親オブジェクトからの参照、子オブジェクトからの参照、およびドキュメントからの対応するオブジェクトを削除します。 |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | 構造から要素を削除し、親オブジェクトからの参照、子オブジェクトからの参照、およびドキュメントからの対応するオブジェクトを削除します。削除されたオブジェクトの子オブジェクトを、削除されたオブジェクトのインデックスから始めてその前の親の子オブジェクトコレクションに挿入します。 |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | 指定された位置の子を削除します。 |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | 構造要素の ID を設定します。 |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | 構造要素のカスタムタグを設定します。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | 構造要素を Annotation にバインドします。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | 構造要素を Artifact にバインドします。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | 構造要素をコンテンツストリーム BDC 演算子にバインドします。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | 構造要素をコンテンツストリーム XForm にバインドします。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | 構造要素を XImage にバインドします。 |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | 現在のオブジェクトを表す文字列を返します。 |

### 参照

* クラス [TableChildElement](../tablechildelement/)
* 名前空間 [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* アセンブリ [Aspose.PDF](../../)