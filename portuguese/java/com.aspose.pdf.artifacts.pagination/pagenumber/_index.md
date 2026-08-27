---
title: "PageNumber"
linktitle: "PageNumber"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa um formato de número de página que inclui um índice, o número total de páginas e um delimitador."
type: docs
weight: 150
url: /pt/java/com.aspose.pdf.artifacts.pagination/pagenumber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.artifacts.pagination.PageNumber

```
public final class PageNumber extends Object
```

Representa um formato de número de página que inclui um índice, o número total de páginas e um delimitador.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [PageNumber](#PageNumber--) |  |

## Métodos

| Método | Descrição |
| --- | --- |
| [getDelimiter](#getDelimiter--) | Obtém ou define o delimitador usado no formato do número da página. A string formatada será atualizada com base no delimitador especificado. |
| [getIndex](#getIndex--) | Obtém ou define o componente de índice de página do formato do número da página. A string formatada incluirá um espaço reservado para o índice da página. |
| [getOffset](#getOffset--) | Obtém ou define o deslocamento a ser adicionado ao índice da página. |
| [getPageNumberString](#getPageNumberString-int-int-) | Retorna uma string formatada que representa o número da página com base nas configurações atuais. |
| [getTotalNum](#getTotalNum--) | Obtém ou define o componente de número total de páginas do formato do número da página. A string formatada incluirá um espaço reservado para o número total de páginas. |
| [setDelimiter](#setDelimiter-java.lang.String-) | Obtém ou define o delimitador usado no formato do número da página. A string formatada será atualizada com base no delimitador especificado. |
| [setIndex](#setIndex-com.aspose.pdf.artifacts.pagination.PageNumber.PageIndex-) | Obtém ou define o componente de índice de página do formato do número da página. |
| [setOffset](#setOffset-int-) | Obtém ou define o deslocamento a ser adicionado ao índice da página. |
| [setTotalNum](#setTotalNum-com.aspose.pdf.artifacts.pagination.PageNumber.PageTotalNum-) | Obtém ou define o componente de número total de páginas do formato do número da página. |

### PageNumber {#PageNumber--}
```
public PageNumber()
```



### getDelimiter {#getDelimiter--}
```
public final String getDelimiter()
```

Obtém ou define o delimitador usado no formato do número da página. A string formatada será atualizada com base no delimitador especificado.

**Returns:**
valor String

### getIndex {#getIndex--}
```
public final PageNumber.PageIndex getIndex()
```

Obtém ou define o componente de índice de página do formato do número da página. A string formatada incluirá um espaço reservado para o índice da página.

**Returns:**
Instância de PageIndex

### getOffset {#getOffset--}
```
public final int getOffset()
```

Obtém ou define o deslocamento a ser adicionado ao índice da página.

**Returns:**
valor int

### getPageNumberString {#getPageNumberString-int-int-}
```
public final String getPageNumberString(int pageNumber, int count)
```

Retorna uma string formatada que representa o número da página com base nas configurações atuais.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pageNumber |  | O número da página atual. |
| contagem |  | O número total de páginas. |

**Returns:**
Uma string de número de página formatada.

### getTotalNum {#getTotalNum--}
```
public final PageNumber.PageTotalNum getTotalNum()
```

Obtém ou define o componente de número total de páginas do formato do número da página. A string formatada incluirá um espaço reservado para o número total de páginas.

**Returns:**
Instância de PageTotalNum

### setDelimiter {#setDelimiter-java.lang.String-}
Obtém ou define o delimitador usado no formato do número da página. A string formatada será atualizada com base no delimitador especificado.

### setIndex {#setIndex-com.aspose.pdf.artifacts.pagination.PageNumber.PageIndex-}
Obtém ou define o componente de índice de página do formato do número da página.

### setOffset {#setOffset-int-}
```
public final void setOffset(int value)
```

Obtém ou define o deslocamento a ser adicionado ao índice da página.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setTotalNum {#setTotalNum-com.aspose.pdf.artifacts.pagination.PageNumber.PageTotalNum-}
Obtém ou define o componente de número total de páginas do formato do número da página.
