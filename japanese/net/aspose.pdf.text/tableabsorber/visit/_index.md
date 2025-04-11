---
title: TableAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: TableAbsorber メソッド。指定されたページのテーブルを抽出します
type: docs
weight: 70
url: /ja/net/aspose.pdf.text/tableabsorber/visit/
---
## Visit(Page) {#visit_1}

指定されたページのテーブルを抽出します

```csharp
public virtual void Visit(Page page)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| page | Page | Pdf ドキュメントページオブジェクト。 |

## 例

この例では、最初の PDF ドキュメントページからテーブルを抽出する方法を示します。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TableAbsorber object to find tables
TableAbsorber absorber = new TableAbsorber();

// Visit first page with absorber
absorber.Visit(doc.Pages[1]);

// Get access to first table on page, their first cell and text fragments in it
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Change text of the first text fragment in the cell
fragment.Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### 参照

* class [Page](../../../aspose.pdf/page/)
* class [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

指定されたドキュメント内のテーブルを抽出します。

```csharp
public void Visit(Document pdf)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pdf | Document | Pdf ドキュメントオブジェクト。 |

## 例

この例では、最初の PDF ドキュメントページからテーブルを抽出する方法を示します。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TableAbsorber object to find tables
TableAbsorber absorber = new TableAbsorber();

// Visit first page with absorber
absorber.Visit(doc);

// Get access to first table on page, their first cell and text fragments in it
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Change text of the first text fragment in the cell
fragment.Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### 参照

* class [Document](../../../aspose.pdf/document/)
* class [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)