---
title: "LinkElement"
linktitle: "LinkElement"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar Link-strukturelement i logisk struktur."
type: docs
weight: 70
url: /sv/java/com.aspose.pdf.tagged.logicalstructure.elements.ils/linkelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement

**All Implemented Interfaces:**
IAdjustPosition, ITextElement

```
public final class LinkElement extends AnnotationElement implements ITextElement , IAdjustPosition
```

Representerar Link-strukturelement i logisk struktur.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [LinkElement](#LinkElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | Justera position. |
| [getHyperlink](#getHyperlink--) | Hämtar eller anger hyperlänk för länkelementet. |
| [getStructureTextState](#getStructureTextState--) | Hämtar {@code /Aspose.Pdf.LogicalStructure.StructureTextState}-objektet för aktuellt element. Värde: {@code /Aspose.Pdf.LogicalStructure.StructureTextState}-objektet för aktuellt element. |
| [preSave](#preSave--) |  |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | Hämtar eller anger hyperlänk för länkelementet. |
| [setText](#setText-java.lang.String-) | Lägger till textinnehåll till aktuellt textelement. |

### LinkElement {#LinkElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}


### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
Justera position.

### getHyperlink {#getHyperlink--}
```
public final Hyperlink getHyperlink()
```

Hämtar eller anger hyperlänk för länkelementet.

**Returns:**
Hyperlänkinstans

### getStructureTextState {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```

Hämtar {@code /Aspose.Pdf.LogicalStructure.StructureTextState}-objektet för aktuellt element. Värde: {@code /Aspose.Pdf.LogicalStructure.StructureTextState}-objektet för aktuellt element.

**Returns:**
Värde: StructureTextState-objekt för textstruktur-elementet.

### preSave {#preSave--}
```
public void preSave()
```



### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
Hämtar eller anger hyperlänk för länkelementet.

### setText {#setText-java.lang.String-}
Lägger till textinnehåll till aktuellt textelement.
