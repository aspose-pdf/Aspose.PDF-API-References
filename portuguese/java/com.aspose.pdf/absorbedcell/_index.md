---
title: "AbsorbedCell"
linktitle: "AbsorbedCell"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma célula de tabela que existe na página"
type: docs
weight: 10
url: /pt/java/com.aspose.pdf/absorbedcell/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AbsorbedCell

**All Implemented Interfaces:**
ITableElement, Comparable < AbsorbedCell >

```
public class AbsorbedCell extends Object implements ITableElement , Comparable < AbsorbedCell >
```

Representa uma célula de tabela que existe na página

## Métodos

| Método | Descrição |
| --- | --- |
| [compareTo](#compareTo-com.aspose.pdf.AbsorbedCell-) | Compara o objeto AbsorbedCell atual com outro objeto AbsorbedCell e retorna um inteiro que indica se o objeto atual precede, segue ou ocorre na mesma posição na ordem de classificação que o outro objeto. |
| [getBorderInfo](#getBorderInfo--) | Retorna as informações de borda da célula quando a propriedade FlowEngine.TableAbsorber.UseFlowEngine está definida como true. |
| [getColSpan](#getColSpan--) | Retorne o número de colunas que a célula deve abranger quando a propriedade TableAbsorber.UseFlowEngine estiver definida como true. |
| [getRectangle](#getRectangle--) | Obtém o retângulo que descreve a posição da célula na página |
| [getTextFragments](#getTextFragments--) | Obtém a coleção de objetos {@code TextFragment} que descrevem o texto contido na célula |

### compareTo {#compareTo-com.aspose.pdf.AbsorbedCell-}
Compara o objeto AbsorbedCell atual com outro objeto AbsorbedCell e retorna um inteiro que indica se o objeto atual precede, segue ou ocorre na mesma posição na ordem de classificação que o outro objeto.

### getBorderInfo {#getBorderInfo--}
```
public final BorderInfo getBorderInfo()
```

Retorna as informações de borda da célula quando a propriedade FlowEngine.TableAbsorber.UseFlowEngine está definida como true.

**Returns:**
Instância BorderInfo

### getColSpan {#getColSpan--}
```
public final int getColSpan()
```

Retorne o número de colunas que a célula deve abranger quando a propriedade TableAbsorber.UseFlowEngine estiver definida como true.

**Returns:**
valor int

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtém o retângulo que descreve a posição da célula na página

**Returns:**
objeto Rectangle

### getTextFragments {#getTextFragments--}
```
public TextFragmentCollection getTextFragments()
```

Obtém a coleção de objetos {@code TextFragment} que descrevem o texto contido na célula

**Returns:**
Objeto TextFragmentCollection
