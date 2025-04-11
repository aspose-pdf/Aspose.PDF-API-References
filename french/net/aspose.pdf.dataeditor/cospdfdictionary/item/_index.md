---
title: CosPdfDictionary.Item
second_title: Aspose.PDF for .NET API Reference
description: Propriété CosPdfDictionary. Obtient ou définit l'élément avec la clé spécifiée
type: docs
weight: 60
url: /fr/net/aspose.pdf.dataeditor/cospdfdictionary/item/
---
## Indexeur CosPdfDictionary

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
* class [CosPdfDictionary](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)