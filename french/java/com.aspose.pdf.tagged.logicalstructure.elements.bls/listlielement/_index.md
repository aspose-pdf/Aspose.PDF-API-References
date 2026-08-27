---
title: "ListLIElement"
linktitle: "ListLIElement"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente l'élément de structure LI dans la structure logique de la liste."
type: docs
weight: 110
url: /fr/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/listlielement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement

**All Implemented Interfaces:**
ITociElement

```
public final class ListLIElement extends ListChildElement implements ITociElement
```

Représente l'élément de structure LI dans la structure logique de la liste.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ListLIElement](#ListLIElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |

## Méthodes

| Méthode | Description |
| --- | --- |
| [addRef](#addRef-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) | Ajoute une référence à l'{@link StructureElement} spécifié au sein de cet élément d'Item du Table des matières (TOCI). Ceci est généralement utilisé lorsque {@code ListLIElement} sert d'en-tête de TOC dans des tables des matières imbriquées. |
| [getGetElement](#getGetElement--) | Obtient l'élément PDF sous-jacent qui représente cette structure TOCI. |
| [preSave](#preSave--) |  |

### ListLIElement {#ListLIElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}


### addRef {#addRef-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-}
Ajoute une référence à l'{@link StructureElement} spécifié au sein de cet élément d'Item du Table des matières (TOCI). Ceci est généralement utilisé lorsque {@code ListLIElement} sert d'en-tête de TOC dans des tables des matières imbriquées.

### getGetElement {#getGetElement--}
```
public final StructureElement getGetElement()
```

Obtient l'élément PDF sous-jacent qui représente cette structure TOCI.

**Returns:**
L'élément qui forme la représentation structurelle de cette entrée de table des matières.

### preSave {#preSave--}
```
public void preSave()
```
