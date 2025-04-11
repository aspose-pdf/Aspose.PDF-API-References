---
title: TableAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: TableAbsorber metodu. Belirtilen sayfadaki tabloları çıkarır
type: docs
weight: 70
url: /tr/net/aspose.pdf.text/tableabsorber/visit/
---
## Visit(Page) {#visit_1}

Belirtilen sayfadaki tabloları çıkarır

```csharp
public virtual void Visit(Page page)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| page | Page | Pdf belgesi sayfa nesnesi. |

## Örnekler

Örnek, ilk PDF belgesi sayfasındaki tabloyu nasıl çıkaracağınızı gösterir.

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

### Ayrıca Bakınız

* class [Page](../../../aspose.pdf/page/)
* class [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Belirtilen belgede tabloları çıkarır.

```csharp
public void Visit(Document pdf)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pdf | Document | Pdf belgesi nesnesi. |

## Örnekler

Örnek, ilk PDF belgesi sayfasındaki tabloyu nasıl çıkaracağınızı gösterir.

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

### Ayrıca Bakınız

* class [Document](../../../aspose.pdf/document/)
* class [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)