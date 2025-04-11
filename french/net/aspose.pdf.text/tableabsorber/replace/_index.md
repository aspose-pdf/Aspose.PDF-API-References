---
title: TableAbsorber.Replace
second_title: Aspose.PDF for .NET API Reference
description: Méthode TableAbsorber. Remplace un AbsorbedTable par Table sur la page
type: docs
weight: 60
url: /fr/net/aspose.pdf.text/tableabsorber/replace/
---
## Méthode TableAbsorber.Replace

Remplace un [`AbsorbedTable`](../../absorbedtable/) par un [`Table`](../../../aspose.pdf/table/) sur la page.

```csharp
public void Replace(Page page, AbsorbedTable oldTable, Table newTable)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| page | Page | Objet de page du document Pdf. |
| oldTable | AbsorbedTable | [`AbsorbedTable`](../../absorbedtable/) à remplacer. |
| newTable | Table | [`Table`](../../../aspose.pdf/table/) pour remplacer l'ancienne table. |

## Remarques

Veuillez prendre en compte que cela modifie la collection TableList. En cas de suppression/remplacement de tables dans une boucle, veuillez utiliser une copie de la collection TableList.

### Voir aussi

* classe [Page](../../../aspose.pdf/page/)
* classe [AbsorbedTable](../../absorbedtable/)
* classe [Table](../../../aspose.pdf/table/)
* classe [TableAbsorber](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)