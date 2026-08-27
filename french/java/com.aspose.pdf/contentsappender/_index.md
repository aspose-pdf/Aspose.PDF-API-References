---
title: "ContentsAppender"
linktitle: "ContentsAppender"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Effectue des modifications du contenu uniquement en mode APPEND. Ce mode permet d'éviter l'analyse inutile et lourde du contenu avant qu'une modification ne soit apportée au contenu. Il n'ajoute que du nouveau."
type: docs
weight: 800
url: /fr/java/com.aspose.pdf/contentsappender/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ContentsAppender

```
public class ContentsAppender extends Object
```

Effectue des modifications du contenu uniquement en mode APPEND. Ce mode permet d'éviter l'analyse inutile et lourde du contenu avant qu'une modification ne soit apportée. Il ajoute seulement de nouveaux opérateurs à la fin ou au début du contenu.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ContentsAppender](#ContentsAppender-com.aspose.pdf.Page-) | Initialise une nouvelle instance du contents appender avec la page attachée |
| [ContentsAppender](#ContentsAppender-com.aspose.pdf.XForm-) | Initialise une nouvelle instance du contents appender avec le Form XObject. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [appendToBegin](#appendToBegin-com.aspose.ms.System.Collections.Generic.List-) | Ajoute des opérateurs à la fin du contenu |
| [appendToBegin](#appendToBegin-com.aspose.pdf.Operator-) | Ajoute un opérateur à la fin du contenu |
| [appendToBegin](#appendToBegin-com.aspose.pdf.Operator:A-) | Ajoute des opérateurs à la fin du contenu |
| [appendToEnd](#appendToEnd-com.aspose.ms.System.Collections.Generic.List-) | Ajoute des opérateurs au début du contenu |
| [appendToEnd](#appendToEnd-com.aspose.pdf.Operator-) | Ajoute un opérateur au début du contenu |
| [appendToEnd](#appendToEnd-com.aspose.pdf.Operator:A-) | Ajoute des opérateurs au début du contenu |
| [getBeginCode](#getBeginCode--) | Chaîne contenant des opérateurs à insérer au début de la page. |
| [getBeginOperators](#getBeginOperators--) | <p> renvoie les opérateurs de début </p> |
| [getEndCode](#getEndCode--) | Chaîne contenant des opérateurs à ajouter à la fin de la page. |
| [getEndOperators](#getEndOperators--) | <p> renvoie les opérateurs de fin </p> |
| [resumeUpdate](#resumeUpdate--) | reprend la mise à jour du document |
| [setBeginCode](#setBeginCode-java.lang.String-) | Chaîne contenant des opérateurs à insérer au début de la page. |
| [setEndCode](#setEndCode-java.lang.String-) | Chaîne contenant des opérateurs à insérer au début de la page. |
| [suppressUpdate](#suppressUpdate--) | Supprime la mise à jour des données du contenu. Le contenu n'est pas mis à jour tant que ResumeUpdate n'est pas appelé. |
| [updateData](#updateData--) | Il s'agit de la nouvelle version de UpdateData, qui évite le décodage du contenu existant. |
| [updateDataOld](#updateDataOld--) | Doit être appelé pour appliquer les modifications |

### ContentsAppender {#ContentsAppender-com.aspose.pdf.Page-}
Initialise une nouvelle instance du contents appender avec la page attachée

### ContentsAppender {#ContentsAppender-com.aspose.pdf.XForm-}
Initialise une nouvelle instance du contents appender avec le Form XObject.

### appendToBegin {#appendToBegin-com.aspose.ms.System.Collections.Generic.List-}
Ajoute des opérateurs à la fin du contenu

### appendToBegin {#appendToBegin-com.aspose.pdf.Operator-}
Ajoute un opérateur à la fin du contenu

### appendToBegin {#appendToBegin-com.aspose.pdf.Operator:A-}
Ajoute des opérateurs à la fin du contenu

### appendToEnd {#appendToEnd-com.aspose.ms.System.Collections.Generic.List-}
Ajoute des opérateurs au début du contenu

### appendToEnd {#appendToEnd-com.aspose.pdf.Operator-}
Ajoute un opérateur au début du contenu

### appendToEnd {#appendToEnd-com.aspose.pdf.Operator:A-}
Ajoute des opérateurs au début du contenu

### getBeginCode {#getBeginCode--}
```
public String getBeginCode()
```

Chaîne contenant des opérateurs à insérer au début de la page.

**Returns:**
Objet String

### getBeginOperators {#getBeginOperators--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > getBeginOperators()
```

<p> renvoie les opérateurs de début </p>

**Returns:**
{@code List<Operator>} objet

### getEndCode {#getEndCode--}
```
public String getEndCode()
```

Chaîne contenant des opérateurs à ajouter à la fin de la page.

**Returns:**
Objet String

### getEndOperators {#getEndOperators--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > getEndOperators()
```

<p> renvoie les opérateurs de fin </p>

**Returns:**
{@code List<Operator>} objet

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

reprend la mise à jour du document

### setBeginCode {#setBeginCode-java.lang.String-}
Chaîne contenant des opérateurs à insérer au début de la page.

### setEndCode {#setEndCode-java.lang.String-}
Chaîne contenant des opérateurs à insérer au début de la page.

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

Supprime la mise à jour des données du contenu. Le contenu n'est pas mis à jour tant que ResumeUpdate n'est pas appelé.

### updateData {#updateData--}
```
public void updateData()
```

Il s'agit de la nouvelle version de UpdateData, qui évite le décodage du contenu existant.

### updateDataOld {#updateDataOld--}
```
public void updateDataOld()
```

Doit être appelé pour appliquer les modifications
