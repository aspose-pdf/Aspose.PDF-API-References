---
title: "Table.ImportDataView"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode Table. Importe les données d'un objet DataView dans le tableau"
type: docs
weight: 270
url: /fr/net/aspose.pdf/table/importdataview/
---
## Table.ImportDataView method

Importe les données d'un objet DataView dans le tableau.

```csharp
public void ImportDataView(DataView sourceDataView, bool isColumnNamesImported, int firstFilledRow, 
    int firstFilledColumn, int maxRows, int maxColumns)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceDataView | DataView | L'objet DataView à importer. |
| isColumnNamesImported | Boolean | Indique si les noms de colonnes seront importés comme première ligne. |
| firstFilledRow | Int32 | Le numéro de ligne, basé sur zéro, de la première cellule dans la table cible à partir duquel l'importation commencera. Si la table cible ne contient pas cette ligne, elle (et toutes les précédentes si nécessaire) sera créée. |
| firstFilledColumn | Int32 | Le numéro de colonne basé sur zéro de la première cellule dans le tableau cible à partir duquel l'importation commencera. Le tableau cible doit contenir cette colonne avant le début de l'importation, sinon une exception sera levée. |
| maxRows | Int32 | Nombre maximal de lignes à importer depuis le DataView source. |
| maxColumns | Int32 | Nombre maximal de colonnes à importer depuis le DataView source. |

### Voir aussi

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


