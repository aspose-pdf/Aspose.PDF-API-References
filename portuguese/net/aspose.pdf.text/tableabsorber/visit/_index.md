---
title: TableAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: Método TableAbsorber. Extrai tabelas na página especificada
type: docs
weight: 70
url: /pt/net/aspose.pdf.text/tableabsorber/visit/
---
## Visit(Page) {#visit_1}

Extrai tabelas na página especificada

```csharp
public virtual void Visit(Page page)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| page | Page | Objeto de página do documento Pdf. |

## Exemplos

O exemplo demonstra como extrair a tabela na primeira página do documento PDF.

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

### Veja Também

* class [Page](../../../aspose.pdf/page/)
* class [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Extrai tabelas no documento especificado.

```csharp
public void Visit(Document pdf)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pdf | Document | Objeto do documento Pdf. |

## Exemplos

O exemplo demonstra como extrair a tabela na primeira página do documento PDF.

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

### Veja Também

* class [Document](../../../aspose.pdf/document/)
* class [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)