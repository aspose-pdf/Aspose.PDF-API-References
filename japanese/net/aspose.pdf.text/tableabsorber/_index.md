---
title: Class TableAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TableAbsorber クラス。テーブル要素のアブソーバーオブジェクトを表します。検索を実行し、[`TableList`](./tablelist/) コレクションを介して検索結果にアクセスします。
type: docs
weight: 10790
url: /ja/net/aspose.pdf.text/tableabsorber/
---
## TableAbsorber クラス

テーブル要素のアブソーバーオブジェクトを表します。検索を実行し、[`TableList`](./tablelist/) コレクションを介して検索結果にアクセスします。

```csharp
public class TableAbsorber
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [TableAbsorber](tableabsorber/#constructor)() | `TableAbsorber` の新しいインスタンスを初期化します。 |
| [TableAbsorber](tableabsorber/#constructor_1)(TextSearchOptions) | テキスト検索オプションを使用して `TableAbsorber` の新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| virtual [TableList](../../aspose.pdf.text/tableabsorber/tablelist/) { get; } | 見つかったテーブルを含む読み取り専用 IList を返します |
| virtual [TextSearchOptions](../../aspose.pdf.text/tableabsorber/textsearchoptions/) { get; set; } | テキスト検索オプションを取得または設定します。 |
| [UseFlowEngine](../../aspose.pdf.text/tableabsorber/useflowengine/) { get; set; } | * 数多くのシナリオで優れた代替テーブル認識エンジンを有効にし、境界線のないテーブルを認識することができます。まだテーブルの編集やテキストスタイルの取得はサポートされていません。デフォルト値は false です; |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Remove](../../aspose.pdf.text/tableabsorber/remove/)(AbsorbedTable) | ページから [`AbsorbedTable`](../absorbedtable/) を削除します。 |
| [Replace](../../aspose.pdf.text/tableabsorber/replace/)(Page, AbsorbedTable, Table) | ページ上の [`AbsorbedTable`](../absorbedtable/) を [`Table`](../../aspose.pdf/table/) で置き換えます。 |
| [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit)(Document) | 指定されたドキュメント内のテーブルを抽出します。 |
| virtual [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit_1)(Page) | 指定されたページ上のテーブルを抽出します |

## 例

この例では、最初の PDF ドキュメントページでテーブルを見つけ、テーブルセル内のテキストを置き換える方法を示します。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TableAbsorber object to find tables
TableAbsorber absorber = new TableAbsorber();

// Visit first page with absorber
absorber.Visit(pdfDocument.Pages[1]);

// Get access to first table on page, their first cell and text fragments in it
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Change text of the first text fragment in the cell
fragment.Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### 参照

* 名前空間 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../)