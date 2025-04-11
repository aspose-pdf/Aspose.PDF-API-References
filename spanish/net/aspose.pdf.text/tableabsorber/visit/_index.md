---
title: TableAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: Método TableAbsorber. Extrae tablas en la página especificada
type: docs
weight: 70
url: /es/net/aspose.pdf.text/tableabsorber/visit/
---
## Visit(Page) {#visit_1}

Extrae tablas en la página especificada

```csharp
public virtual void Visit(Page page)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page | Page | Objeto de página del documento Pdf. |

## Ejemplos

El ejemplo demuestra cómo extraer una tabla en la primera página del documento PDF.

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

### Ver También

* clase [Page](../../../aspose.pdf/page/)
* clase [TableAbsorber](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Extrae tablas en el documento especificado.

```csharp
public void Visit(Document pdf)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pdf | Document | Objeto del documento Pdf. |

## Ejemplos

El ejemplo demuestra cómo extraer una tabla en la primera página del documento PDF.

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

### Ver También

* clase [Document](../../../aspose.pdf/document/)
* clase [TableAbsorber](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)