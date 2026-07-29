---
title: "TableAbsorber"
linktitle: "TableAbsorber"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "<p> テーブル要素の吸収オブジェクトを表します。検索を実行し、{@code TableAbsorber.TableList} コレクションを介して検索結果へのアクセスを提供します。 </p> <hr> <pre> The."
type: docs
weight: 4800
url: /ja/java/com.aspose.pdf/tableabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TableAbsorber

```
public class TableAbsorber extends Object
```

<p> テーブル要素の吸収オブジェクトを表します。検索を実行し、{@code TableAbsorber.TableList} コレクションを介して検索結果へのアクセスを提供します。 </p> <hr> <pre> この例は、最初の PDF ドキュメントページでテーブルを見つけ、テーブルセル内のテキストを置換する方法を示しています。 // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TableAbsorber object to find tables TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber absorber.visit(doc.getPages().get_Item(1)); // Get access to first table on page, their first cell and text fragments in it TextFragment fragment = absorber.getTableList().get_Item(0).getRowList().get_Item(0).getCellList().get_Item(0) .getTextFragments().get_Item(1); // Change text of the first text fragment in the cell fragment.setText("hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TableAbsorber](#TableAbsorber--) | <p> {@code TableAbsorber} の新しいインスタンスを初期化します。 </p> <hr> テーブルの検索を実行し、{@code TableList} オブジェクトを介してテーブルへのアクセスを提供します。 |
| [TableAbsorber](#TableAbsorber-com.aspose.pdf.TextSearchOptions-) | <p> {@code TableAbsorber} の新しいインスタンスを初期化します。 </p> <hr> テーブルの検索を実行し、{@code TableList} オブジェクトを介してテーブルへのアクセスを提供します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getTableList](#getTableList--) | <p> 見つかったテーブルを含む読み取り専用 IList を返します </p> |
| [getTextSearchOptions](#getTextSearchOptions--) | <p> テキスト検索オプションを取得します。 </p> <hr> テーブル内のテキスト検索時に使用される複数のオプションを定義できます。 |
| [isUseFlowEngine](#isUseFlowEngine--) | 多数のシナリオで優れた代替テーブル認識エンジンを有効にし、罫線のないテーブルを認識できるようにします。 |
| [remove](#remove-com.aspose.pdf.AbsorbedTable-) | <p> ページから {@code AbsorbedTable} を削除します。 </p> <hr> <p> これにより TableList コレクションが変更されることに留意してください。ループ内でテーブルを削除/置換する場合は、TableList コレクションのコピーを使用してください。 </p> |
| [replace](#replace-com.aspose.pdf.Page-com.aspose.pdf.AbsorbedTable-com.aspose.pdf.Table-) | <p> ページ上の {@code AbsorbedTable} を {@code Table} に置換します。 </p> <hr> <p> これにより TableList コレクションが変更されることに留意してください。ループ内でテーブルを削除/置換する場合は、TableList コレクションのコピーを使用してください。 </p> |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | <p> テキスト検索オプションを取得または設定します。 </p> <hr> テーブル内のテキスト検索時に使用される複数のオプションを定義できます。 |
| [setUseFlowEngine](#setUseFlowEngine-boolean-) | 多数のシナリオで優れた代替テーブル認識エンジンを有効にし、罫線のないテーブルを認識できるようにします。 |
| [visit](#visit-com.aspose.pdf.IDocument-) | <p> 指定されたドキュメントからテーブルを抽出します。 </p> <hr> <pre> この例は、PDF ドキュメントの最初のページからテーブルを抽出する方法を示しています。 // ドキュメントを開く Document doc = new Document(@\"D:\\\\Tests\\\\input.pdf\"); // テーブルを検索するための TableAbsorber オブジェクトを作成 TableAbsorber absorber = new TableAbsorber(); // 吸収器で最初のページを訪問 absorber.visit(pdfDocument); // ページ上の最初のテーブル、その最初のセル、およびその中のテキストフラグメントにアクセス TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // セル内の最初のテキストフラグメントのテキストを変更 fragment.setText (\"hi world\"); // ドキュメントを保存 doc.save(@\"D:\\\\Tests\\\\output.pdf\"); </pre> |
| [visit](#visit-com.aspose.pdf.Page-) | <p> 指定されたページからテーブルを抽出します </p> <hr> <pre> この例は、PDF ドキュメントの最初のページからテーブルを抽出する方法を示しています。 // ドキュメントを開く Document doc = new Document(@\"D:\\\\Tests\\\\input.pdf\"); // テーブルを検索するための TableAbsorber オブジェクトを作成 TableAbsorber absorber = new TableAbsorber(); // 吸収器で最初のページを訪問 absorber.visit(doc.getPages.get_item(1)); // ページ上の最初のテーブル、その最初のセル、およびその中のテキストフラグメントにアクセス TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // セル内の最初のテキストフラグメントのテキストを変更 fragment.setText (\"hi world\"); // ドキュメントを保存 doc.save(@\"D:\\\\Tests\\\\output.pdf\"); </pre> |

### TableAbsorber {#TableAbsorber--}
```
public TableAbsorber()
```

<p> {@code TableAbsorber} の新しいインスタンスを初期化します。 </p> <hr> テーブルの検索を実行し、{@code TableList} オブジェクトを介してテーブルへのアクセスを提供します。

### TableAbsorber {#TableAbsorber-com.aspose.pdf.TextSearchOptions-}
<p> {@code TableAbsorber} の新しいインスタンスを初期化します。 </p> <hr> テーブルの検索を実行し、{@code TableList} オブジェクトを介してテーブルへのアクセスを提供します。

### getTableList {#getTableList--}
```
public List < AbsorbedTable > getTableList()
```

<p> 見つかったテーブルを含む読み取り専用 IList を返します </p>

**Returns:**
{@code IGenericList<AbsorbedTable> object}

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

<p> テキスト検索オプションを取得します。 </p> <hr> テーブル内のテキスト検索時に使用される複数のオプションを定義できます。

**Returns:**
TextSearchOptions オブジェクト

### isUseFlowEngine {#isUseFlowEngine--}
```
public boolean isUseFlowEngine()
```

多数のシナリオで優れた代替テーブル認識エンジンを有効にし、罫線のないテーブルを認識できるようにします。

**Returns:**
ブール値

### remove {#remove-com.aspose.pdf.AbsorbedTable-}
<p> ページから {@code AbsorbedTable} を削除します。 </p> <hr> <p> これにより TableList コレクションが変更されることに留意してください。ループ内でテーブルを削除/置換する場合は、TableList コレクションのコピーを使用してください。 </p>

### replace {#replace-com.aspose.pdf.Page-com.aspose.pdf.AbsorbedTable-com.aspose.pdf.Table-}
<p> ページ上の {@code AbsorbedTable} を {@code Table} に置換します。 </p> <hr> <p> これにより TableList コレクションが変更されることに留意してください。ループ内でテーブルを削除/置換する場合は、TableList コレクションのコピーを使用してください。 </p>

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
<p> テキスト検索オプションを取得または設定します。 </p> <hr> テーブル内のテキスト検索時に使用される複数のオプションを定義できます。

### setUseFlowEngine {#setUseFlowEngine-boolean-}
```
public void setUseFlowEngine(boolean useFlowEngine)
```

多数のシナリオで優れた代替テーブル認識エンジンを有効にし、罫線のないテーブルを認識できるようにします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| useFlowEngine |  | ブール値 |

### visit {#visit-com.aspose.pdf.IDocument-}
<p> 指定されたドキュメントからテーブルを抽出します。 </p> <hr> <pre> この例は、PDF ドキュメントの最初のページからテーブルを抽出する方法を示しています。 // ドキュメントを開く Document doc = new Document(@\"D:\\Tests\\input.pdf\"); // テーブルを検索するための TableAbsorber オブジェクトを作成 TableAbsorber absorber = new TableAbsorber(); // 吸収器で最初のページを訪問 absorber.visit(pdfDocument); // ページ上の最初のテーブル、その最初のセル、およびその中のテキストフラグメントにアクセス TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // セル内の最初のテキストフラグメントのテキストを変更 fragment.setText (\"hi world\"); // ドキュメントを保存 doc.save(@\"D:\\Tests\\output.pdf\"); </pre>

### visit {#visit-com.aspose.pdf.Page-}
<p> 指定されたページからテーブルを抽出します </p> <hr> <pre> この例は、PDF ドキュメントの最初のページからテーブルを抽出する方法を示しています。 // ドキュメントを開く Document doc = new Document(@\"D:\\Tests\\input.pdf\"); // テーブルを検索するための TableAbsorber オブジェクトを作成 TableAbsorber absorber = new TableAbsorber(); // 吸収器で最初のページを訪問 absorber.visit(doc.getPages.get_item(1)); // ページ上の最初のテーブル、その最初のセル、およびその中のテキストフラグメントにアクセス TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // セル内の最初のテキストフラグメントのテキストを変更 fragment.setText (\"hi world\"); // ドキュメントを保存 doc.save(@\"D:\\Tests\\output.pdf\"); </pre>
