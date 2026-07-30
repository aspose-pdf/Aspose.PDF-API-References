---
title: "Table.ImportDataTable"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode Table. Importe les données de System.Data.DataTable vers Aspose.Pdf.Table"
type: docs
weight: 260
url: /fr/net/aspose.pdf/table/importdatatable/
---
## ImportDataTable(DataTable, bool, int, int) {#importdatatable_1}

Importe des données de System.Data.DataTable dans Aspose.Pdf.Table

```csharp
public void ImportDataTable(DataTable importedDataTable, bool isColumnNamesImported, 
    int firstFilledRow, int firstFilledColumn)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| importedDataTable | DataTable | instance source de System.Data.DataTable |
| isColumnNamesImported | Boolean | spécifie si les noms de colonnes seront importés comme première ligne |
| firstFilledRow | Int32 | spécifie le numéro basé sur zéro de la première ligne dans le tableau cible à partir de laquelle l'importation commencera, si la ligne avec ce numéro (et certaines lignes précédentes) est absente du tableau cible, elle sera créée en premier |
| firstFilledColumn | Int32 | spécifie le numéro de la première colonne cible dans le tableau cible, la colonne doit être présente dans le tableau cible avant le début de l'importation |

### Voir aussi

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## ImportDataTable(DataTable, bool, int, byte, int, int, bool) {#importdatatable}

Importe un objet DataTable dans le tableau.

```csharp
public void ImportDataTable(DataTable importedDataTable, bool isColumnNamesShown, 
    int firstFilledRow, byte firstFilledColumn, int maxRows, int maxColumns, 
    bool isHtmlSupported = false)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| importedDataTable | DataTable | L'objet DataTable à importer. |
| isColumnNamesShown | Boolean | Spécifie si les noms de colonnes du datatable source seront importés en première ligne. |
| firstFilledRow | Int32 | spécifie le numéro basé sur zéro de la première ligne dans le tableau cible à partir de laquelle l'importation commencera, si la ligne avec ce numéro (et certaines lignes précédentes) est absente du tableau cible, elle sera créée en premier |
| firstFilledColumn | Byte | spécifie le numéro de la première colonne cible dans le tableau cible, la colonne doit être présente dans le tableau cible avant le début de l'importation |
| maxRows | Int32 | Nombre maximal de lignes à importer depuis la table source. |
| maxColumns | Int32 | Nombre maximal de colonnes à importer depuis la table source. |
| isHtmlSupported | Boolean | Spécifie si le texte est une chaîne HTML. |

### Voir aussi

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## ImportDataTable(DataTable, int[], int[], int, int, bool, bool) {#importdatatable_2}

Importe un objet DataTable, mais pas en tant qu'entité complète. Seules les lignes et colonnes spécifiées sont importées.

```csharp
public void ImportDataTable(DataTable importedDataTable, int[] sourceRowList, 
    int[] sourceColumnList, int firstFilledRow, int firstFilledColumn, 
    bool showColumnNamesAsFirstRow, bool isHtmlSupported = false)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| importedDataTable | DataTable | L'objet DataTable à importer. |
| sourceRowList | Int32[] | Le tableau des numéros de lignes dans l'objet DataTable source qui doivent être importés. La liste ne doit pas être nulle et doit contenir uniquement les numéros de lignes existantes, sinon une exception sera levée. |
| sourceColumnList | Int32[] | Le tableau des numéros de colonnes dans l'objet DataTable source qui doivent être importés. La liste ne doit pas être nulle et doit contenir uniquement les numéros de colonnes existantes, sinon une exception sera levée. |
| firstFilledRow | Int32 | Le numéro de ligne, basé sur zéro, de la première cellule dans la table cible à partir duquel l'importation commencera. Si la table cible ne contient pas cette ligne, elle (et toutes les précédentes si nécessaire) sera créée. |
| firstFilledColumn | Int32 | Le numéro de colonne, basé sur zéro, de la première cellule dans la table cible à partir duquel l'importation commencera. La table cible doit contenir cette colonne avant le début de l'importation, sinon une exception sera levée. |
| showColumnNamesAsFirstRow | Boolean | Spécifie si les noms de colonnes du datatable source seront importés en première ligne. |
| isHtmlSupported | Boolean | Spécifie si le texte est une chaîne HTML. |

### Voir aussi

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


