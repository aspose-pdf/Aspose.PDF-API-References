---
title: "AbsorbedTable"
linktitle: "AbsorbedTable"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma tabela que existe na página"
type: docs
weight: 30
url: /pt/java/com.aspose.pdf/absorbedtable/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AbsorbedTable

**All Implemented Interfaces:**
ITableElement, Comparable < AbsorbedTable >

```
public class AbsorbedTable extends Object implements ITableElement , Comparable < AbsorbedTable >
```

Representa uma tabela que existe na página

## Métodos

| Método | Descrição |
| --- | --- |
| [compareTo](#compareTo-com.aspose.pdf.AbsorbedTable-) | Compara o objeto AbsorbedTable atual com outro objeto AbsorbedTable e retorna um inteiro que indica se o objeto atual precede, segue ou ocorre na mesma posição na ordem de classificação que o outro objeto. |
| [getPageNum](#getPageNum--) | Obtém o número da página que contém esta tabela |
| [getRectangle](#getRectangle--) | Obtém o retângulo que descreve a posição da tabela na página |
| [getRowList](#getRowList--) | <p> Obtém IList somente leitura contendo linhas da tabela </p> |

### compareTo {#compareTo-com.aspose.pdf.AbsorbedTable-}
Compara o objeto AbsorbedTable atual com outro objeto AbsorbedTable e retorna um inteiro que indica se o objeto atual precede, segue ou ocorre na mesma posição na ordem de classificação que o outro objeto.

### getPageNum {#getPageNum--}
```
public int getPageNum()
```

Obtém o número da página que contém esta tabela

**Returns:**
valor int

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtém o retângulo que descreve a posição da tabela na página

**Returns:**
objeto Rectangle

### getRowList {#getRowList--}
```
public List < AbsorbedRow > getRowList()
```

<p> Obtém IList somente leitura contendo linhas da tabela </p>

**Returns:**
{@code IGenericList<AbsorbedRow>} objeto
