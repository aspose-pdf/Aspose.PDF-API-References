---
title: "Élément"
linktitle: "Élément"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une classe de base pour un élément dans la structure logique."
type: docs
weight: 10
url: /fr/java/com.aspose.pdf.tagged.logicalstructure.elements/element/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element

```
public abstract class Element extends Object
```

Représente une classe de base pour un élément dans la structure logique.

## Méthodes

| Méthode | Description |
| --- | --- |
| [appendChild](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | Ajoute {@code /Aspose.Pdf.LogicalStructure.Element} à la collection d'enfants. |
| [appendChild](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) | Ajoute {@code /Aspose.Pdf.LogicalStructure.Element} à la collection d'enfants. |
| [clearChilds](#clearChilds--) | Efface tous les enfants. |
| [findElements](#findElements-java.lang.Class-) | Trouve les éléments d'un type donné |
| [findElements](#findElements-java.lang.Class-boolean-) | Trouve les éléments d'un type donné |
| [getChildElements](#getChildElements--) | Obtient la collection d'enfants d'objets {@code Element}. |
| [getElementEngine](#getElementEngine--) | Obtient l'élément parent. |
| [getParentElement](#getParentElement--) | Obtient la collection parent d'objets {@code Element}. |
| [getTaggedContent](#getTaggedContent--) |  |
| [getTrailer](#getTrailer--) | Méthode interne |
| [insertChild](#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-) | Insère {@code /Aspose.Pdf.LogicalStructure.Element} dans la collection d'enfants à l'index spécifié. |
| [insertChild](#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-boolean-) | Insère {@code /Aspose.Pdf.LogicalStructure.Element} dans la collection d'enfants à l'index spécifié. |
| [preSave](#preSave--) |  |
| [removeChild](#removeChild-int-) | Supprime l'enfant à. |
| [setParentElement](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
| [tag](#tag-com.aspose.pdf.Annotation-) | Lier un élément de structure à l'Annotation. |
| [tag](#tag-com.aspose.pdf.Artifact-) | Lier un élément de structure à l'Artifact. |
| [tag](#tag-com.aspose.pdf.operators.BDC-) | Lier un élément de structure à l'opérateur BDC du flux de contenu. |
| [tag](#tag-com.aspose.pdf.XForm-) | Lier un élément de structure au XForm du flux de contenu. |
| [tag](#tag-com.aspose.pdf.XImage-) | Lier un élément de structure au XImage. |
| [toString](#toString--) | Renvoie une chaîne qui représente l'objet actuel. |

### appendChild {#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
Ajoute {@code /Aspose.Pdf.LogicalStructure.Element} à la collection d'enfants.

### appendChild {#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
Ajoute {@code /Aspose.Pdf.LogicalStructure.Element} à la collection d'enfants.

### clearChilds {#clearChilds--}
```
public final void clearChilds()
```

Efface tous les enfants.

### findElements {#findElements-java.lang.Class-}
Trouve les éléments d'un type donné

### findElements {#findElements-java.lang.Class-boolean-}
Trouve les éléments d'un type donné

### getChildElements {#getChildElements--}
```
public final ElementList getChildElements()
```

Obtient la collection d'enfants d'objets {@code Element}.

**Returns:**
Valeur: collection d'enfants d'objets {@code Element}.

### getElementEngine {#getElementEngine--}
```
public final ElementPdfEngine getElementEngine()
```

Obtient l'élément parent.

**Returns:**
Valeur: élément parent.

### getParentElement {#getParentElement--}
```
public final Element getParentElement()
```

Obtient la collection parent d'objets {@code Element}.

**Returns:**
Valeur: collection parent d'objets {@code Element}.

### getTaggedContent {#getTaggedContent--}
```
public final ITaggedContent getTaggedContent()
```



### getTrailer {#getTrailer--}
```
public final com.aspose.pdf.engine.data.ITrailerable getTrailer()
```

Méthode interne

**Returns:**
Élément interne

### insertChild {#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-}
Insère {@code /Aspose.Pdf.LogicalStructure.Element} dans la collection d'enfants à l'index spécifié.

### insertChild {#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-boolean-}
Insère {@code /Aspose.Pdf.LogicalStructure.Element} dans la collection d'enfants à l'index spécifié.

### preSave {#preSave--}
```
public void preSave()
```



### removeChild {#removeChild-int-}
```
public final void removeChild(int index)
```

Supprime l'enfant à.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | Index de l'élément enfant. |

### setParentElement {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}


### tag {#tag-com.aspose.pdf.Annotation-}
Lier un élément de structure à l'Annotation.

### tag {#tag-com.aspose.pdf.Artifact-}
Lier un élément de structure à l'Artifact.

### tag {#tag-com.aspose.pdf.operators.BDC-}
Lier un élément de structure à l'opérateur BDC du flux de contenu.

### tag {#tag-com.aspose.pdf.XForm-}
Lier un élément de structure au XForm du flux de contenu.

### tag {#tag-com.aspose.pdf.XImage-}
Lier un élément de structure au XImage.

### toString {#toString--}
```
public String toString()
```

Renvoie une chaîne qui représente l'objet actuel.

**Returns:**
Chaîne qui représente l'objet actuel.
