---
title: "XForm"
linktitle: "XForm"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant XForm"
type: docs
weight: 5590
url: /fr/java/com.aspose.pdf/xform/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XForm

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.IOperatorContainer

```
public final class XForm extends Object implements com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.IOperatorContainer
```

Classe représentant XForm

## Méthodes

| Méthode | Description |
| --- | --- |
| [close](#close--) | Libère la mémoire |
| [containsOwnResources](#containsOwnResources--) | Renvoie True si contient ses propres ressources |
| [createNewForm](#createNewForm-com.aspose.pdf.engine.data.ITrailerable-) | Crée un nouveau XForm dans le document. |
| [createNewForm](#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.IDocument-) | Crée un XForm qui duplique le contenu de la page. |
| [createNewForm](#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.engine.data.ITrailerable-com.aspose.pdf.Copier-) |  |
| [dispose](#dispose--) | Libère la mémoire |
| [freeMemory](#freeMemory--) | Efface les données en cache |
| [getBBox](#getBBox--) | Obtient la boîte englobante du formulaire. |
| [getContents](#getContents--) | Obtient les opérateurs du formulaire. |
| [getEngineObj](#getEngineObj--) | Interne uniquement |
| [getIT](#getIT--) | Obtient le IT du formulaire. Le IT du formulaire est un nom décrivant l'intention du XObject. |
| [getMatrix](#getMatrix--) | Obtient la matrice du formulaire. |
| [getName](#getName--) | Obtient le nom du formulaire. Le nom du formulaire est le nom utilisé pour référencer le formulaire dans le dictionnaire XObejct des ressources de la page. |
| [getOpi](#getOpi--) | Obtient l'Open Prepress Interface (OPI). |
| [getRectangle](#getRectangle--) | Obtient le rectangle du formulaire. |
| [getResources](#getResources--) | Renvoie les ressources du Form X-Object. Si le Form n'a pas de ressources et que allowCreate est vrai, les Resources seront créées automatiquement pour le formulaire. |
| [getResources](#getResources-boolean-) | Renvoie les ressources du Form X-Object |
| [getResourcesField](#getResourcesField--) | Obtient les ressources du Form XObject. |
| [getSubtype](#getSubtype--) | Obtient le sous-type du formulaire. |
| [setBBox](#setBBox-com.aspose.pdf.Rectangle-) | Définit la boîte englobante du formulaire. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Définit la matrice du formulaire. |
| [setName](#setName-java.lang.String-) | Définit le nom du formulaire. Le nom du formulaire est le nom utilisé pour référencer le formulaire dans le dictionnaire XObejct des ressources de la page. |

### close {#close--}
```
public final void close()
```

Libère la mémoire

### containsOwnResources {#containsOwnResources--}
```
public boolean containsOwnResources()
```

Renvoie True si contient ses propres ressources

**Returns:**
valeur booléenne

### createNewForm {#createNewForm-com.aspose.pdf.engine.data.ITrailerable-}
Crée un nouveau XForm dans le document.

### createNewForm {#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.IDocument-}
Crée un XForm qui duplique le contenu de la page.

### createNewForm {#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.engine.data.ITrailerable-com.aspose.pdf.Copier-}


### dispose {#dispose--}
```
public final void dispose()
```

Libère la mémoire

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

Efface les données en cache

### getBBox {#getBBox--}
```
public Rectangle getBBox()
```

Obtient la boîte englobante du formulaire.

**Returns:**
Rectangle

### getContents {#getContents--}
```
public OperatorCollection getContents()
```

Obtient les opérateurs du formulaire.

**Returns:**
Objet OperatorCollection

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

Interne uniquement

**Returns:**
Objet IPdfObject

### getIT {#getIT--}
```
public final String getIT()
```

Obtient le IT du formulaire. Le IT du formulaire est un nom décrivant l'intention du XObject.

**Returns:**
valeur String

### getMatrix {#getMatrix--}
```
public Matrix getMatrix()
```

Obtient la matrice du formulaire.

**Returns:**
Matrice

### getName {#getName--}
```
public String getName()
```

Obtient le nom du formulaire. Le nom du formulaire est le nom utilisé pour référencer le formulaire dans le dictionnaire XObejct des ressources de la page.

**Returns:**
Chaîne

### getOpi {#getOpi--}
```
public Opi getOpi()
```

Obtient l'Open Prepress Interface (OPI).

**Returns:**
Instance Opi

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtient le rectangle du formulaire.

**Returns:**
Rectangle

### getResources {#getResources--}
```
public Resources getResources()
```

Renvoie les ressources du Form X-Object. Si le Form n'a pas de ressources et que allowCreate est vrai, les Resources seront créées automatiquement pour le formulaire.

**Returns:**
Instance Resources

### getResources {#getResources-boolean-}
```
public final Resources getResources(boolean allowCreate)
```

Renvoie les ressources du Form X-Object

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| allowCreate |  | Si le Form n'a pas de ressources et que allowCreate est vrai, les Resources seront créées automatiquement pour le formulaire. |

**Returns:**
Instance Resources

### getResourcesField {#getResourcesField--}
```
public final Resources getResourcesField()
```

Obtient les ressources du Form XObject.

**Returns:**
Instance Resources. Si le Form n'a pas de ressources, les Resources seront créées automatiquement pour le formulaire.

### getSubtype {#getSubtype--}
```
public final String getSubtype()
```

Obtient le sous-type du formulaire.

**Returns:**
valeur String

### setBBox {#setBBox-com.aspose.pdf.Rectangle-}
Définit la boîte englobante du formulaire.

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
Définit la matrice du formulaire.

### setName {#setName-java.lang.String-}
Définit le nom du formulaire. Le nom du formulaire est le nom utilisé pour référencer le formulaire dans le dictionnaire XObejct des ressources de la page.
