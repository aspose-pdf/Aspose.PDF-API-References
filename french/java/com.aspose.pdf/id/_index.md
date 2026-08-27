---
title: "Id"
linktitle: "Id"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "<p> Représente la structure d'identifiant de fichier. </p> <hr> <pre> Document doc = new Document(\\\"example.pdf\\\"); String original = doc.getId().getOriginal(); String modified =."
type: docs
weight: 2220
url: /fr/java/com.aspose.pdf/id/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Id

```
public class Id extends Object
```

<p> Représente la structure d'identifiant de fichier. </p> <hr> <pre> Document doc = new Document("example.pdf"); String original = doc.getId().getOriginal(); String modified = doc.getId().getModified(); </pre>

## Méthodes

| Méthode | Description |
| --- | --- |
| [getModified](#getModified--) | Modification de l'identifiant en fonction du contenu du document au moment de sa dernière mise à jour. |
| [getOriginal](#getOriginal--) | Identifiant permanent basé sur le contenu du document au moment de sa création initiale. |

### getModified {#getModified--}
```
public String getModified()
```

Modification de l'identifiant en fonction du contenu du document au moment de sa dernière mise à jour.

**Returns:**
valeur String

### getOriginal {#getOriginal--}
```
public String getOriginal()
```

Identifiant permanent basé sur le contenu du document au moment de sa création initiale.

**Returns:**
valeur String
