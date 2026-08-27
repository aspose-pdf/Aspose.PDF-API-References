---
title: "TextExtractionOptions"
linktitle: "TextExtractionOptions"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa opções de extração de texto"
type: docs
weight: 5060
url: /pt/java/com.aspose.pdf/textextractionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextExtractionOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextExtractionOptions

```
public final class TextExtractionOptions extends TextOptions
```

Representa opções de extração de texto

## Construtores

| Construtor | Descrição |
| --- | --- |
| [TextExtractionOptions](#TextExtractionOptions-int-) | Inicializa uma nova instância do objeto {@code TextExtractionOptions} para o modo de formatação de texto especificado. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getFormattingMode](#getFormattingMode--) | Obtém o modo de formatação. |
| [getScaleFactor](#getScaleFactor--) | Obtém o fator que será aplicado para escalar o tamanho da fonte durante a extração no modo puro. Definir um valor menor gera mais espaços no texto extraído. O valor padrão é 1 - sem escala; definir o valor como zero permite que o algoritmo escolha a escala automaticamente. |
| [setFormattingMode](#setFormattingMode-int-) | Define o modo de formatação. |
| [setScaleFactor](#setScaleFactor-double-) | Define o fator que será aplicado para escalar o tamanho da fonte durante a extração no modo puro. Definir um valor menor gera mais espaços no texto extraído (de 1 a 10). O valor padrão é 1 - sem escala; definir o valor como zero permite que o algoritmo escolha a escala automaticamente. |

### TextExtractionOptions {#TextExtractionOptions-int-}
```
public TextExtractionOptions(int formattingMode)
```

Inicializa uma nova instância do objeto {@code TextExtractionOptions} para o modo de formatação de texto especificado.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| formattingMode |  | Valor do modo de formatação de texto. @see TextFormattingMode |

### getFormattingMode {#getFormattingMode--}
```
public int getFormattingMode()
```

Obtém o modo de formatação.

**Returns:**
TextFormattingMode valor @see TextFormattingMode

### getScaleFactor {#getScaleFactor--}
```
public double getScaleFactor()
```

Obtém o fator que será aplicado para escalar o tamanho da fonte durante a extração no modo puro. Definir um valor menor gera mais espaços no texto extraído. O valor padrão é 1 - sem escala; definir o valor como zero permite que o algoritmo escolha a escala automaticamente.

**Returns:**
valor double

### setFormattingMode {#setFormattingMode-int-}
```
public void setFormattingMode(int value)
```

Define o modo de formatação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | TextFormattingMode valor @see TextFormattingMode |

### setScaleFactor {#setScaleFactor-double-}
```
public void setScaleFactor(double value)
```

Define o fator que será aplicado para escalar o tamanho da fonte durante a extração no modo puro. Definir um valor menor gera mais espaços no texto extraído (de 1 a 10). O valor padrão é 1 - sem escala; definir o valor como zero permite que o algoritmo escolha a escala automaticamente.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |
