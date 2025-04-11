---
title: TableAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: Metodo TableAbsorber. Estrae tabelle nella pagina specificata
type: docs
weight: 70
url: /it/net/aspose.pdf.text/tableabsorber/visit/
---
## Visit(Page) {#visit_1}

Estrae tabelle nella pagina specificata

```csharp
public virtual void Visit(Page page)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | Page | Oggetto pagina del documento Pdf. |

## Esempi

L'esempio dimostra come estrarre una tabella nella prima pagina del documento PDF.

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

### Vedi Anche

* classe [Page](../../../aspose.pdf/page/)
* classe [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Estrae tabelle nel documento specificato.

```csharp
public void Visit(Document pdf)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pdf | Document | Oggetto documento Pdf. |

## Esempi

L'esempio dimostra come estrarre una tabella nella prima pagina del documento PDF.

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

### Vedi Anche

* classe [Document](../../../aspose.pdf/document/)
* classe [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)