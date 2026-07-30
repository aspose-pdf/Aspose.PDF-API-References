---
title: "Table.ImportArray"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode Table. Importe un tableau unidimensionnel de données dans le tableau. L'importation place une cellule pour chaque élément du tableau et commence à la ligne et à la colonne définies dans les paramètres. Pendant l'importation, si l'on détecte que les lignes nécessaires sont encore absentes, c’est‑à‑dire que le tableau cible est trop petit pour absorber toutes les données, les lignes nécessaires seront créées."
type: docs
weight: 250
url: /fr/net/aspose.pdf/table/importarray/
---
## Table.ImportArray method

Importe un tableau unidimensionnel de données dans le tableau. L'importation place une cellule pour chaque élément du tableau et commence à la ligne et à la colonne définies dans les paramètres. Pendant l'importation, si l'on détecte que les lignes nécessaires sont encore absentes (c.-à-d. que le tableau cible est trop petit pour absorber toutes les données), les lignes nécessaires seront créées

```csharp
public void ImportArray(object[] importedArray, int firstFilledRow, int firstFilledColumn, 
    bool isLeftColumnsFilled)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| importedArray | Object[] | données importées, les null seront importés comme des chaînes vides |
| firstFilledRow | Int32 | définir le numéro de la première ligne cible dans le tableau cible à partir de laquelle l'importation commencera. Si le nombre de lignes dans le tableau cible est inférieur au requis, les lignes manquantes seront créées en premier. |
| firstFilledColumn | Int32 | spécifie le numéro de la première colonne cible dans le tableau cible, la colonne doit être présente dans le tableau cible avant le début de l'importation |
| isLeftColumnsFilled | Boolean | Si 'isLeftColumnsFilled'=false, alors dans la deuxième et toutes les lignes remplies suivantes, les cellules situées à gauche de firstFilledColumn seront ignorées. |

### Voir aussi

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


