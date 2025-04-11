---
title: TableAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: TableAbsorber-Methode. Extrahiert Tabellen auf der angegebenen Seite
type: docs
weight: 70
url: /de/net/aspose.pdf.text/tableabsorber/visit/
---
## Besuchen(Page) {#visit_1}

Extrahiert Tabellen auf der angegebenen Seite

```csharp
public virtual void Visit(Page page)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | Seite | Pdf-Dokumentseitenobjekt. |

## Beispiele

Das Beispiel zeigt, wie man eine Tabelle auf der ersten Seite des PDF-Dokuments extrahiert.

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

### Siehe auch

* Klasse [Seite](../../../aspose.pdf/page/)
* Klasse [TableAbsorber](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)

---

## Besuchen(Dokument) {#visit}

Extrahiert Tabellen im angegebenen Dokument.

```csharp
public void Visit(Document pdf)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pdf | Dokument | Pdf-Dokumentobjekt. |

## Beispiele

Das Beispiel zeigt, wie man eine Tabelle auf der ersten Seite des PDF-Dokuments extrahiert.

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

### Siehe auch

* Klasse [Dokument](../../../aspose.pdf/document/)
* Klasse [TableAbsorber](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)