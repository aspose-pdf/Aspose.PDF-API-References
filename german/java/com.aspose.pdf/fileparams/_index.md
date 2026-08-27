---
title: "FileParams"
linktitle: "FileParams"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Definiert ein eingebettetes Datei-Parameter-Wörterbuch, das zusätzliche dateispezifische Informationen enthalten soll."
type: docs
weight: 1490
url: /de/java/com.aspose.pdf/fileparams/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FileParams

```
public final class FileParams extends Object
```

Definiert ein eingebettetes Datei-Parameter-Wörterbuch, das zusätzliche dateispezifische Informationen enthalten soll.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FileParams](#FileParams-com.aspose.pdf.FileSpecification-) | Konstruktor für die FileParams-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCheckSum](#getCheckSum--) | Ein 16‑Byte‑String, der die Prüfsumme der Bytes der unkomprimierten eingebetteten Datei ist. Die Prüfsumme wird berechnet, indem der standardmäßige MD5-Message-Digest‑Algorithmus auf die Bytes des eingebetteten Dateistreams angewendet wird. |
| [getCreationDate](#getCreationDate--) | Liefert Datum und Uhrzeit, zu der die eingebettete Datei erstellt wurde. |
| [getModDate](#getModDate--) | Liefert Datum und Uhrzeit, zu der die eingebettete Datei zuletzt geändert wurde. |
| [getSize](#getSize--) | Die Größe der unkomprimierten eingebetteten Datei in Bytes. |
| [setCreationDate](#setCreationDate-java.util.Date-) | Setzt Datum und Uhrzeit, zu der die eingebettete Datei erstellt wurde. |
| [setModDate](#setModDate-java.util.Date-) | Setzt Datum und Uhrzeit, zu der die eingebettete Datei zuletzt geändert wurde. |

### FileParams {#FileParams-com.aspose.pdf.FileSpecification-}
Konstruktor für die FileParams-Klasse.

### getCheckSum {#getCheckSum--}
```
public String getCheckSum()
```

Ein 16‑Byte‑String, der die Prüfsumme der Bytes der unkomprimierten eingebetteten Datei ist. Die Prüfsumme wird berechnet, indem der standardmäßige MD5-Message-Digest‑Algorithmus auf die Bytes des eingebetteten Dateistreams angewendet wird.

**Returns:**
String Wert

### getCreationDate {#getCreationDate--}
```
public Date getCreationDate()
```

Liefert Datum und Uhrzeit, zu der die eingebettete Datei erstellt wurde.

**Returns:**
Date-Objekt

### getModDate {#getModDate--}
```
public Date getModDate()
```

Liefert Datum und Uhrzeit, zu der die eingebettete Datei zuletzt geändert wurde.

**Returns:**
Date-Objekt

### getSize {#getSize--}
```
public int getSize()
```

Die Größe der unkomprimierten eingebetteten Datei in Bytes.

**Returns:**
int-Wert

### setCreationDate {#setCreationDate-java.util.Date-}
Setzt Datum und Uhrzeit, zu der die eingebettete Datei erstellt wurde.

### setModDate {#setModDate-java.util.Date-}
Setzt Datum und Uhrzeit, zu der die eingebettete Datei zuletzt geändert wurde.
