---
title: "DictionaryEditor.Item"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété DictionaryEditor. Obtient ou définit l'élément avec la clé spécifiée"
type: docs
weight: 50
url: /fr/net/aspose.pdf.dataeditor/dictionaryeditor/item/
---
## DictionaryEditor indexer

Obtient ou définit l'élément avec la clé spécifiée.

```csharp
public ICosPdfPrimitive this[string key] { get; set; }
```

| Paramètre | Description |
| --- | --- |
| clé | La clé de l'élément à obtenir ou à définir. |

### Valeur de retour

L'élément avec la clé spécifiée.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | La clé est nulle. |
| KeyNotFoundException | La propriété est récupérée et la clé n'est pas trouvée. |
| ArgumentException | Lancez une exception si la clé ne peut pas être modifiée/établie. |

### Voir aussi

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* class [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)


