---
title: TableAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: TableAbsorber method. Extracts tables on the specified page
type: docs
weight: 70
url: /net/aspose.pdf.text/tableabsorber/visit/
---
## Visit(Page) {#visit_1}

Extracts tables on the specified page

```csharp
public virtual void Visit(Page page)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Page | Pdf pocument page object. |

## Examples

The example demonstrates how to extract table on the first PDF document page.

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

### See Also

* class [Page](../../../aspose.pdf/page/)
* class [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Extracts tables in the specified document.

```csharp
public void Visit(Document pdf)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pdf | Document | Pdf pocument object. |

## Examples

The example demonstrates how to extract table on the first PDF document page.

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

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


