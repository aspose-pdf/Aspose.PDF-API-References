---
title: Table.ImportArray
second_title: Aspose.PDF for .NET API Reference
description: Méthode Table. Importe un tableau unidimensionnel de données dans une table. L'importation se fait une cellule par élément du tableau et commence à partir de la ligne et de la colonne définies dans les paramètres. Pendant l'importation, si des lignes nécessaires sont encore absentes, c'est-à-dire que la table cible est trop petite pour absorber toutes les données, les lignes nécessaires seront créées.
type: docs
weight: 250
url: /fr/net/aspose.pdf/table/importarray/
---
## Méthode Table.ImportArray

Importe un tableau unidimensionnel de données dans une table. L'importation se fait une cellule par élément du tableau et commence à partir de la ligne et de la colonne définies dans les paramètres. Pendant l'importation, si des lignes nécessaires sont encore absentes (c'est-à-dire que la table cible est trop petite pour absorber toutes les données), les lignes nécessaires seront créées.

```csharp
public void ImportArray(object[] importedArray, int firstFilledRow, int firstFilledColumn, 
    bool isLeftColumnsFilled)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| importedArray | Object[] | données importées, les valeurs nulles seront importées comme des chaînes vides |
| firstFilledRow | Int32 | définit le numéro de la première ligne cible dans la table cible à partir de laquelle l'importation commencera. Si le nombre de lignes dans la table cible est inférieur à celui requis, les lignes manquantes seront créées en premier. |
| firstFilledColumn | Int32 | spécifie le numéro de la première colonne cible dans la table cible, la colonne doit être présente dans la table cible avant le début de l'importation |
| isLeftColumnsFilled | Boolean | Si 'isLeftColumnsFilled'=false, alors dans la deuxième et toutes les lignes remplies suivantes, les cellules qui se trouvent à gauche de firstFilledColumn seront ignorées |

### Voir aussi

* classe [Table](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)