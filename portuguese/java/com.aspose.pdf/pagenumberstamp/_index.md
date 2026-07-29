---
title: "PageNumberStamp"
linktitle: "PageNumberStamp"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa o selo de número de página e é usado para numerar páginas."
type: docs
weight: 3440
url: /pt/java/com.aspose.pdf/pagenumberstamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp com.aspose.pdf.TextStamp com.aspose.pdf.PageNumberStamp, com.aspose.pdf.Stamp, com.aspose.pdf.TextStamp com.aspose.pdf.PageNumberStamp, com.aspose.pdf.TextStamp, com.aspose.pdf.PageNumberStamp

```
public final class PageNumberStamp extends TextStamp
```

Representa o selo de número de página e é usado para numerar páginas.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [PageNumberStamp](#PageNumberStamp--) | Inicializa uma nova instância da classe {@code PageNumberStamp}. O formato é definido como "#". |
| [PageNumberStamp](#PageNumberStamp-com.aspose.pdf.facades.FormattedText-) | Inicializa uma nova instância da classe {@code PageNumberStamp}. O formato é definido como "#". |
| [PageNumberStamp](#PageNumberStamp-java.lang.String-) | Inicializa uma nova instância da classe {@code PageNumberStamp}. O formato é definido como "#". |

## Métodos

| Método | Descrição |
| --- | --- |
| [getFormat](#getFormat--) | Obtém o valor String para carimbar números de página. O valor deve incluir o caractere '#' que é substituído pelo número da página durante o carimbo. |
| [getNumberingStyle](#getNumberingStyle--) | Estilo de numeração usado por este carimbo. |
| [getStartingNumber](#getStartingNumber--) | Obtém o valor do número da página inicial. As outras páginas serão numeradas a partir desse valor. |
| [put](#put-com.aspose.pdf.Page-) | Adiciona número da página. |
| [setFormat](#setFormat-java.lang.String-) | Define o valor String para a marcação de números de página. O valor deve incluir o caractere '#' que é substituído pelo número da página durante o processo de marcação. |
| [setNumberingStyle](#setNumberingStyle-com.aspose.pdf.NumberingStyle-) | Estilo de numeração usado por este carimbo. |
| [setStartingNumber](#setStartingNumber-int-) | Define o valor do número da página inicial. As outras páginas serão numeradas a partir desse valor. |

### PageNumberStamp {#PageNumberStamp--}
```
public PageNumberStamp()
```

Inicializa uma nova instância da classe {@code PageNumberStamp}. O formato é definido como "#".

### PageNumberStamp {#PageNumberStamp-com.aspose.pdf.facades.FormattedText-}
Inicializa uma nova instância da classe {@code PageNumberStamp}. O formato é definido como "#".

### PageNumberStamp {#PageNumberStamp-java.lang.String-}
Inicializa uma nova instância da classe {@code PageNumberStamp}. O formato é definido como "#".

### getFormat {#getFormat--}
```
public String getFormat()
```

Obtém o valor String para carimbar números de página. O valor deve incluir o caractere '#' que é substituído pelo número da página durante o carimbo.

**Returns:**
valor String

### getNumberingStyle {#getNumberingStyle--}
```
public NumberingStyle getNumberingStyle()
```

Estilo de numeração usado por este carimbo.

**Returns:**
Valor NumberingStyle @see NumberingStyle

### getStartingNumber {#getStartingNumber--}
```
public int getStartingNumber()
```

Obtém o valor do número da página inicial. As outras páginas serão numeradas a partir desse valor.

**Returns:**
valor int

### put {#put-com.aspose.pdf.Page-}
Adiciona número da página.

### setFormat {#setFormat-java.lang.String-}
Define o valor String para a marcação de números de página. O valor deve incluir o caractere '#' que é substituído pelo número da página durante o processo de marcação.

### setNumberingStyle {#setNumberingStyle-com.aspose.pdf.NumberingStyle-}
Estilo de numeração usado por este carimbo.

### setStartingNumber {#setStartingNumber-int-}
```
public void setStartingNumber(int value)
```

Define o valor do número da página inicial. As outras páginas serão numeradas a partir desse valor.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |
