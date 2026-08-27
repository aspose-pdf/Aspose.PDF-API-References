---
title: "StructureElement"
linktitle: "StructureElement"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Basisklasse für Strukturelemente in der logischen Struktur dar."
type: docs
weight: 110
url: /de/java/com.aspose.pdf.tagged.logicalstructure.elements/structureelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement

```
public abstract class StructureElement extends Element
```

Stellt eine Basisklasse für Strukturelemente in der logischen Struktur dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [changeParentElement](#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) | Ändern Sie das übergeordnete Element für das aktuelle Strukturelement. |
| [changeParentElement](#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-boolean-) | Ändern Sie das übergeordnete Element für das aktuelle Strukturelement. |
| [clearId](#clearId--) | ID für das Strukturelement löschen. |
| [generateId](#generateId--) | ID für das Strukturelement erzeugen. |
| [getActualText](#getActualText--) | Liest oder setzt den tatsächlichen Text für das Strukturelement. |
| [getAlternativeText](#getAlternativeText--) | Liest oder setzt den Alternativtext für das Strukturelement. |
| [getAttributes](#getAttributes--) | Liest {@code StructureAttributeCollection}-Objekt. |
| [getDefaultAttributeOwner](#getDefaultAttributeOwner--) | Liest {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard}-Objekt. Wert: {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard}-Objekt. |
| [getExpansionText](#getExpansionText--) | Liest oder setzt den Erweiterungstext für das Strukturelement. |
| [getID](#getID--) | Liest die ID für das Strukturelement. Wert: ID des Strukturelements. |
| [getLanguage](#getLanguage--) | Liest oder setzt die Sprache für das Strukturelement. |
| [getPage](#getPage--) | Liest die Seite, auf der einige oder alle Kind-Elemente gerendert werden. |
| [getS](#getS--) |  |
| [getStructureType](#getStructureType--) | Ermittelt den Typ des Strukturelements. |
| [getTitle](#getTitle--) | Liest oder setzt den Titel für das Strukturelement. |
| [remove](#remove--) | Entfernt: ein Element aus der Struktur, eine Referenz darauf vom übergeordneten Objekt, Referenzen darauf von Kindobjekten, das entsprechende Objekt aus dem Dokument. |
| [removeAndMoveItsChildObjectsToItsParent](#removeAndMoveItsChildObjectsToItsParent--) | Entfernt ein Element aus der Struktur, eine Referenz darauf vom übergeordneten Objekt, Referenzen darauf von Kindobjekten und das entsprechende Objekt aus dem Dokument. Fügt die Kindobjekte des entfernten Objekts in die frühere Kindobjektsammlung des übergeordneten Elements ein, beginnend am Index des entfernten Objekts. |
| [removeAndMoveItsChildObjectsToItsParent](#removeAndMoveItsChildObjectsToItsParent-boolean-) | Entfernt ein Element aus der Struktur, eine Referenz darauf vom übergeordneten Objekt, Referenzen darauf von Kindobjekten und das entsprechende Objekt aus dem Dokument. Fügt die Kindobjekte des entfernten Objekts in die frühere Kindobjektsammlung des übergeordneten Elements ein, beginnend am Index des entfernten Objekts. |
| [setActualText](#setActualText-java.lang.String-) | Liest oder setzt den tatsächlichen Text für das Strukturelement. |
| [setAlternativeText](#setAlternativeText-java.lang.String-) | Liest oder setzt den Alternativtext für das Strukturelement. |
| [setExpansionText](#setExpansionText-java.lang.String-) | Liest oder setzt den Erweiterungstext für das Strukturelement. |
| [setId](#setId-java.lang.String-) | Setzt die ID für das Strukturelement. |
| [setLanguage](#setLanguage-java.lang.String-) | Liest oder setzt die Sprache für das Strukturelement. |
| [setParentElement](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | set Parent Element |
| [setTag](#setTag-java.lang.String-) | Setzt ein benutzerdefiniertes Tag für das Strukturelement. |
| [setTitle](#setTitle-java.lang.String-) | Liest oder setzt den Titel für das Strukturelement. |
| [tag](#tag-com.aspose.pdf.Annotation-) | Binden Sie ein Strukturelement an die Annotation. |
| [tag](#tag-com.aspose.pdf.Artifact-) | Binden Sie ein Strukturelement an das Artefakt. |
| [tag](#tag-com.aspose.pdf.operators.BDC-) | Binden Sie ein Strukturelement an den Inhaltsstrom-BDC-Operator. |
| [tag](#tag-com.aspose.pdf.XForm-) | Binden Sie ein Strukturelement an den Inhaltsstrom XForm. |
| [tag](#tag-com.aspose.pdf.XImage-) | Binden Sie ein Strukturelement an das XImage. |
| [toString](#toString--) | Gibt einen String zurück, der das aktuelle Objekt darstellt. |

### changeParentElement {#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-}
Ändern Sie das übergeordnete Element für das aktuelle Strukturelement.

### changeParentElement {#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-boolean-}
Ändern Sie das übergeordnete Element für das aktuelle Strukturelement.

### clearId {#clearId--}
```
public final void clearId()
```

ID für das Strukturelement löschen.

### generateId {#generateId--}
```
public final void generateId()
```

ID für das Strukturelement erzeugen.

### getActualText {#getActualText--}
```
public final String getActualText()
```

Liest oder setzt den tatsächlichen Text für das Strukturelement.

**Returns:**
Wert: Tatsächlicher Text des Strukturelements.

### getAlternativeText {#getAlternativeText--}
```
public final String getAlternativeText()
```

Liest oder setzt den Alternativtext für das Strukturelement.

**Returns:**
Wert: Alternativtext des Strukturelements.

### getAttributes {#getAttributes--}
```
public final StructureAttributeCollection getAttributes()
```

Liest {@code StructureAttributeCollection}-Objekt.

**Returns:**
{@code StructureAttributeCollection} Objekt.

### getDefaultAttributeOwner {#getDefaultAttributeOwner--}
```
public final AttributeOwnerStandard getDefaultAttributeOwner()
```

Liest {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard}-Objekt. Wert: {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard}-Objekt.

**Returns:**
AttributeOwnerStandard-Instanz

### getExpansionText {#getExpansionText--}
```
public final String getExpansionText()
```

Liest oder setzt den Erweiterungstext für das Strukturelement.

**Returns:**
Wert: Erweiterungstext des Strukturelements.

### getID {#getID--}
```
public final String getID()
```

Liest die ID für das Strukturelement. Wert: ID des Strukturelements.

**Returns:**
String Wert

### getLanguage {#getLanguage--}
```
public final String getLanguage()
```

Liest oder setzt die Sprache für das Strukturelement.

**Returns:**
Wert: Sprache des Strukturelements.

### getPage {#getPage--}
```
public final Page getPage()
```

Liest die Seite, auf der einige oder alle Kind-Elemente gerendert werden.

**Returns:**
Seiteninstanz

### getS {#getS--}
```
public final com.aspose.pdf.engine.data.IPdfName getS()
```



### getStructureType {#getStructureType--}
```
public final StructureTypeStandard getStructureType()
```

Ermittelt den Typ des Strukturelements.

**Returns:**
Wert: {@code StructureTypeStandard} Objekt des Strukturelements.

### getTitle {#getTitle--}
```
public final String getTitle()
```

Liest oder setzt den Titel für das Strukturelement.

**Returns:**
Wert: Titel des Strukturelements.

### remove {#remove--}
```
public final void remove()
```

Entfernt: ein Element aus der Struktur, eine Referenz darauf vom übergeordneten Objekt, Referenzen darauf von Kindobjekten, das entsprechende Objekt aus dem Dokument.

### removeAndMoveItsChildObjectsToItsParent {#removeAndMoveItsChildObjectsToItsParent--}
```
public final void removeAndMoveItsChildObjectsToItsParent()
```

Entfernt ein Element aus der Struktur, eine Referenz darauf vom übergeordneten Objekt, Referenzen darauf von Kindobjekten und das entsprechende Objekt aus dem Dokument. Fügt die Kindobjekte des entfernten Objekts in die frühere Kindobjektsammlung des übergeordneten Elements ein, beginnend am Index des entfernten Objekts.

### removeAndMoveItsChildObjectsToItsParent {#removeAndMoveItsChildObjectsToItsParent-boolean-}
```
public final void removeAndMoveItsChildObjectsToItsParent(boolean checkIfChildObjectsCanBeMovedToParent)
```

Entfernt ein Element aus der Struktur, eine Referenz darauf vom übergeordneten Objekt, Referenzen darauf von Kindobjekten und das entsprechende Objekt aus dem Dokument. Fügt die Kindobjekte des entfernten Objekts in die frühere Kindobjektsammlung des übergeordneten Elements ein, beginnend am Index des entfernten Objekts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| checkIfChildObjectsCanBeMovedToParent |  | Prüft, ob Kindobjekte des entfernten Objekts in die Kindobjektsammlung des übergeordneten Elements eingefügt werden können. |

### setActualText {#setActualText-java.lang.String-}
Liest oder setzt den tatsächlichen Text für das Strukturelement.

### setAlternativeText {#setAlternativeText-java.lang.String-}
Liest oder setzt den Alternativtext für das Strukturelement.

### setExpansionText {#setExpansionText-java.lang.String-}
Liest oder setzt den Erweiterungstext für das Strukturelement.

### setId {#setId-java.lang.String-}
Setzt die ID für das Strukturelement.

### setLanguage {#setLanguage-java.lang.String-}
Liest oder setzt die Sprache für das Strukturelement.

### setParentElement {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
set Parent Element

### setTag {#setTag-java.lang.String-}
Setzt ein benutzerdefiniertes Tag für das Strukturelement.

### setTitle {#setTitle-java.lang.String-}
Liest oder setzt den Titel für das Strukturelement.

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
