---
title: "TableAbsorber.Replace"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode TableAbsorber. Remplace un AbsorbedTable par Table sur la page"
type: docs
weight: 60
url: /fr/net/aspose.pdf.text/tableabsorber/replace/
---
## TableAbsorber.Replace method

Remplace un [`AbsorbedTable`](../../absorbedtable/) par [`Table`](../../../aspose.pdf/table/) sur la page.

```csharp
public void Replace(Page page, AbsorbedTable oldTable, Table newTable)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| page | Page | Objet de page de document PDF. |
| oldTable | AbsorbedTable | [`AbsorbedTable`](../../absorbedtable/) à remplacer. |
| newTable | Table | [`Table`](../../../aspose.pdf/table/) pour remplacer l'ancienne table. |

## Remarques

Veuillez prendre en compte que cela modifie la collection TableList. En cas de suppression/remplacement de tables dans une boucle, veuillez utiliser une copie de la collection TableList.

### Voir aussi

* class [Page](../../../aspose.pdf/page/)
* class [AbsorbedTable](../../absorbedtable/)
* class [Table](../../../aspose.pdf/table/)
* class [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


