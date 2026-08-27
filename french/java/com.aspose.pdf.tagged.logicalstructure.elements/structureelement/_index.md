---
title: "StructureElement"
linktitle: "StructureElement"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une classe de base pour les éléments de structure dans la structure logique."
type: docs
weight: 110
url: /fr/java/com.aspose.pdf.tagged.logicalstructure.elements/structureelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement

```
public abstract class StructureElement extends Element
```

Représente une classe de base pour les éléments de structure dans la structure logique.

## Méthodes

| Méthode | Description |
| --- | --- |
| [changeParentElement](#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) | Modifier l'élément parent de l'élément de structure actuel |
| [changeParentElement](#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-boolean-) | Modifier l'élément parent de l'élément de structure actuel |
| [clearId](#clearId--) | Effacer l'ID de l'élément de structure. |
| [generateId](#generateId--) | Générer l'ID de l'élément de structure. |
| [getActualText](#getActualText--) | Obtient ou définit le texte réel de l'élément de structure. |
| [getAlternativeText](#getAlternativeText--) | Obtient ou définit le texte alternatif de l'élément de structure. |
| [getAttributes](#getAttributes--) | Obtient l'objet {@code StructureAttributeCollection}. |
| [getDefaultAttributeOwner](#getDefaultAttributeOwner--) | Obtient l'objet {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard}. Valeur : {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard}. |
| [getExpansionText](#getExpansionText--) | Obtient ou définit le texte d'expansion de l'élément de structure. |
| [getID](#getID--) | Obtient l'ID de l'élément de structure. Valeur : ID de l'élément de structure. |
| [getLanguage](#getLanguage--) | Obtient ou définit la langue de l'élément de structure. |
| [getPage](#getPage--) | Obtient la page sur laquelle certains ou tous les éléments enfants seront rendus. |
| [getS](#getS--) |  |
| [getStructureType](#getStructureType--) | Obtient le type de l'élément de structure. |
| [getTitle](#getTitle--) | Obtient ou définit le titre de l'élément de structure. |
| [remove](#remove--) | Supprime : un élément de la structure, une référence à celui‑ci depuis l'objet parent, des références à celui‑ci depuis les objets enfants, l'objet correspondant du document. |
| [removeAndMoveItsChildObjectsToItsParent](#removeAndMoveItsChildObjectsToItsParent--) | Supprime un élément de la structure, une référence à celui‑ci depuis l'objet parent, des références à celui‑ci depuis les objets enfants, et l'objet correspondant du document. Insère les objets enfants de l'élément supprimé dans la collection des objets enfants de son ancien parent à partir de l'index de l'élément supprimé. |
| [removeAndMoveItsChildObjectsToItsParent](#removeAndMoveItsChildObjectsToItsParent-boolean-) | Supprime un élément de la structure, une référence à celui‑ci depuis l'objet parent, des références à celui‑ci depuis les objets enfants, et l'objet correspondant du document. Insère les objets enfants de l'élément supprimé dans la collection des objets enfants de son ancien parent à partir de l'index de l'élément supprimé. |
| [setActualText](#setActualText-java.lang.String-) | Obtient ou définit le texte réel de l'élément de structure. |
| [setAlternativeText](#setAlternativeText-java.lang.String-) | Obtient ou définit le texte alternatif de l'élément de structure. |
| [setExpansionText](#setExpansionText-java.lang.String-) | Obtient ou définit le texte d'expansion de l'élément de structure. |
| [setId](#setId-java.lang.String-) | Définit l'ID de l'élément de structure. |
| [setLanguage](#setLanguage-java.lang.String-) | Obtient ou définit la langue de l'élément de structure. |
| [setParentElement](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | définir l'élément parent |
| [setTag](#setTag-java.lang.String-) | Définit la balise personnalisée de l'élément de structure. |
| [setTitle](#setTitle-java.lang.String-) | Obtient ou définit le titre de l'élément de structure. |
| [tag](#tag-com.aspose.pdf.Annotation-) | Lier un élément de structure à l'Annotation. |
| [tag](#tag-com.aspose.pdf.Artifact-) | Lier un élément de structure à l'Artifact. |
| [tag](#tag-com.aspose.pdf.operators.BDC-) | Lier un élément de structure à l'opérateur BDC du flux de contenu. |
| [tag](#tag-com.aspose.pdf.XForm-) | Lier un élément de structure au XForm du flux de contenu. |
| [tag](#tag-com.aspose.pdf.XImage-) | Lier un élément de structure au XImage. |
| [toString](#toString--) | Renvoie une chaîne qui représente l'objet actuel. |

### changeParentElement {#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-}
Modifier l'élément parent de l'élément de structure actuel

### changeParentElement {#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-boolean-}
Modifier l'élément parent de l'élément de structure actuel

### clearId {#clearId--}
```
public final void clearId()
```

Effacer l'ID de l'élément de structure.

### generateId {#generateId--}
```
public final void generateId()
```

Générer l'ID de l'élément de structure.

### getActualText {#getActualText--}
```
public final String getActualText()
```

Obtient ou définit le texte réel de l'élément de structure.

**Returns:**
Valeur : texte réel de l'élément de structure.

### getAlternativeText {#getAlternativeText--}
```
public final String getAlternativeText()
```

Obtient ou définit le texte alternatif de l'élément de structure.

**Returns:**
Valeur : texte alternatif de l'élément de structure.

### getAttributes {#getAttributes--}
```
public final StructureAttributeCollection getAttributes()
```

Obtient l'objet {@code StructureAttributeCollection}.

**Returns:**
{@code StructureAttributeCollection} objet.

### getDefaultAttributeOwner {#getDefaultAttributeOwner--}
```
public final AttributeOwnerStandard getDefaultAttributeOwner()
```

Obtient l'objet {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard}. Valeur : {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard}.

**Returns:**
Instance d'AttributeOwnerStandard.

### getExpansionText {#getExpansionText--}
```
public final String getExpansionText()
```

Obtient ou définit le texte d'expansion de l'élément de structure.

**Returns:**
Valeur : texte d'expansion de l'élément de structure.

### getID {#getID--}
```
public final String getID()
```

Obtient l'ID de l'élément de structure. Valeur : ID de l'élément de structure.

**Returns:**
valeur String

### getLanguage {#getLanguage--}
```
public final String getLanguage()
```

Obtient ou définit la langue de l'élément de structure.

**Returns:**
Valeur : langue de l'élément de structure.

### getPage {#getPage--}
```
public final Page getPage()
```

Obtient la page sur laquelle certains ou tous les éléments enfants seront rendus.

**Returns:**
Instance de page

### getS {#getS--}
```
public final com.aspose.pdf.engine.data.IPdfName getS()
```



### getStructureType {#getStructureType--}
```
public final StructureTypeStandard getStructureType()
```

Obtient le type de l'élément de structure.

**Returns:**
Valeur : objet {@code StructureTypeStandard} de l'élément de structure.

### getTitle {#getTitle--}
```
public final String getTitle()
```

Obtient ou définit le titre de l'élément de structure.

**Returns:**
Valeur : titre de l'élément de structure.

### remove {#remove--}
```
public final void remove()
```

Supprime : un élément de la structure, une référence à celui‑ci depuis l'objet parent, des références à celui‑ci depuis les objets enfants, l'objet correspondant du document.

### removeAndMoveItsChildObjectsToItsParent {#removeAndMoveItsChildObjectsToItsParent--}
```
public final void removeAndMoveItsChildObjectsToItsParent()
```

Supprime un élément de la structure, une référence à celui‑ci depuis l'objet parent, des références à celui‑ci depuis les objets enfants, et l'objet correspondant du document. Insère les objets enfants de l'élément supprimé dans la collection des objets enfants de son ancien parent à partir de l'index de l'élément supprimé.

### removeAndMoveItsChildObjectsToItsParent {#removeAndMoveItsChildObjectsToItsParent-boolean-}
```
public final void removeAndMoveItsChildObjectsToItsParent(boolean checkIfChildObjectsCanBeMovedToParent)
```

Supprime un élément de la structure, une référence à celui‑ci depuis l'objet parent, des références à celui‑ci depuis les objets enfants, et l'objet correspondant du document. Insère les objets enfants de l'élément supprimé dans la collection des objets enfants de son ancien parent à partir de l'index de l'élément supprimé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| checkIfChildObjectsCanBeMovedToParent |  | Vérifier si les objets enfants de l'élément supprimé peuvent être insérés dans la collection des objets enfants de son parent. |

### setActualText {#setActualText-java.lang.String-}
Obtient ou définit le texte réel de l'élément de structure.

### setAlternativeText {#setAlternativeText-java.lang.String-}
Obtient ou définit le texte alternatif de l'élément de structure.

### setExpansionText {#setExpansionText-java.lang.String-}
Obtient ou définit le texte d'expansion de l'élément de structure.

### setId {#setId-java.lang.String-}
Définit l'ID de l'élément de structure.

### setLanguage {#setLanguage-java.lang.String-}
Obtient ou définit la langue de l'élément de structure.

### setParentElement {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
définir l'élément parent

### setTag {#setTag-java.lang.String-}
Définit la balise personnalisée de l'élément de structure.

### setTitle {#setTitle-java.lang.String-}
Obtient ou définit le titre de l'élément de structure.

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
