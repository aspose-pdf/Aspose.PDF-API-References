---
title: Table.ImportDataView
second_title: Aspose.PDF for .NET API Reference
description: Méthode Table. Importe les données d'un objet DataView dans la table
type: docs
weight: 270
url: /fr/net/aspose.pdf/table/importdataview/
---
## Méthode Table.ImportDataView

Importe les données d'un objet DataView dans la table.

```csharp
public void ImportDataView(DataView sourceDataView, bool isColumnNamesImported, int firstFilledRow, 
    int firstFilledColumn, int maxRows, int maxColumns)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceDataView | DataView | L'objet DataView à importer. |
| isColumnNamesImported | Boolean | Indique si les noms de colonnes seront importés en tant que première ligne. |
| firstFilledRow | Int32 | Le numéro de ligne basé sur zéro de la première cellule dans la table cible à partir de laquelle l'importation commencera. Si la table cible ne contient pas cette ligne, elle (et toutes les précédentes si nécessaire) sera créée |
| firstFilledColumn | Int32 | Le numéro de colonne basé sur zéro de la première cellule dans la table cible à partir de laquelle l'importation commencera. La table cible doit contenir cette colonne avant que l'importation ne commence, sinon une exception sera levée. |
| maxRows | Int32 | Nombre maximum de lignes à importer depuis la source dataview. |
| maxColumns | Int32 | Nombre maximum de colonnes à importer depuis la source dataview. |

### Voir aussi

* classe [Table](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)