---
title: "Element"
linktitle: "Element"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Basisklasse für ein Element in der logischen Struktur dar."
type: docs
weight: 10
url: /de/java/com.aspose.pdf.tagged.logicalstructure.elements/element/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element

```
public abstract class Element extends Object
```

Stellt eine Basisklasse für ein Element in der logischen Struktur dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [appendChild](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | Fügt {@code /Aspose.Pdf.LogicalStructure.Element} zur Kindersammlung hinzu. |
| [appendChild](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) | Fügt {@code /Aspose.Pdf.LogicalStructure.Element} zur Kindersammlung hinzu. |
| [clearChilds](#clearChilds--) | Alle Kinder löschen. |
| [findElements](#findElements-java.lang.Class-) | Elemente eines bestimmten Typs finden. |
| [findElements](#findElements-java.lang.Class-boolean-) | Elemente eines bestimmten Typs finden. |
| [getChildElements](#getChildElements--) | Liest die Kindersammlung von {@code Element}-Objekten. |
| [getElementEngine](#getElementEngine--) | Lese übergeordnetes Element. |
| [getParentElement](#getParentElement--) | Liest die übergeordnete Sammlung von {@code Element}-Objekten. |
| [getTaggedContent](#getTaggedContent--) |  |
| [getTrailer](#getTrailer--) | Interne Methode |
| [insertChild](#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-) | Fügt {@code /Aspose.Pdf.LogicalStructure.Element} an der angegebenen Position in die Kindersammlung ein. |
| [insertChild](#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-boolean-) | Fügt {@code /Aspose.Pdf.LogicalStructure.Element} an der angegebenen Position in die Kindersammlung ein. |
| [preSave](#preSave--) |  |
| [removeChild](#removeChild-int-) | Kind an Position entfernen. |
| [setParentElement](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
| [tag](#tag-com.aspose.pdf.Annotation-) | Binden Sie ein Strukturelement an die Annotation. |
| [tag](#tag-com.aspose.pdf.Artifact-) | Binden Sie ein Strukturelement an das Artefakt. |
| [tag](#tag-com.aspose.pdf.operators.BDC-) | Binden Sie ein Strukturelement an den Inhaltsstrom-BDC-Operator. |
| [tag](#tag-com.aspose.pdf.XForm-) | Binden Sie ein Strukturelement an den Inhaltsstrom XForm. |
| [tag](#tag-com.aspose.pdf.XImage-) | Binden Sie ein Strukturelement an das XImage. |
| [toString](#toString--) | Gibt einen String zurück, der das aktuelle Objekt darstellt. |

### appendChild {#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
Fügt {@code /Aspose.Pdf.LogicalStructure.Element} zur Kindersammlung hinzu.

### appendChild {#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
Fügt {@code /Aspose.Pdf.LogicalStructure.Element} zur Kindersammlung hinzu.

### clearChilds {#clearChilds--}
```
public final void clearChilds()
```

Alle Kinder löschen.

### findElements {#findElements-java.lang.Class-}
Elemente eines bestimmten Typs finden.

### findElements {#findElements-java.lang.Class-boolean-}
Elemente eines bestimmten Typs finden.

### getChildElements {#getChildElements--}
```
public final ElementList getChildElements()
```

Liest die Kindersammlung von {@code Element}-Objekten.

**Returns:**
Wert: Kindersammlung von {@code Element}-Objekten.

### getElementEngine {#getElementEngine--}
```
public final ElementPdfEngine getElementEngine()
```

Lese übergeordnetes Element.

**Returns:**
Wert: Übergeordnetes Element.

### getParentElement {#getParentElement--}
```
public final Element getParentElement()
```

Liest die übergeordnete Sammlung von {@code Element}-Objekten.

**Returns:**
Wert: Übergeordnete Sammlung von {@code Element}-Objekten.

### getTaggedContent {#getTaggedContent--}
```
public final ITaggedContent getTaggedContent()
```



### getTrailer {#getTrailer--}
```
public final com.aspose.pdf.engine.data.ITrailerable getTrailer()
```

Interne Methode

**Returns:**
Internes Element

### insertChild {#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-}
Fügt {@code /Aspose.Pdf.LogicalStructure.Element} an der angegebenen Position in die Kindersammlung ein.

### insertChild {#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-boolean-}
Fügt {@code /Aspose.Pdf.LogicalStructure.Element} an der angegebenen Position in die Kindersammlung ein.

### preSave {#preSave--}
```
public void preSave()
```



### removeChild {#removeChild-int-}
```
public final void removeChild(int index)
```

Kind an Position entfernen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | Index des Kindelements. |

### setParentElement {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}


### tag {#tag-com.aspose.pdf.Annotation-}
Binden Sie ein Strukturelement an die Annotation.

### tag {#tag-com.aspose.pdf.Artifact-}
Binden Sie ein Strukturelement an das Artefakt.

### tag {#tag-com.aspose.pdf.operators.BDC-}
Binden Sie ein Strukturelement an den Inhaltsstrom-BDC-Operator.

### tag {#tag-com.aspose.pdf.XForm-}
Binden Sie ein Strukturelement an den Inhaltsstrom XForm.

### tag {#tag-com.aspose.pdf.XImage-}
Binden Sie ein Strukturelement an das XImage.

### toString {#toString--}
```
public String toString()
```

Gibt einen String zurück, der das aktuelle Objekt darstellt.

**Returns:**
String, der das aktuelle Objekt darstellt.
