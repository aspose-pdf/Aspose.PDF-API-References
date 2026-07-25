---
title: "BLSTextElement"
linktitle: "BLSTextElement"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une classe de base pour les éléments de structure de texte de niveau bloc dans la structure logique."
type: docs
weight: 20
url: /fr/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/blstextelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSTextElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSTextElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSTextElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSTextElement

**All Implemented Interfaces:**
IAdjustPosition, ITextElement

```
public abstract class BLSTextElement extends BLSElement implements ITextElement , IAdjustPosition
```

Représente une classe de base pour les éléments de structure de texte de niveau bloc dans la structure logique.

## Méthodes

| Méthode | Description |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | Ajuster la position. |
| [getStructureTextState](#getStructureTextState--) | Obtient l'objet {@code StructureTextState} pour l'élément actuel. Valeur : l'objet {@code structureTextState} pour l'élément actuel. |
| [getTextFragment](#getTextFragment--) |  |
| [setText](#setText-java.lang.String-) | Ajoute du contenu texte à l'élément texte actuel. |

### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
Ajuster la position.

### getStructureTextState {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```

Obtient l'objet {@code StructureTextState} pour l'élément actuel. Valeur : l'objet {@code structureTextState} pour l'élément actuel.

**Returns:**
Valeur : objet StructureTextState pour l'élément de structure de texte.

### getTextFragment {#getTextFragment--}
```
public final TextFragment getTextFragment()
```



### setText {#setText-java.lang.String-}
Ajoute du contenu texte à l'élément texte actuel.
