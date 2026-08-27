---
title: "DictionaryEditor.Remove"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode DictionaryEditor. Supprime l'élément avec la clé spécifiée du DictionaryEditor"
type: docs
weight: 140
url: /fr/net/aspose.pdf.dataeditor/dictionaryeditor/remove/
---
## Remove(string) {#remove_1}

Supprime l'élément avec la clé spécifiée du [`DictionaryEditor`](../).

```csharp
public bool Remove(string key)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| clé | String | La clé de l'élément à supprimer. |

### Valeur de retour

True si l'élément est supprimé avec succès ; sinon, false. Cette méthode renvoie également false si la clé n'a pas été trouvée dans le dictionnaire original ou si la clé n'est pas modifiable

### Voir aussi

* class [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) {#remove}

Supprime la première occurrence d'un objet spécifique du [`DictionaryEditor`](../).

```csharp
public bool Remove(KeyValuePair<string, ICosPdfPrimitive> item)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| item | KeyValuePair`2 | L'objet à supprimer du [`DictionaryEditor`](../). |

### Valeur de retour

true si l'élément a été supprimé avec succès du [`DictionaryEditor`](../) ; sinon, false. Cette méthode renvoie également false si l'élément n'est pas trouvé dans le [`DictionaryEditor`](../) original.

### Voir aussi

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* class [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)


