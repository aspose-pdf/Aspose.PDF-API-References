---
title: "HtmlSaveOptions.HtmlImageSavingInfo"
linktitle: "HtmlSaveOptions.HtmlImageSavingInfo"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Diese Klasse repräsentiert einen Datensatz, der sich auf das Speichern von externen Bilddateien während der PDF-zu-HTML-Konvertierung bezieht."
type: docs
weight: 2070
url: /de/java/com.aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions.ResourceSavingInfo com.aspose.pdf.HtmlSaveOptions.HtmlImageSavingInfo, com.aspose.pdf.SaveOptions.ResourceSavingInfo, com.aspose.pdf.HtmlSaveOptions.HtmlImageSavingInfo

```
public static class HtmlSaveOptions.HtmlImageSavingInfo extends SaveOptions.ResourceSavingInfo
```

Diese Klasse repräsentiert einen Datensatz, der sich auf das Speichern von externen Bilddateien während der PDF-zu-HTML-Konvertierung bezieht.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [HtmlImageSavingInfo](#HtmlImageSavingInfo--) | erstellt eine neue Instanz von HtmlImageSavingInfo |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getHtmlHostPageNumber](#getHtmlHostPageNumber--) | Gibt dem benutzerdefinierten Code an, zu welcher Seite des erzeugten Satzes von HTML‑Dateien das gespeicherte Bild gehört. Ist das Aufteilen in Seiten deaktiviert, enthält dieser Wert stets '1', da in diesem Fall nur eine HTML‑Seite erzeugt wird. |
| [getImageType](#getImageType--) | Stellt den Typ des im HTML referenzierten gespeicherten Bildes dar. Wird vom Konverter gesetzt und kann im benutzerdefinierten Code verwendet werden, um zu entscheiden, was zu tun ist. |
| [getParentType](#getParentType--) | Das gespeicherte Bild kann zur HTML‑Selbst gehören oder aus einem in HTML eingebetteten SVG extrahiert werden. Diese Eigenschaft kann dem benutzerdefinierten Code mitteilen, welcher Elterntyp des verarbeiteten Bildes vorliegt. Sie wird vom Konverter gesetzt und kann im benutzerdefinierten Code verwendet werden, um zu entscheiden, was mit diesem Bild geschehen soll (z. B. kann der benutzerdefinierte Code bestimmen, wo das Bild gespeichert wird oder wie es im Inhalt des Elternteils referenziert werden muss). |
| [getPdfHostPageNumber](#getPdfHostPageNumber--) | Gibt dem benutzerdefinierten Code an, zu welcher Seite des ursprünglichen PDF‑Dokuments das gespeicherte Bild gehört. Da möglicherweise nicht alle Seiten des Originaldokuments gespeichert werden, gibt dieser Wert die Host‑Seitenzahl im ursprünglichen PDF an. Ist die Original‑Seitenzahl aus irgendeinem Grund unbekannt, wird stets '1' zurückgegeben. |
| [setHtmlHostPageNumber](#setHtmlHostPageNumber-int-) | Gibt dem benutzerdefinierten Code an, zu welcher Seite des erzeugten Satzes von HTML‑Dateien das gespeicherte Bild gehört. Ist das Aufteilen in Seiten deaktiviert, enthält dieser Wert stets '1', da in diesem Fall nur eine HTML‑Seite erzeugt wird. |
| [setImageType](#setImageType-int-) | Stellt den Typ des im HTML referenzierten gespeicherten Bildes dar. Wird vom Konverter gesetzt und kann im benutzerdefinierten Code verwendet werden, um zu entscheiden, was zu tun ist. |
| [setParentType](#setParentType-int-) | Das gespeicherte Bild kann zur HTML‑Selbst gehören oder aus einem in HTML eingebetteten SVG extrahiert werden. Diese Eigenschaft kann dem benutzerdefinierten Code mitteilen, welcher Elterntyp des verarbeiteten Bildes vorliegt. Sie wird vom Konverter gesetzt und kann im benutzerdefinierten Code verwendet werden, um zu entscheiden, was mit diesem Bild geschehen soll (z. B. kann der benutzerdefinierte Code bestimmen, wo das Bild gespeichert wird oder wie es im Inhalt des Elternteils referenziert werden muss). |
| [setPdfHostPageNumber](#setPdfHostPageNumber-int-) | Gibt dem benutzerdefinierten Code an, zu welcher Seite des ursprünglichen PDF‑Dokuments das gespeicherte Bild gehört. Da möglicherweise nicht alle Seiten des Originaldokuments gespeichert werden, gibt dieser Wert die Host‑Seitenzahl im ursprünglichen PDF an. Ist die Original‑Seitenzahl aus irgendeinem Grund unbekannt, wird stets '1' zurückgegeben. |

### HtmlImageSavingInfo {#HtmlImageSavingInfo--}
```
public HtmlImageSavingInfo()
```

erstellt eine neue Instanz von HtmlImageSavingInfo

### getHtmlHostPageNumber {#getHtmlHostPageNumber--}
```
public int getHtmlHostPageNumber()
```

Gibt dem benutzerdefinierten Code an, zu welcher Seite des erzeugten Satzes von HTML‑Dateien das gespeicherte Bild gehört. Ist das Aufteilen in Seiten deaktiviert, enthält dieser Wert stets '1', da in diesem Fall nur eine HTML‑Seite erzeugt wird.

**Returns:**
int-Wert

### getImageType {#getImageType--}
```
public int getImageType()
```

Stellt den Typ des im HTML referenzierten gespeicherten Bildes dar. Wird vom Konverter gesetzt und kann im benutzerdefinierten Code verwendet werden, um zu entscheiden, was zu tun ist.

**Returns:**
HtmlImageType-Element @see HtmlImageType

### getParentType {#getParentType--}
```
public int getParentType()
```

Das gespeicherte Bild kann zur HTML‑Selbst gehören oder aus einem in HTML eingebetteten SVG extrahiert werden. Diese Eigenschaft kann dem benutzerdefinierten Code mitteilen, welcher Elterntyp des verarbeiteten Bildes vorliegt. Sie wird vom Konverter gesetzt und kann im benutzerdefinierten Code verwendet werden, um zu entscheiden, was mit diesem Bild geschehen soll (z. B. kann der benutzerdefinierte Code bestimmen, wo das Bild gespeichert wird oder wie es im Inhalt des Elternteils referenziert werden muss).

**Returns:**
ImageParentTypes-Element @see ImageParentTypes

### getPdfHostPageNumber {#getPdfHostPageNumber--}
```
public int getPdfHostPageNumber()
```

Gibt dem benutzerdefinierten Code an, zu welcher Seite des ursprünglichen PDF‑Dokuments das gespeicherte Bild gehört. Da möglicherweise nicht alle Seiten des Originaldokuments gespeichert werden, gibt dieser Wert die Host‑Seitenzahl im ursprünglichen PDF an. Ist die Original‑Seitenzahl aus irgendeinem Grund unbekannt, wird stets '1' zurückgegeben.

**Returns:**
int-Wert

### setHtmlHostPageNumber {#setHtmlHostPageNumber-int-}
```
public void setHtmlHostPageNumber(int htmlHostPageNumber)
```

Gibt dem benutzerdefinierten Code an, zu welcher Seite des erzeugten Satzes von HTML‑Dateien das gespeicherte Bild gehört. Ist das Aufteilen in Seiten deaktiviert, enthält dieser Wert stets '1', da in diesem Fall nur eine HTML‑Seite erzeugt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlHostPageNumber |  | int-Wert |

### setImageType {#setImageType-int-}
```
public void setImageType(int imageType)
```

Stellt den Typ des im HTML referenzierten gespeicherten Bildes dar. Wird vom Konverter gesetzt und kann im benutzerdefinierten Code verwendet werden, um zu entscheiden, was zu tun ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageType |  | HtmlImageType-Element @see HtmlImageType |

### setParentType {#setParentType-int-}
```
public void setParentType(int parentType)
```

Das gespeicherte Bild kann zur HTML‑Selbst gehören oder aus einem in HTML eingebetteten SVG extrahiert werden. Diese Eigenschaft kann dem benutzerdefinierten Code mitteilen, welcher Elterntyp des verarbeiteten Bildes vorliegt. Sie wird vom Konverter gesetzt und kann im benutzerdefinierten Code verwendet werden, um zu entscheiden, was mit diesem Bild geschehen soll (z. B. kann der benutzerdefinierte Code bestimmen, wo das Bild gespeichert wird oder wie es im Inhalt des Elternteils referenziert werden muss).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| parentType |  | ImageParentTypes-Element @see ImageParentTypes |

### setPdfHostPageNumber {#setPdfHostPageNumber-int-}
```
public void setPdfHostPageNumber(int pdfHostPageNumber)
```

Gibt dem benutzerdefinierten Code an, zu welcher Seite des ursprünglichen PDF‑Dokuments das gespeicherte Bild gehört. Da möglicherweise nicht alle Seiten des Originaldokuments gespeichert werden, gibt dieser Wert die Host‑Seitenzahl im ursprünglichen PDF an. Ist die Original‑Seitenzahl aus irgendeinem Grund unbekannt, wird stets '1' zurückgegeben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pdfHostPageNumber |  | int-Wert |
