---
title: "Classe TableAbsorber"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Text.TableAbsorber. Représente un objet absorbeur d'éléments de tableau. Effectue la recherche et fournit l'accès aux résultats de recherche via la collection TableList"
type: docs
weight: 10970
url: /fr/net/aspose.pdf.text/tableabsorber/
---
## TableAbsorber class

Représente un objet absorbeur d'éléments de tableau. Effectue une recherche et fournit l'accès aux résultats de recherche via la collection [`TableList`](./tablelist/).

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
| virtual [TableList](../../aspose.pdf.text/tableabsorber/tablelist/) { get; } | Renvoie un IList en lecture seule contenant les tables qui ont été trouvées |
| virtual [TextSearchOptions](../../aspose.pdf.text/tableabsorber/textsearchoptions/) { get; set; } | Obtient ou définit les options de recherche de texte. |
| [UseFlowEngine](../../aspose.pdf.text/tableabsorber/useflowengine/) { get; set; } | * Active un moteur de reconnaissance de tables alternatif qui est supérieur dans de nombreux scénarios et capable de reconnaître les tables sans bordures. Ne prend pas encore en charge la modification des tables ni l'obtention des styles de texte. La valeur par défaut est false ; |

## Méthodes

| Nom | Description |
| --- | --- |
| [Remove](../../aspose.pdf.text/tableabsorber/remove/)(AbsorbedTable) | Supprime un [`AbsorbedTable`](../absorbedtable/) de la page. |
| [Replace](../../aspose.pdf.text/tableabsorber/replace/)(Page, AbsorbedTable, Table) | Remplace un [`AbsorbedTable`](../absorbedtable/) par [`Table`](../../aspose.pdf/table/) sur la page. |
| [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit)(Document) | Extrait les tables du document spécifié. |
| virtual [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit_1)(Page) | Extrait les tables de la page spécifiée |

## Exemples

L'exemple montre comment trouver une table sur la première page du document PDF et remplacer le texte dans une cellule de table.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Créez un objet TableAbsorber pour trouver des tables
TableAbsorber absorber = new TableAbsorber();

// Visitez la première page avec l'absorbeur
absorber.Visit(pdfDocument.Pages[1]);

// Obtenez l'accès à la première table de la page, à sa première cellule et aux fragments de texte qu'elle contient
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Modifiez le texte du premier fragment de texte dans la cellule
fragment.Text = "hi world";

// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf");  
```

### Voir aussi

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


