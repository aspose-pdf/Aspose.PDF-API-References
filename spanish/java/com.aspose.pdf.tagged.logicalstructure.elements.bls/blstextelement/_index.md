---
title: "BLSTextElement"
linktitle: "BLSTextElement"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una clase base para elementos estructurales de texto de nivel de bloque en la estructura lógica."
type: docs
weight: 20
url: /es/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/blstextelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSTextElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSTextElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSTextElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSTextElement

**All Implemented Interfaces:**
IAdjustPosition, ITextElement

```
public abstract class BLSTextElement extends BLSElement implements ITextElement , IAdjustPosition
```

Representa una clase base para elementos estructurales de texto de nivel de bloque en la estructura lógica.

## Métodos

| Método | Descripción |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | Ajustar posición. |
| [getStructureTextState](#getStructureTextState--) | Obtiene el objeto {@code StructureTextState} para el elemento actual. Valor: objeto {@code structureTextState} para el elemento actual. |
| [getTextFragment](#getTextFragment--) |  |
| [setText](#setText-java.lang.String-) | Añade contenido de texto al elemento de texto actual. |

### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
Ajustar posición.

### getStructureTextState {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```

Obtiene el objeto {@code StructureTextState} para el elemento actual. Valor: objeto {@code structureTextState} para el elemento actual.

**Returns:**
Valor: objeto StructureTextState para el elemento de estructura de texto.

### getTextFragment {#getTextFragment--}
```
public final TextFragment getTextFragment()
```



### setText {#setText-java.lang.String-}
Añade contenido de texto al elemento de texto actual.
