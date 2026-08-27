---
title: "HtmlDiffOutputGenerator"
linktitle: "HtmlDiffOutputGenerator"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma classe para gerar representação HTML das diferenças de textos. Quebras de linha excluídas são indicadas por - marca de parágrafo."
type: docs
weight: 10
url: /pt/java/com.aspose.pdf.comparison.outputgenerator/htmldiffoutputgenerator/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.outputgenerator.HtmlDiffOutputGenerator

**All Implemented Interfaces:**
IFileOutputGenerator, IStringOutputGenerator

```
public class HtmlDiffOutputGenerator extends Object implements IStringOutputGenerator , IFileOutputGenerator
```

Representa uma classe para gerar representação HTML das diferenças de textos. Quebras de linha excluídas são indicadas por - marca de parágrafo.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [HtmlDiffOutputGenerator](#HtmlDiffOutputGenerator--) | Cria uma instância da classe {@link HtmlDiffOutputGenerator} . |
| [HtmlDiffOutputGenerator](#HtmlDiffOutputGenerator-com.aspose.pdf.comparison.outputgenerator.OutputTextStyle-) | Cria uma instância da classe {@link HtmlDiffOutputGenerator} . |

## Métodos

| Método | Descrição |
| --- | --- |
| [generateOutput](#generateOutput-java.util.List-) | Gera a saída com base nas diferenças entre os textos e a salva em um arquivo. |
| [generateOutput](#generateOutput-java.util.List-java.lang.String-) | Gera a saída com base nas diferenças entre os textos e a salva em um arquivo. |
| [generateOutput1](#generateOutput1-java.util.List-) | Gera a saída com base nas diferenças entre os textos e a salva em um arquivo. |
| [generateOutput1](#generateOutput1-java.util.List-java.lang.String-) | Gera a saída com base nas diferenças entre os textos e a salva em um arquivo. |
| [generateOutputInternal](#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-) |  |
| [generateOutputInternal](#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-java.lang.String-) |  |
| [generateOutputInternal1](#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-) | Método interno |
| [generateOutputInternal1](#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-java.lang.String-) |  |
| [getDeleteStyle](#getDeleteStyle--) | Obtém e define a string em estilo CSS para a operação Delete. Example: color: #003300; background-color: #ccff66; |
| [getEqualStyle](#getEqualStyle--) | Obtém e define a string em estilo CSS para a operação Equal. Example: color: #003300; background-color: #ccff66; |
| [getInsertStyle](#getInsertStyle--) | Obtém e define a string em estilo CSS para a operação Insert. Example: color: #003300; background-color: #ccff66; |
| [getStrikethroughDeleted](#getStrikethroughDeleted--) | Obtenha ou defina o estilo text-decoration: line-through para a operação delete. Default value is {@code False}. |
| [setDeleteStyle](#setDeleteStyle-java.lang.String-) | Obtém e define a string em estilo CSS para a operação Delete. Example: color: #003300; background-color: #ccff66; |
| [setEqualStyle](#setEqualStyle-java.lang.String-) | Obtém e define a string em estilo CSS para a operação Equal. Example: color: #003300; background-color: #ccff66; |
| [setInsertStyle](#setInsertStyle-java.lang.String-) | Obtém e define a string em estilo CSS para a operação Insert. Example: color: #003300; background-color: #ccff66; |
| [setStrikethroughDeleted](#setStrikethroughDeleted-boolean-) | Obtenha ou defina o estilo text-decoration: line-through para a operação delete. Default value is {@code False}. |

### HtmlDiffOutputGenerator {#HtmlDiffOutputGenerator--}
```
public HtmlDiffOutputGenerator()
```

Cria uma instância da classe {@link HtmlDiffOutputGenerator} .

### HtmlDiffOutputGenerator {#HtmlDiffOutputGenerator-com.aspose.pdf.comparison.outputgenerator.OutputTextStyle-}
Cria uma instância da classe {@link HtmlDiffOutputGenerator} .

### generateOutput {#generateOutput-java.util.List-}
Gera a saída com base nas diferenças entre os textos e a salva em um arquivo.

### generateOutput {#generateOutput-java.util.List-java.lang.String-}
Gera a saída com base nas diferenças entre os textos e a salva em um arquivo.

### generateOutput1 {#generateOutput1-java.util.List-}
Gera a saída com base nas diferenças entre os textos e a salva em um arquivo.

### generateOutput1 {#generateOutput1-java.util.List-java.lang.String-}
Gera a saída com base nas diferenças entre os textos e a salva em um arquivo.

### generateOutputInternal {#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-}


### generateOutputInternal {#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-java.lang.String-}


### generateOutputInternal1 {#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-}
Método interno

### generateOutputInternal1 {#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-java.lang.String-}


### getDeleteStyle {#getDeleteStyle--}
```
public final String getDeleteStyle()
```

Obtém e define a string em estilo CSS para a operação Delete. Example: color: #003300; background-color: #ccff66;

**Returns:**
valor String

### getEqualStyle {#getEqualStyle--}
```
public final String getEqualStyle()
```

Obtém e define a string em estilo CSS para a operação Equal. Example: color: #003300; background-color: #ccff66;

**Returns:**
valor String

### getInsertStyle {#getInsertStyle--}
```
public final String getInsertStyle()
```

Obtém e define a string em estilo CSS para a operação Insert. Example: color: #003300; background-color: #ccff66;

**Returns:**
valor String

### getStrikethroughDeleted {#getStrikethroughDeleted--}
```
public final boolean getStrikethroughDeleted()
```

Obtenha ou defina o estilo text-decoration: line-through para a operação delete. Default value is {@code False}.

**Returns:**
valor booleano

### setDeleteStyle {#setDeleteStyle-java.lang.String-}
Obtém e define a string em estilo CSS para a operação Delete. Example: color: #003300; background-color: #ccff66;

### setEqualStyle {#setEqualStyle-java.lang.String-}
Obtém e define a string em estilo CSS para a operação Equal. Example: color: #003300; background-color: #ccff66;

### setInsertStyle {#setInsertStyle-java.lang.String-}
Obtém e define a string em estilo CSS para a operação Insert. Example: color: #003300; background-color: #ccff66;

### setStrikethroughDeleted {#setStrikethroughDeleted-boolean-}
```
public final void setStrikethroughDeleted(boolean value)
```

Obtenha ou defina o estilo text-decoration: line-through para a operação delete. Default value is {@code False}.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |
