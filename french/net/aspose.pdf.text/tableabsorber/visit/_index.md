---
title: TableAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: Méthode TableAbsorber. Extrait des tables sur la page spécifiée
type: docs
weight: 70
url: /fr/net/aspose.pdf.text/tableabsorber/visit/
---
## Visit(Page) {#visit_1}

Extrait des tables sur la page spécifiée

```csharp
public virtual void Visit(Page page)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| page | Page | Objet de page de document Pdf. |

## Exemples

L'exemple démontre comment extraire une table sur la première page du document PDF.

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

### Voir aussi

* classe [Page](../../../aspose.pdf/page/)
* classe [TableAbsorber](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Extrait des tables dans le document spécifié.

```csharp
public void Visit(Document pdf)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pdf | Document | Objet de document Pdf. |

## Exemples

L'exemple démontre comment extraire une table sur la première page du document PDF.

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

### Voir aussi

* classe [Document](../../../aspose.pdf/document/)
* classe [TableAbsorber](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)