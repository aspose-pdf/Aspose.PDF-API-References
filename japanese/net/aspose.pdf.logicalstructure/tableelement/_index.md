---
title: "クラス TableElement"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.LogicalStructure.TableElement クラス。論理構造における Table 構造要素を表します。"
type: docs
weight: 6920
url: /ja/net/aspose.pdf.logicalstructure/tableelement/
---
## TableElement class

論理構造内のテーブル構造要素を表します。

```csharp
public sealed class TableElement : BLSElement, IAdjustPosition
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | 構造要素の実際のテキストを取得または設定します。 |
| [Alignment](../../aspose.pdf.logicalstructure/tableelement/alignment/) { get; set; } | テーブルの配置を取得または設定します。 |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | 構造要素の代替テキストを取得または設定します。 |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | StructureAttributeCollection オブジェクトを取得します。 |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tableelement/backgroundcolor/) { get; set; } | テーブルの背景色を取得または設定します。 |
| [Border](../../aspose.pdf.logicalstructure/tableelement/border/) { get; set; } | テーブルの罫線を取得または設定します。 |
| [Broken](../../aspose.pdf.logicalstructure/tableelement/broken/) { get; set; } | テーブルの垂直分割を取得または設定します; |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Element オブジェクトの子コレクションを取得します。 |
| [ColumnAdjustment](../../aspose.pdf.logicalstructure/tableelement/columnadjustment/) { get; set; } | テーブルの列調整を取得または設定します。 |
| [ColumnWidths](../../aspose.pdf.logicalstructure/tableelement/columnwidths/) { get; set; } | テーブルの列幅を取得します。 |
| [CornerStyle](../../aspose.pdf.logicalstructure/tableelement/cornerstyle/) { get; set; } | 罫線の角のスタイルを取得または設定します |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | AttributeOwnerStandard オブジェクトを取得します。 |
| [DefaultCellBorder](../../aspose.pdf.logicalstructure/tableelement/defaultcellborder/) { get; set; } | デフォルトのセル罫線を取得します。 |
| [DefaultCellPadding](../../aspose.pdf.logicalstructure/tableelement/defaultcellpadding/) { get; set; } | デフォルトのセル余白を取得または設定します。 |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tableelement/defaultcelltextstate/) { get; set; } | デフォルトのセルテキスト状態を取得または設定します。 |
| [DefaultColumnWidth](../../aspose.pdf.logicalstructure/tableelement/defaultcolumnwidth/) { get; set; } | デフォルトの列幅を取得または設定します。 |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | 構造要素の拡張テキストを取得または設定します。 |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | 構造要素の ID を取得します。 |
| [IsBordersIncluded](../../aspose.pdf.logicalstructure/tableelement/isbordersincluded/) { get; set; } | 列幅に含まれる罫線を取得または設定します。 |
| [IsBroken](../../aspose.pdf.logicalstructure/tableelement/isbroken/) { get; set; } | テーブルが分割されるかどうかを取得または設定します - 次のページで切り捨てられます。 |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | 構造要素の言語を取得または設定します。 |
| [Left](../../aspose.pdf.logicalstructure/tableelement/left/) { get; set; } | テーブルの左座標を取得または設定します。 |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | 一部またはすべての子要素が描画されるページを取得します。 |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | 親要素を取得します。 |
| [RepeatingColumnsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingcolumnscount/) { get; set; } | テーブルの最大列数を取得または設定します。 |
| [RepeatingRowsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingrowscount/) { get; set; } | 複数ページにわたって繰り返される最初の行数を取得します。 |
| [RepeatingRowsStyle](../../aspose.pdf.logicalstructure/tableelement/repeatingrowsstyle/) { get; set; } | 繰り返し行のスタイルを取得します。 |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | 構造要素のタイプを取得します。 |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | 構造要素のタイトルを取得または設定します。 |
| [Top](../../aspose.pdf.logicalstructure/tableelement/top/) { get; set; } | テーブルの上座標を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AdjustPosition](../../aspose.pdf.logicalstructure/tableelement/adjustposition/)(PositionSettings) |  |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | 子コレクションに Element を追加します。 |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | 現在の構造要素の親要素を変更します。 |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | すべての子要素をクリアします。 |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | 構造要素の ID をクリアします。 |
| [CreateTBody](../../aspose.pdf.logicalstructure/tableelement/createtbody/)() | [`TableTHeadElement`](../tabletheadelement/) を作成し、現在のテーブルに追加します。 |
| [CreateTFoot](../../aspose.pdf.logicalstructure/tableelement/createtfoot/)() | [`TableTFootElement`](../tabletfootelement/) を作成し、現在のテーブルに追加します。 |
| [CreateTHead](../../aspose.pdf.logicalstructure/tableelement/createthead/)() | [`TableTHeadElement`](../tabletheadelement/) を作成し、現在のテーブルに追加します。 |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | 指定されたタイプの要素を検索します |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | 構造要素の ID を生成します。 |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | 指定されたインデックスで子コレクションに要素を挿入します。 |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | 構造から要素を削除し、親オブジェクトからの参照、子オブジェクトからの参照、およびドキュメントからの対応するオブジェクトを削除します。 |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | 構造から要素を削除し、親オブジェクトからの参照、子オブジェクトからの参照、およびドキュメントからの対応するオブジェクトを削除します。削除されたオブジェクトの子オブジェクトを、削除されたオブジェクトのインデックスから元の親の子オブジェクトコレクションに挿入します。 |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | 指定位置の子を削除します。 |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | 構造要素の ID を設定します。 |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | 構造要素のカスタムタグを設定します。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | 構造要素を Annotation にバインドします。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | 構造要素を Artifact にバインドします。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | 構造要素をコンテンツストリームの BDC 演算子にバインドします。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | 構造要素をコンテンツストリームの XForm にバインドします。 |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | 構造要素を XImage にバインドします。 |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | 現在のオブジェクトを表す文字列を返します。 |

### 関連項目

* class [BLSElement](../blselement/)
* interface [IAdjustPosition](../../aspose.pdf.tagged/iadjustposition/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)


