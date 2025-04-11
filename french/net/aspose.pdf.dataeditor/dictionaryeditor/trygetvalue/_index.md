---
title: DictionaryEditor.TryGetValue
second_title: Aspose.PDF for .NET API Reference
description: Méthode DictionaryEditor. Pour accéder à des types de données simples comme string, name, bool, number. Renvoie null pour d'autres types
type: docs
weight: 150
url: /fr/net/aspose.pdf.dataeditor/dictionaryeditor/trygetvalue/
---
## Méthode DictionaryEditor.TryGetValue

Pour accéder à des types de données simples comme string, name, bool, number. Renvoie null pour d'autres types.

```csharp
public bool TryGetValue(string key, out ICosPdfPrimitive value)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| key | String | Valeur de la clé |
| value | ICosPdfPrimitive& | renvoie [`ICosPdfPrimitive`](../../icospdfprimitive/) pour la clé ou null. |

### Valeur de retour

Renvoie true si [`ICosPdfPrimitive`](../../icospdfprimitive/) est comme string, name, bool, number. Renvoie false pour tous les autres types.

### Voir aussi

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* class [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)