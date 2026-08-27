---
title: "TableAbsorber.Visit"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "TableAbsorber メソッド。指定されたページのテーブルを抽出します"
type: docs
weight: 70
url: /ja/net/aspose.pdf.text/tableabsorber/visit/
---
## Visit(Page) {#visit_1}

指定されたページ上のテーブルを抽出します

```csharp
public virtual void Visit(Page page)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| ページ | ページ | Pdf ドキュメント ページ オブジェクト。 |

## 例

この例では、最初の PDF ドキュメントページからテーブルを抽出する方法を示しています。

```csharp
// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

// テーブルを見つけるために TableAbsorber オブジェクトを作成します
TableAbsorber absorber = new TableAbsorber();

// 吸収オブジェクトで最初のページを訪問します
absorber.Visit(doc.Pages[1]);

// ページ上の最初のテーブル、その最初のセル、およびその中のテキストフラグメントにアクセスします
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// セル内の最初のテキストフラグメントのテキストを変更します
fragment.Text = "hi world";

// 保存 document
doc.Save(@"D:\Tests\output.pdf");  
```

### 関連項目

* class [Page](../../../aspose.pdf/page/)
* class [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

指定されたドキュメントからテーブルを抽出します。

```csharp
public void Visit(Document pdf)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| pdf | Document | Pdf ドキュメント オブジェクト。 |

## 例

この例では、最初の PDF ドキュメントページからテーブルを抽出する方法を示しています。

```csharp
// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

// テーブルを見つけるために TableAbsorber オブジェクトを作成します
TableAbsorber absorber = new TableAbsorber();

// 吸収オブジェクトで最初のページを訪問します
absorber.Visit(doc);

// ページ上の最初のテーブル、その最初のセル、およびその中のテキストフラグメントにアクセスします
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// セル内の最初のテキストフラグメントのテキストを変更します
fragment.Text = "hi world";

// 保存 document
doc.Save(@"D:\Tests\output.pdf");  
```

### 関連項目

* class [Document](../../../aspose.pdf/document/)
* class [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


