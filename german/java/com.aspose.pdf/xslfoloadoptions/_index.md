---
title: "XslFoLoadOptions"
linktitle: "XslFoLoadOptions"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt Optionen zum Laden/Importieren von XSL‑FO‑Dateien in ein PDF‑Dokument dar."
type: docs
weight: 5780
url: /de/java/com.aspose.pdf/xslfoloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.XmlLoadOptions com.aspose.pdf.XslFoLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.XmlLoadOptions com.aspose.pdf.XslFoLoadOptions, com.aspose.pdf.XmlLoadOptions, com.aspose.pdf.XslFoLoadOptions

```
public final class XslFoLoadOptions extends XmlLoadOptions
```

Stellt Optionen zum Laden/Importieren von XSL‑FO‑Dateien in ein PDF‑Dokument dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [XslFoLoadOptions](#XslFoLoadOptions--) | Erstellt ein {@code XslFoLoadOptions}-Objekt ohne XSL-Daten. |
| [XslFoLoadOptions](#XslFoLoadOptions-java.io.InputStream-) | Erstellt ein {@code XslFoLoadOptions}-Objekt ohne XSL-Daten. |
| [XslFoLoadOptions](#XslFoLoadOptions-java.lang.String-) | Erstellt ein {@code XslFoLoadOptions}-Objekt ohne XSL-Daten. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBasePath](#getBasePath--) | Der Basis-Pfad/URL, von dem aus relative Pfade zu externen Ressourcen (falls vorhanden) gesucht werden, die in der geladenen SVG-Datei referenziert werden. |
| [getParsingErrorsHandlingType](#getParsingErrorsHandlingType--) | Das Quell‑XSLFO‑Dokument kann Formatierungsfehler enthalten. Dieses Enum enumeriert mögliche Strategien zum Umgang mit diesen Fehlern. |
| [setBasePath](#setBasePath-java.lang.String-) |  |
| [setParsingErrorsHandlingType](#setParsingErrorsHandlingType-int-) | Das Quell‑XSLFO‑Dokument kann Formatierungsfehler enthalten. Dieses Enum enumeriert mögliche Strategien zum Umgang mit diesen Fehlern. |

### XslFoLoadOptions {#XslFoLoadOptions--}
```
public XslFoLoadOptions()
```

Erstellt ein {@code XslFoLoadOptions}-Objekt ohne XSL-Daten.

### XslFoLoadOptions {#XslFoLoadOptions-java.io.InputStream-}
Erstellt ein {@code XslFoLoadOptions}-Objekt ohne XSL-Daten.

### XslFoLoadOptions {#XslFoLoadOptions-java.lang.String-}
Erstellt ein {@code XslFoLoadOptions}-Objekt ohne XSL-Daten.

### getBasePath {#getBasePath--}
```
public String getBasePath()
```

Der Basis-Pfad/URL, von dem aus relative Pfade zu externen Ressourcen (falls vorhanden) gesucht werden, die in der geladenen SVG-Datei referenziert werden.

**Returns:**
String

### getParsingErrorsHandlingType {#getParsingErrorsHandlingType--}
```
public int getParsingErrorsHandlingType()
```

Das Quell‑XSLFO‑Dokument kann Formatierungsfehler enthalten. Dieses Enum enumeriert mögliche Strategien zum Umgang mit diesen Fehlern.

**Returns:**
ParsingErrorsHandlingTypes‑Element @see ParsingErrorsHandlingTypes

### setBasePath {#setBasePath-java.lang.String-}


### setParsingErrorsHandlingType {#setParsingErrorsHandlingType-int-}
```
public void setParsingErrorsHandlingType(int parsingErrorsHandlingType)
```

Das Quell‑XSLFO‑Dokument kann Formatierungsfehler enthalten. Dieses Enum enumeriert mögliche Strategien zum Umgang mit diesen Fehlern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| parsingErrorsHandlingType |  | ParsingErrorsHandlingTypes‑Element @see ParsingErrorsHandlingTypes |
