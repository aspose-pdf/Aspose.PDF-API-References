---
title: "XslFoLoadOptions"
linktitle: "XslFoLoadOptions"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta le opzioni per caricare/importare un file XSL-FO in un documento pdf."
type: docs
weight: 5780
url: /it/java/com.aspose.pdf/xslfoloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.XmlLoadOptions com.aspose.pdf.XslFoLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.XmlLoadOptions com.aspose.pdf.XslFoLoadOptions, com.aspose.pdf.XmlLoadOptions, com.aspose.pdf.XslFoLoadOptions

```
public final class XslFoLoadOptions extends XmlLoadOptions
```

Rappresenta le opzioni per caricare/importare un file XSL-FO in un documento pdf.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [XslFoLoadOptions](#XslFoLoadOptions--) | Crea l'oggetto {@code XslFoLoadOptions} senza dati xsl. |
| [XslFoLoadOptions](#XslFoLoadOptions-java.io.InputStream-) | Crea l'oggetto {@code XslFoLoadOptions} senza dati xsl. |
| [XslFoLoadOptions](#XslFoLoadOptions-java.lang.String-) | Crea l'oggetto {@code XslFoLoadOptions} senza dati xsl. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBasePath](#getBasePath--) | Il percorso/base URL da cui vengono cercati i percorsi relativi alle risorse esterne (se presenti) referenziate nel file SVG caricato. |
| [getParsingErrorsHandlingType](#getParsingErrorsHandlingType--) | Il documento XSLFO di origine può contenere errori di formattazione. Questa enum elenca le possibili strategie di gestione di tali errori. |
| [setBasePath](#setBasePath-java.lang.String-) |  |
| [setParsingErrorsHandlingType](#setParsingErrorsHandlingType-int-) | Il documento XSLFO di origine può contenere errori di formattazione. Questa enum elenca le possibili strategie di gestione di tali errori. |

### XslFoLoadOptions {#XslFoLoadOptions--}
```
public XslFoLoadOptions()
```

Crea l'oggetto {@code XslFoLoadOptions} senza dati xsl.

### XslFoLoadOptions {#XslFoLoadOptions-java.io.InputStream-}
Crea l'oggetto {@code XslFoLoadOptions} senza dati xsl.

### XslFoLoadOptions {#XslFoLoadOptions-java.lang.String-}
Crea l'oggetto {@code XslFoLoadOptions} senza dati xsl.

### getBasePath {#getBasePath--}
```
public String getBasePath()
```

Il percorso/base URL da cui vengono cercati i percorsi relativi alle risorse esterne (se presenti) referenziate nel file SVG caricato.

**Returns:**
Stringa

### getParsingErrorsHandlingType {#getParsingErrorsHandlingType--}
```
public int getParsingErrorsHandlingType()
```

Il documento XSLFO di origine può contenere errori di formattazione. Questa enum elenca le possibili strategie di gestione di tali errori.

**Returns:**
Elemento ParsingErrorsHandlingTypes @see ParsingErrorsHandlingTypes

### setBasePath {#setBasePath-java.lang.String-}


### setParsingErrorsHandlingType {#setParsingErrorsHandlingType-int-}
```
public void setParsingErrorsHandlingType(int parsingErrorsHandlingType)
```

Il documento XSLFO di origine può contenere errori di formattazione. Questa enum elenca le possibili strategie di gestione di tali errori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| parsingErrorsHandlingType |  | Elemento ParsingErrorsHandlingTypes @see ParsingErrorsHandlingTypes |
