---
title: "Layer"
linktitle: "Layer"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente un calque au sein d'une page PDF."
type: docs
weight: 2640
url: /fr/java/com.aspose.pdf/layer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Layer

```
public class Layer extends Object
```

Représente un calque au sein d'une page PDF.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Layer](#Layer-java.lang.String-java.lang.String-) | Initialise une nouvelle instance de la classe {@code Layer}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [delete](#delete--) | Supprime la couche actuelle du document PDF. |
| [flatten](#flatten-boolean-) | Aplatisse la couche spécifiée. |
| [getContents](#getContents--) | <p> Obtient le contenu de la couche. </p> |
| [getDefaultState](#getDefaultState--) | Obtient l'état par défaut de la couche PDF. |
| [getId](#getId--) | Obtient l'identifiant de la couche. |
| [getLocked](#getLocked--) | Obtient une valeur indiquant si la couche est verrouillée. |
| [getName](#getName--) | Obtient le nom de la couche. |
| [lock](#lock--) | Verrouille la couche. |
| [save](#save-java.io.OutputStream-) | Enregistre la couche actuelle dans un document PDF. |
| [save](#save-java.lang.String-) | Enregistre la couche actuelle dans un document PDF. |
| [setDefaultState](#setDefaultState-com.aspose.pdf.DefaultState-) | Définit l'état par défaut de la couche PDF. |
| [unlock](#unlock--) | Déverrouille la couche. |

### Layer {#Layer-java.lang.String-java.lang.String-}
Initialise une nouvelle instance de la classe {@code Layer}.

### delete {#delete--}
```
public final void delete()
```

Supprime la couche actuelle du document PDF.

### flatten {#flatten-boolean-}
```
public final void flatten(boolean cleanupContentStream)
```

Aplatisse la couche spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cleanupContentStream |  | Spécifie s'il faut supprimer les marqueurs de groupe de contenu optionnel du flux de contenu. Définir le paramètre {@code cleanupContentStream} sur false accélère le processus d'aplatissement. |

### getContents {#getContents--}
```
public List < Operator > getContents()
```

<p> Obtient le contenu de la couche. </p>

**Returns:**
{@code List<Operator>} objet

### getDefaultState {#getDefaultState--}
```
public final DefaultState getDefaultState()
```

Obtient l'état par défaut de la couche PDF.

**Returns:**
l'état par défaut de la couche PDF.

### getId {#getId--}
```
public String getId()
```

Obtient l'identifiant de la couche.

**Returns:**
valeur String

### getLocked {#getLocked--}
```
public final boolean getLocked()
```

Obtient une valeur indiquant si la couche est verrouillée.

**Returns:**
valeur booléenne

### getName {#getName--}
```
public String getName()
```

Obtient le nom de la couche.

**Returns:**
valeur String

### lock {#lock--}
```
public final void lock()
```

Verrouille la couche.

### save {#save-java.io.OutputStream-}
Enregistre la couche actuelle dans un document PDF.

### save {#save-java.lang.String-}
Enregistre la couche actuelle dans un document PDF.

### setDefaultState {#setDefaultState-com.aspose.pdf.DefaultState-}
Définit l'état par défaut de la couche PDF.

### unlock {#unlock--}
```
public final void unlock()
```

Déverrouille la couche.
