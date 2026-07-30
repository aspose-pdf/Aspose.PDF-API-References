---
title: "DictionaryEditor.TryGetValue"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode DictionaryEditor. Pour accéder à des types de données simples comme string, name, bool, number. Retourne null pour les autres types."
type: docs
weight: 150
url: /fr/net/aspose.pdf.dataeditor/dictionaryeditor/trygetvalue/
---
## DictionaryEditor.TryGetValue method

Pour accéder à des types de données simples comme string, name, bool, number. Renvoie null pour les autres types.

```csharp
public bool TryGetValue(string key, out ICosPdfPrimitive value)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| clé | String | Valeur de la clé |
| value | ICosPdfPrimitive& | renvoie [`ICosPdfPrimitive`](../../icospdfprimitive/) pour la clé ou null. |

### Valeur de retour

Renvoie true si [`ICosPdfPrimitive`](../../icospdfprimitive/) est similaire à string, name, bool, number. Renvoie false pour tous les autres types.

### Voir aussi

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* class [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)


