---
title: "MCRElement"
linktitle: "MCRElement"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt ein markierten Inhaltsreferenzobjekt in der logischen Struktur dar."
type: docs
weight: 80
url: /de/java/com.aspose.pdf.tagged.logicalstructure.elements/mcrelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.MCRElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.MCRElement

```
public final class MCRElement extends Element
```

Stellt ein markierten Inhaltsreferenzobjekt in der logischen Struktur dar.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [Handler](#Handler) |  |

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MCRElement](#MCRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | Konstruktor |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getMCID](#getMCID--) | Ruft MCID des markierten Inhaltsreferenzobjekts ab. |
| [getPage](#getPage--) | Seiteninstanz abrufen |
| [preSave](#preSave--) |  |
| [setNewMCID](#setNewMCID-int-) | MCID-Wert abrufen |
| [setPage](#setPage-com.aspose.pdf.Page-) | Seiteninstanz festlegen |
| [tag](#tag-com.aspose.pdf.Annotation-) | Binden Sie ein Strukturelement an die Annotation. |
| [tag](#tag-com.aspose.pdf.Artifact-) | Binden Sie ein Strukturelement an das Artefakt. |
| [tag](#tag-com.aspose.pdf.operators.BDC-) | Binden Sie ein Strukturelement an den Inhaltsstrom-BDC-Operator. |
| [tag](#tag-com.aspose.pdf.XForm-) | Binden Sie ein Strukturelement an den Inhaltsstrom XForm. |
| [tag](#tag-com.aspose.pdf.XImage-) | Binden Sie ein Strukturelement an das XImage. |
| [toString](#toString--) | Gibt einen String zurück, der das aktuelle Objekt darstellt. |

### Handler {#Handler}
```
public com.aspose.pdf.tagged.helpers.logicalstructure.MCRElementHandler Handler
```



### MCRElement {#MCRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
Konstruktor

### getMCID {#getMCID--}
```
public final int getMCID()
```

Ruft MCID des markierten Inhaltsreferenzobjekts ab.

**Returns:**
MCID des markierten Inhaltsreferenzobjekts.

### getPage {#getPage--}
```
public final Page getPage()
```

Seiteninstanz abrufen

**Returns:**
Seiteninstanz

### preSave {#preSave--}
```
public void preSave()
```



### setNewMCID {#setNewMCID-int-}
```
public final void setNewMCID(int value)
```

MCID-Wert abrufen

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | MCID-Wert |

### setPage {#setPage-com.aspose.pdf.Page-}
Seiteninstanz festlegen

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
