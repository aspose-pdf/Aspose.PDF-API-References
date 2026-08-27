---
title: "XslFoLoadOptions"
linktitle: "XslFoLoadOptions"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa opções para carregar/importar arquivo XSL-FO em documento PDF."
type: docs
weight: 5780
url: /pt/java/com.aspose.pdf/xslfoloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.XmlLoadOptions com.aspose.pdf.XslFoLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.XmlLoadOptions com.aspose.pdf.XslFoLoadOptions, com.aspose.pdf.XmlLoadOptions, com.aspose.pdf.XslFoLoadOptions

```
public final class XslFoLoadOptions extends XmlLoadOptions
```

Representa opções para carregar/importar arquivo XSL-FO em documento PDF.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [XslFoLoadOptions](#XslFoLoadOptions--) | Cria um objeto {@code XslFoLoadOptions} sem dados xsl. |
| [XslFoLoadOptions](#XslFoLoadOptions-java.io.InputStream-) | Cria um objeto {@code XslFoLoadOptions} sem dados xsl. |
| [XslFoLoadOptions](#XslFoLoadOptions-java.lang.String-) | Cria um objeto {@code XslFoLoadOptions} sem dados xsl. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getBasePath](#getBasePath--) | O caminho/base URL a partir do qual são pesquisados caminhos relativos para recursos externos (se houver) referenciados no arquivo SVG carregado. |
| [getParsingErrorsHandlingType](#getParsingErrorsHandlingType--) | O documento XSLFO de origem pode conter erros de formatação. Este enum enumera possíveis estratégias de tratamento desses erros. |
| [setBasePath](#setBasePath-java.lang.String-) |  |
| [setParsingErrorsHandlingType](#setParsingErrorsHandlingType-int-) | O documento XSLFO de origem pode conter erros de formatação. Este enum enumera possíveis estratégias de tratamento desses erros. |

### XslFoLoadOptions {#XslFoLoadOptions--}
```
public XslFoLoadOptions()
```

Cria um objeto {@code XslFoLoadOptions} sem dados xsl.

### XslFoLoadOptions {#XslFoLoadOptions-java.io.InputStream-}
Cria um objeto {@code XslFoLoadOptions} sem dados xsl.

### XslFoLoadOptions {#XslFoLoadOptions-java.lang.String-}
Cria um objeto {@code XslFoLoadOptions} sem dados xsl.

### getBasePath {#getBasePath--}
```
public String getBasePath()
```

O caminho/base URL a partir do qual são pesquisados caminhos relativos para recursos externos (se houver) referenciados no arquivo SVG carregado.

**Returns:**
String

### getParsingErrorsHandlingType {#getParsingErrorsHandlingType--}
```
public int getParsingErrorsHandlingType()
```

O documento XSLFO de origem pode conter erros de formatação. Este enum enumera possíveis estratégias de tratamento desses erros.

**Returns:**
Elemento ParsingErrorsHandlingTypes @see ParsingErrorsHandlingTypes

### setBasePath {#setBasePath-java.lang.String-}


### setParsingErrorsHandlingType {#setParsingErrorsHandlingType-int-}
```
public void setParsingErrorsHandlingType(int parsingErrorsHandlingType)
```

O documento XSLFO de origem pode conter erros de formatação. Este enum enumera possíveis estratégias de tratamento desses erros.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| parsingErrorsHandlingType |  | Elemento ParsingErrorsHandlingTypes @see ParsingErrorsHandlingTypes |
