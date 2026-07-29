---
title: "XslFoLoadOptions"
linktitle: "XslFoLoadOptions"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar alternativ för inläsning/import av XSL-FO-fil till pdf-dokument."
type: docs
weight: 5780
url: /sv/java/com.aspose.pdf/xslfoloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.XmlLoadOptions com.aspose.pdf.XslFoLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.XmlLoadOptions com.aspose.pdf.XslFoLoadOptions, com.aspose.pdf.XmlLoadOptions, com.aspose.pdf.XslFoLoadOptions

```
public final class XslFoLoadOptions extends XmlLoadOptions
```

Representerar alternativ för inläsning/import av XSL-FO-fil till pdf-dokument.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [XslFoLoadOptions](#XslFoLoadOptions--) | Skapar {@code XslFoLoadOptions}-objekt utan xsl-data. |
| [XslFoLoadOptions](#XslFoLoadOptions-java.io.InputStream-) | Skapar {@code XslFoLoadOptions}-objekt utan xsl-data. |
| [XslFoLoadOptions](#XslFoLoadOptions-java.lang.String-) | Skapar {@code XslFoLoadOptions}-objekt utan xsl-data. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBasePath](#getBasePath--) | Bas-sökväg/URL varifrån relativa sökvägar till externa resurser (om några) som refereras i den inlästa SVG-filen söks. |
| [getParsingErrorsHandlingType](#getParsingErrorsHandlingType--) | Käll-XSLFO-dokumentet kan innehålla formateringsfel. Denna enum listar möjliga strategier för hantering av dessa fel. |
| [setBasePath](#setBasePath-java.lang.String-) |  |
| [setParsingErrorsHandlingType](#setParsingErrorsHandlingType-int-) | Käll-XSLFO-dokumentet kan innehålla formateringsfel. Denna enum listar möjliga strategier för hantering av dessa fel. |

### XslFoLoadOptions {#XslFoLoadOptions--}
```
public XslFoLoadOptions()
```

Skapar {@code XslFoLoadOptions}-objekt utan xsl-data.

### XslFoLoadOptions {#XslFoLoadOptions-java.io.InputStream-}
Skapar {@code XslFoLoadOptions}-objekt utan xsl-data.

### XslFoLoadOptions {#XslFoLoadOptions-java.lang.String-}
Skapar {@code XslFoLoadOptions}-objekt utan xsl-data.

### getBasePath {#getBasePath--}
```
public String getBasePath()
```

Bas-sökväg/URL varifrån relativa sökvägar till externa resurser (om några) som refereras i den inlästa SVG-filen söks.

**Returns:**
String

### getParsingErrorsHandlingType {#getParsingErrorsHandlingType--}
```
public int getParsingErrorsHandlingType()
```

Käll-XSLFO-dokumentet kan innehålla formateringsfel. Denna enum listar möjliga strategier för hantering av dessa fel.

**Returns:**
ParsingErrorsHandlingTypes-element @see ParsingErrorsHandlingTypes

### setBasePath {#setBasePath-java.lang.String-}


### setParsingErrorsHandlingType {#setParsingErrorsHandlingType-int-}
```
public void setParsingErrorsHandlingType(int parsingErrorsHandlingType)
```

Käll-XSLFO-dokumentet kan innehålla formateringsfel. Denna enum listar möjliga strategier för hantering av dessa fel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| parsingErrorsHandlingType |  | ParsingErrorsHandlingTypes-element @see ParsingErrorsHandlingTypes |
