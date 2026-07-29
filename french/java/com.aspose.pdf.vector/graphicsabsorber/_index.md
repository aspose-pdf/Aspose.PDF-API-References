---
title: "GraphicsAbsorber"
linktitle: "GraphicsAbsorber"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente un objet absorbeur d'éléments graphiques. Effectue une recherche graphique et fournit l'accès aux résultats de recherche via {@code GraphicsAbsorber.Elements}({@link."
type: docs
weight: 30
url: /fr/java/com.aspose.pdf.vector/graphicsabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicsAbsorber

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public class GraphicsAbsorber extends Object implements com.aspose.ms.System.IDisposable
```

Représente un objet absorbeur d'éléments graphiques. Effectue la recherche graphique et fournit l'accès aux résultats de recherche via la collection {@code GraphicsAbsorber.Elements}({@link GraphicsAbsorber#getElements}).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [GraphicsAbsorber](#GraphicsAbsorber--) |  |

## Méthodes

| Méthode | Description |
| --- | --- |
| [dispose](#dispose--) | Libère toutes les ressources utilisées par la classe {@link GraphicsAbsorber}. |
| [getElements](#getElements--) | Obtient la collection d'occurrences de recherche présentées avec des objets {@link GraphicElement}. |
| [resumeUpdate](#resumeUpdate--) | Reprend la mise à jour de Page#getContents et de tous les @link XForm#getContents. Cela a été fait pour augmenter les performances, voir aussi. |
| [suppressUpdate](#suppressUpdate--) | Supprime la mise à jour de Page#getContents et de tous les @link XForm#getContents. Cela a été fait pour augmenter les performances, voir aussi. |
| [visit](#visit-com.aspose.pdf.Page-) | Effectue la recherche sur la page spécifiée. |

### GraphicsAbsorber {#GraphicsAbsorber--}
```
public GraphicsAbsorber()
```



### dispose {#dispose--}
```
public final void dispose()
```

Libère toutes les ressources utilisées par la classe {@link GraphicsAbsorber}.

### getElements {#getElements--}
```
public final GraphicElementCollection getElements()
```

Obtient la collection d'occurrences de recherche présentées avec des objets {@link GraphicElement}.

**Returns:**
Instance de GraphicElementCollection

### resumeUpdate {#resumeUpdate--}
```
public final void resumeUpdate()
```

Reprend la mise à jour de Page#getContents et de tous les @link XForm#getContents. Cela a été fait pour augmenter les performances, voir aussi.

### suppressUpdate {#suppressUpdate--}
```
public final void suppressUpdate()
```

Supprime la mise à jour de Page#getContents et de tous les @link XForm#getContents. Cela a été fait pour augmenter les performances, voir aussi.

### visit {#visit-com.aspose.pdf.Page-}
Effectue la recherche sur la page spécifiée.
