---
title: DictionaryEditor.Item
second_title: Aspose.PDF for .NET API Reference
description: Propriété DictionaryEditor. Obtient ou définit l'élément avec la clé spécifiée
type: docs
weight: 50
url: /fr/net/aspose.pdf.dataeditor/dictionaryeditor/item/
---
## Indexeur DictionaryEditor

Obtient ou définit l'élément avec la clé spécifiée.

```csharp
public ICosPdfPrimitive this[string key] { get; set; }
```

| Paramètre | Description |
| --- | --- |
| key | La clé de l'élément à obtenir ou à définir. |

### Valeur de retour

L'élément avec la clé spécifiée.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | La clé est nulle. |
| KeyNotFoundException | La propriété est récupérée et la clé n'est pas trouvée. |
| ArgumentException | Lève une exception si la clé ne peut pas être modifiée/définie. |

### Voir aussi

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* class [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)