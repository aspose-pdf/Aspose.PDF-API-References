---
title: "Element"
linktitle: "Element"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en basklass för element i logisk struktur."
type: docs
weight: 10
url: /sv/java/com.aspose.pdf.tagged.logicalstructure.elements/element/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element

```
public abstract class Element extends Object
```

Representerar en basklass för element i logisk struktur.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [appendChild](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | Lägg till {@code /Aspose.Pdf.LogicalStructure.Element} i samlingen av barn. |
| [appendChild](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) | Lägg till {@code /Aspose.Pdf.LogicalStructure.Element} i samlingen av barn. |
| [clearChilds](#clearChilds--) | Rensa alla barn. |
| [findElements](#findElements-java.lang.Class-) | Hitta element av en given typ |
| [findElements](#findElements-java.lang.Class-boolean-) | Hitta element av en given typ |
| [getChildElements](#getChildElements--) | Hämtar samling av barn av {@code Element}-objekt. |
| [getElementEngine](#getElementEngine--) | Hämta förälderelement. |
| [getParentElement](#getParentElement--) | Hämtar föräldrasamling av {@code Element}-objekt. |
| [getTaggedContent](#getTaggedContent--) |  |
| [getTrailer](#getTrailer--) | Intern metod |
| [insertChild](#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-) | Infoga {@code /Aspose.Pdf.LogicalStructure.Element} i samlingen av barn på angivet index. |
| [insertChild](#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-boolean-) | Infoga {@code /Aspose.Pdf.LogicalStructure.Element} i samlingen av barn på angivet index. |
| [preSave](#preSave--) |  |
| [removeChild](#removeChild-int-) | Ta bort barn vid. |
| [setParentElement](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
| [tag](#tag-com.aspose.pdf.Annotation-) | Koppla ett strukturelement till Annotation. |
| [tag](#tag-com.aspose.pdf.Artifact-) | Koppla ett strukturelement till Artifact. |
| [tag](#tag-com.aspose.pdf.operators.BDC-) | Koppla ett strukturelement till innehållsströmmen BDC-operator. |
| [tag](#tag-com.aspose.pdf.XForm-) | Koppla ett strukturelement till innehållsströmmen XForm. |
| [tag](#tag-com.aspose.pdf.XImage-) | Koppla ett strukturelement till XImage. |
| [toString](#toString--) | Returnerar en sträng som representerar det aktuella objektet. |

### appendChild {#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
Lägg till {@code /Aspose.Pdf.LogicalStructure.Element} i samlingen av barn.

### appendChild {#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
Lägg till {@code /Aspose.Pdf.LogicalStructure.Element} i samlingen av barn.

### clearChilds {#clearChilds--}
```
public final void clearChilds()
```

Rensa alla barn.

### findElements {#findElements-java.lang.Class-}
Hitta element av en given typ

### findElements {#findElements-java.lang.Class-boolean-}
Hitta element av en given typ

### getChildElements {#getChildElements--}
```
public final ElementList getChildElements()
```

Hämtar samling av barn av {@code Element}-objekt.

**Returns:**
Värde: Samling av barn av {@code Element}-objekt.

### getElementEngine {#getElementEngine--}
```
public final ElementPdfEngine getElementEngine()
```

Hämta förälderelement.

**Returns:**
Värde: Förälderelement.

### getParentElement {#getParentElement--}
```
public final Element getParentElement()
```

Hämtar föräldrasamling av {@code Element}-objekt.

**Returns:**
Värde: Föräldrasamling av {@code Element}-objekt.

### getTaggedContent {#getTaggedContent--}
```
public final ITaggedContent getTaggedContent()
```



### getTrailer {#getTrailer--}
```
public final com.aspose.pdf.engine.data.ITrailerable getTrailer()
```

Intern metod

**Returns:**
Internt element

### insertChild {#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-}
Infoga {@code /Aspose.Pdf.LogicalStructure.Element} i samlingen av barn på angivet index.

### insertChild {#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-boolean-}
Infoga {@code /Aspose.Pdf.LogicalStructure.Element} i samlingen av barn på angivet index.

### preSave {#preSave--}
```
public void preSave()
```



### removeChild {#removeChild-int-}
```
public final void removeChild(int index)
```

Ta bort barn vid.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Index för barn-element |

### setParentElement {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}


### tag {#tag-com.aspose.pdf.Annotation-}
Koppla ett strukturelement till Annotation.

### tag {#tag-com.aspose.pdf.Artifact-}
Koppla ett strukturelement till Artifact.

### tag {#tag-com.aspose.pdf.operators.BDC-}
Koppla ett strukturelement till innehållsströmmen BDC-operator.

### tag {#tag-com.aspose.pdf.XForm-}
Koppla ett strukturelement till innehållsströmmen XForm.

### tag {#tag-com.aspose.pdf.XImage-}
Koppla ett strukturelement till XImage.

### toString {#toString--}
```
public String toString()
```

Returnerar en sträng som representerar det aktuella objektet.

**Returns:**
Sträng som representerar det aktuella objektet.
