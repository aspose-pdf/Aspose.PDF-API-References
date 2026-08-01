---
title: "クラス TableAbsorber"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Text.TableAbsorber クラス。テーブル要素の吸収オブジェクトを表します。検索を実行し、TableList コレクションを介して検索結果へのアクセスを提供します"
type: docs
weight: 10970
url: /ja/net/aspose.pdf.text/tableabsorber/
---
## TableAbsorber class

テーブル要素の吸収オブジェクトを表します。検索を実行し、[`TableList`](./tablelist/) コレクションを介して検索結果へのアクセスを提供します。

```csharp
public class TableAbsorber
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TableAbsorber](tableabsorber/#constructor)() | `TableAbsorber` の新しいインスタンスを初期化します。 |
| [TableAbsorber](tableabsorber/#constructor_1)(TextSearchOptions) | `TableAbsorber` の新しいインスタンスをテキスト検索オプションと共に初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| virtual [TableList](../../aspose.pdf.text/tableabsorber/tablelist/) { get; } | 見つかったテーブルを含む読み取り専用 IList を返します |
| virtual [TextSearchOptions](../../aspose.pdf.text/tableabsorber/textsearchoptions/) { get; set; } | テキスト検索オプションを取得または設定します。 |
| [UseFlowEngine](../../aspose.pdf.text/tableabsorber/useflowengine/) { get; set; } | * さまざまなシナリオで優れた代替テーブル認識エンジンを有効にし、枠線のないテーブルを認識できるようにします。テーブルの編集やテキストスタイルの取得はまだサポートされていません。デフォルト値は false です; |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Remove](../../aspose.pdf.text/tableabsorber/remove/)(AbsorbedTable) | [`AbsorbedTable`](../absorbedtable/) をページから削除します。 |
| [Replace](../../aspose.pdf.text/tableabsorber/replace/)(Page, AbsorbedTable, Table) | ページ上で [`AbsorbedTable`](../absorbedtable/) を [`Table`](../../aspose.pdf/table/) に置き換えます。 |
| [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit)(Document) | 指定されたドキュメントからテーブルを抽出します。 |
| virtual [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit_1)(Page) | 指定されたページ上のテーブルを抽出します |

## 例

この例では、最初の PDF ドキュメントページでテーブルを見つけ、テーブルセル内のテキストを置換する方法を示しています。

```csharp
// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

// テーブルを見つけるために TableAbsorber オブジェクトを作成します
TableAbsorber absorber = new TableAbsorber();

// 吸収オブジェクトで最初のページを訪問します
absorber.Visit(pdfDocument.Pages[1]);

// ページ上の最初のテーブル、その最初のセル、およびその中のテキストフラグメントにアクセスします
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// セル内の最初のテキストフラグメントのテキストを変更します
fragment.Text = "hi world";

// 保存 document
doc.Save(@"D:\Tests\output.pdf");  
```

### 関連項目

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


