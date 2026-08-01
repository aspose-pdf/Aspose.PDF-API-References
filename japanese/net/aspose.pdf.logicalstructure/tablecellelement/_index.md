---
title: "クラス TableCellElement"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.LogicalStructure.TableCellElement クラス。論理構造内のテーブルセル要素 TH と TD の基底クラスを表します"
type: docs
weight: 6900
url: /ja/net/aspose.pdf.logicalstructure/tablecellelement/
---
## TableCellElement class

論理構造内のテーブルセル要素 (TH と TD) の基底クラスを表します。

```csharp
public abstract class TableCellElement : TableChildElement, IAdjustPosition, ITextElement
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | 構造要素の実際のテキストを取得または設定します。 |
| [Alignment](../../aspose.pdf.logicalstructure/tablecellelement/alignment/) { get; set; } | セルの配置を取得または設定します。 |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | 構造要素の代替テキストを取得または設定します。 |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | StructureAttributeCollection オブジェクトを取得します。 |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tablecellelement/backgroundcolor/) { get; set; } | セルの背景色を取得または設定します。 |
| [Border](../../aspose.pdf.logicalstructure/tablecellelement/border/) { get; set; } | セルの境界線を取得または設定します。 |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Element オブジェクトの子コレクションを取得します。 |
| [ColSpan](../../aspose.pdf.logicalstructure/tablecellelement/colspan/) { get; set; } | 列のスパンを取得または設定します。 |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | AttributeOwnerStandard オブジェクトを取得します。 |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tablecellelement/defaultcelltextstate/) { get; set; } | デフォルトのセルテキスト状態を取得または設定します。 |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | 構造要素の拡張テキストを取得または設定します。 |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | 構造要素の ID を取得します。 |
| [IsNoBorder](../../aspose.pdf.logicalstructure/tablecellelement/isnoborder/) { get; set; } | セルに境界線があるかどうかを取得または設定します。 |
| [IsWordWrapped](../../aspose.pdf.logicalstructure/tablecellelement/iswordwrapped/) { get; set; } | セルのテキストの折り返しを取得または設定します。 |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | 構造要素の言語を取得または設定します。 |
| [Margin](../../aspose.pdf.logicalstructure/tablecellelement/margin/) { get; set; } | 余白を取得または設定します。 |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | 一部またはすべての子要素が描画されるページを取得します。 |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | 親要素を取得します。 |
| [RowSpan](../../aspose.pdf.logicalstructure/tablecellelement/rowspan/) { get; set; } | 行のスパンを取得または設定します。 |
| [StructureTextState](../../aspose.pdf.logicalstructure/tablecellelement/structuretextstate/) { get; } | 現在の要素の StructureTextState オブジェクトを取得します。 |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | 構造要素のタイプを取得します。 |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | 構造要素のタイトルを取得または設定します。 |
| [VerticalAlignment](../../aspose.pdf.logicalstructure/tablecellelement/verticalalignment/) { get; set; } | 垂直方向の配置を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AdjustPosition](../../aspose.pdf.logicalstructure/tablecellelement/adjustposition/)(PositionSettings) |  |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | 子コレクションに Element を追加します。 |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | 現在の構造要素の親要素を変更します。 |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | すべての子要素をクリアします。 |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | 構造要素の ID をクリアします。 |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | 指定されたタイプの要素を検索します |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | 構造要素の ID を生成します。 |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | 指定されたインデックスで子コレクションに要素を挿入します。 |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | 構造から要素を削除し、親オブジェクトからの参照、子オブジェクトからの参照、およびドキュメントからの対応するオブジェクトを削除します。 |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | 構造から要素を削除し、親オブジェクトからの参照、子オブジェクトからの参照、およびドキュメントからの対応するオブジェクトを削除します。削除されたオブジェクトの子オブジェクトを、削除されたオブジェクトのインデックスから元の親の子オブジェクトコレクションに挿入します。 |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | 指定位置の子を削除します。 |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | 構造要素の ID を設定します。 |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | 構造要素のカスタムタグを設定します。 |
| [SetText](../../aspose.pdf.logicalstructure/tablecellelement/settext/)(string) |  |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | 構造要素を Annotation にバインドします。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | 構造要素を Artifact にバインドします。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | 構造要素をコンテンツストリームの BDC 演算子にバインドします。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | 構造要素をコンテンツストリームの XForm にバインドします。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | 構造要素を XImage にバインドします。 |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | 現在のオブジェクトを表す文字列を返します。 |

### 関連項目

* class [TableChildElement](../tablechildelement/)
* interface [IAdjustPosition](../../aspose.pdf.tagged/iadjustposition/)
* interface [ITextElement](../itextelement/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)


