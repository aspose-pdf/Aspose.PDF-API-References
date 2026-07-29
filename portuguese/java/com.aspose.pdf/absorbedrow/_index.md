---
title: "AbsorbedRow"
linktitle: "AbsorbedRow"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma linha de tabela que existe na página"
type: docs
weight: 20
url: /pt/java/com.aspose.pdf/absorbedrow/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AbsorbedRow

**All Implemented Interfaces:**
ITableElement, Comparable < AbsorbedRow >

```
public class AbsorbedRow extends Object implements ITableElement , Comparable < AbsorbedRow >
```

Representa uma linha de tabela que existe na página

## Métodos

| Método | Descrição |
| --- | --- |
| [compareTo](#compareTo-com.aspose.pdf.AbsorbedRow-) | Compara o objeto AbsorbedRow atual com outro objeto AbsorbedRow e retorna um inteiro que indica se o objeto atual precede, segue ou ocorre na mesma posição na ordem de classificação que o outro objeto. |
| [getCellList](#getCellList--) | Obtém IList somente leitura contendo as células da linha |
| [getRectangle](#getRectangle--) | Obtém o retângulo que descreve a posição da linha na página |

### compareTo {#compareTo-com.aspose.pdf.AbsorbedRow-}
Compara o objeto AbsorbedRow atual com outro objeto AbsorbedRow e retorna um inteiro que indica se o objeto atual precede, segue ou ocorre na mesma posição na ordem de classificação que o outro objeto.

### getCellList {#getCellList--}
```
public List < AbsorbedCell > getCellList()
```

Obtém IList somente leitura contendo as células da linha

**Returns:**
Lista de objetos AbsorbedCell

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtém o retângulo que descreve a posição da linha na página

**Returns:**
Instância de Rectangle
