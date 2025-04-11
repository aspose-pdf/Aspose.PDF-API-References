---
title: Class TableAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.TableAbsorber. Représente un objet absorbeur d'éléments de table. Effectue une recherche et fournit un accès aux résultats de recherche via la collection TableList
type: docs
weight: 10790
url: /fr/net/aspose.pdf.text/tableabsorber/
---
## Classe TableAbsorber

Représente un objet absorbeur d'éléments de table. Effectue une recherche et fournit un accès aux résultats de recherche via la collection [`TableList`](./tablelist/).

```csharp
public class TableAbsorber
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TableAbsorber](tableabsorber/#constructor)() | Initialise une nouvelle instance de `TableAbsorber`. |
| [TableAbsorber](tableabsorber/#constructor_1)(TextSearchOptions) | Initialise une nouvelle instance de `TableAbsorber` avec des options de recherche de texte. |

## Propriétés

| Nom | Description |
| --- | --- |
| virtual [TableList](../../aspose.pdf.text/tableabsorber/tablelist/) { get; } | Renvoie une IList en lecture seule contenant les tables qui ont été trouvées |
| virtual [TextSearchOptions](../../aspose.pdf.text/tableabsorber/textsearchoptions/) { get; set; } | Obtient ou définit les options de recherche de texte. |
| [UseFlowEngine](../../aspose.pdf.text/tableabsorber/useflowengine/) { get; set; } | * Active un moteur de reconnaissance de table alternatif qui est supérieur dans de nombreux scénarios et capable de reconnaître des tables sans bordures. Ne prend pas encore en charge l'édition des tables et l'obtention des styles de texte. La valeur par défaut est false; |

## Méthodes

| Nom | Description |
| --- | --- |
| [Remove](../../aspose.pdf.text/tableabsorber/remove/)(AbsorbedTable) | Supprime un [`AbsorbedTable`](../absorbedtable/) de la page. |
| [Replace](../../aspose.pdf.text/tableabsorber/replace/)(Page, AbsorbedTable, Table) | Remplace un [`AbsorbedTable`](../absorbedtable/) par un [`Table`](../../aspose.pdf/table/) sur la page. |
| [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit)(Document) | Extrait des tables dans le document spécifié. |
| virtual [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit_1)(Page) | Extrait des tables sur la page spécifiée |

## Exemples

L'exemple démontre comment trouver une table sur la première page du document PDF et remplacer le texte dans une cellule de table.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TableAbsorber object to find tables
TableAbsorber absorber = new TableAbsorber();

// Visit first page with absorber
absorber.Visit(pdfDocument.Pages[1]);

// Get access to first table on page, their first cell and text fragments in it
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Change text of the first text fragment in the cell
fragment.Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Voir aussi

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)