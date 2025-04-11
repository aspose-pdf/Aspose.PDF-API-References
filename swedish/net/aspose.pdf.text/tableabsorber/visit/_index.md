---
title: TableAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: TableAbsorber-metod. Extraherar tabeller på den angivna sidan
type: docs
weight: 70
url: /sv/net/aspose.pdf.text/tableabsorber/visit/
---
## Visit(Page) {#visit_1}

Extraherar tabeller på den angivna sidan

```csharp
public virtual void Visit(Page page)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page | Page | Pdf-dokument sidobjekt. |

## Exempel

Exemplet visar hur man extraherar tabell på den första PDF-dokument sidan.

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

### Se Även

* klass [Page](../../../aspose.pdf/page/)
* klass [TableAbsorber](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Extraherar tabeller i det angivna dokumentet.

```csharp
public void Visit(Document pdf)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pdf | Document | Pdf-dokument objekt. |

## Exempel

Exemplet visar hur man extraherar tabell på den första PDF-dokument sidan.

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

### Se Även

* klass [Document](../../../aspose.pdf/document/)
* klass [TableAbsorber](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)