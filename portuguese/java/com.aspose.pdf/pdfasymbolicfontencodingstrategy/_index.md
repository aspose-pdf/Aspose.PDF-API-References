---
title: "PdfASymbolicFontEncodingStrategy"
linktitle: "PdfASymbolicFontEncodingStrategy"
second_title: "Referência da API Aspose.PDF para Java"
description: "Esta classe descreve regras que podem ser usadas para ajustar o processo de cópia de dados de codificação para casos em que a fonte simbólica TrueType tem mais de uma codificação. Alguns documentos PDF depois."
type: docs
weight: 3690
url: /pt/java/com.aspose.pdf/pdfasymbolicfontencodingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfASymbolicFontEncodingStrategy

```
public class PdfASymbolicFontEncodingStrategy extends Object
```

Esta classe descreve regras que podem ser usadas para ajustar o processo de cópia de dados de codificação para casos em que a fonte simbólica TrueType tem mais de uma codificação. Alguns documentos PDF após a conversão para o formato PDF/A podem gerar um erro \"More than one encoding in symbolic TrueType font's cmap\". Qual é a razão desse erro? Todas as fontes simbólicas TrueType têm uma tabela especial \"cmap\" em seus dados internos. Essa tabela mapeia códigos de caracteres para índices de glifos. E essa tabela pode conter diferentes subtabelas de codificação que descrevem as codificações usadas. Veja informações avançadas sobre tabelas cmap em https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html. Normalmente a tabela cmap contém várias subtabelas de codificação, mas o padrão PDF/A exige que ou apenas uma subtabela de codificação seja deixada para essa fonte no documento PDF/A ou que exista uma subtabela de codificação (3,0) entre as subtabelas dessa fonte. E a questão principal aqui – quais dados devem ser obtidos de outras subtabelas para copiar para a tabela de codificação de destino (3,0)? A maioria das fontes possui tabelas cmap "bem‑formadas" onde cada subtabela de codificação é totalmente consistente com outra subtabela. Mas algumas fontes têm tabelas cmap com colisões – onde, por exemplo, uma subtabela tem índice de glifo 100 para unicode 100, mas outra subtabela tem índice de glifo 200 para o mesmo unicode 100. Para resolver esses problemas é necessária uma estratégia especial. Por padrão, a seguinte estratégia é usada: procura‑se a subtabela mac (1,0). Se essa tabela for encontrada, apenas esses dados são usados para preencher a tabela de destino (3,0). Se a subtabela mac não for encontrada, então todas as subtabelas exceto (3,0) são iteradas e usadas para copiar dados para a subtabela de destino (3,0). Também o mapeamento para cada unicode (unicode, índice de glifo) é copiado para a tabela de destino somente se a tabela de destino não possuir esse unicode no momento. Assim, por exemplo, se a primeira subtabela tem índice de glifo 100 para unicode 100, e a próxima subtabela tem índice de glifo 200 para o mesmo unicode 100, apenas os dados da primeira subtabela (unicode=100, índice de glifo = 100) serão copiados. Portanto, cada subtabela anterior tem precedência sobre a seguinte. As propriedades desta classe { PdfASymbolicFontEncodingStrategy} ajudam a ajustar o comportamento padrão. Se a propriedade {PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ { PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) do tipo { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} estiver definida, então a subtabela relevante será usada com precedência sobre a subtabela mac (1,0). O valor 'MacTable' da enumeração {PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} não faz sentido neste caso, pois aponta para a mesma subtabela mac (1,0) que será usada por padrão. A propriedade {CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ {PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) descarta todas as prioridades para qualquer subtabela. Se essa propriedade for definida, então apenas as subtabelas da fila declarada serão usadas na ordem especificada. Se as subtabelas especificadas não forem encontradas, então a iteração padrão de todas as subtabelas e a estratégia de cópia descrita acima serão usadas. O objeto { PdfASymbolicFontEncodingStrategy.QueueItem} especifica a subtabela de codificação usada. Essa subtabela pode ser definida via combinação de membros (PlatformID, PlatformSpecificId) ou via enumeração { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType}. No caso de a fonte não ter subtabela (3,0), outra subtabela será usada para manter a compatibilidade PDF/A. A escolha da subtabela a ser usada é feita sob as mesmas regras descritas anteriormente, de modo que as propriedades {@code PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ {PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) e {@code CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ { PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) são usadas para determinar a subtabela resultante, e se a fonte não possuir a(s) subtabela(s) solicitada(s), então qualquer subtabela existente será usada.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [PdfASymbolicFontEncodingStrategy](#PdfASymbolicFontEncodingStrategy--) | Construtor. Define a sub‑tabela padrão (mac 1,0) |
| [PdfASymbolicFontEncodingStrategy](#PdfASymbolicFontEncodingStrategy-com.aspose.ms.System.Collections.Generic.Queue-) | Construtor. Define a sub‑tabela padrão (mac 1,0) |
| [PdfASymbolicFontEncodingStrategy](#PdfASymbolicFontEncodingStrategy-short-) | Construtor |

## Métodos

| Método | Descrição |
| --- | --- |
| [getCmapEncodingTablesPriorityQueue](#getCmapEncodingTablesPriorityQueue--) | Especifica a fila de subtabelas de codificação a serem processadas. |
| [getPreferredCmapEncodingTable](#getPreferredCmapEncodingTable--) | Especifica a subtabela que será usada com precedência sobre a subtabela mac (1,0). O valor 'MacTable' da enumeração {@code QueueItem.CMapEncodingTableType} não faz sentido neste caso. |
| [setCmapEncodingTablesPriorityQueue](#setCmapEncodingTablesPriorityQueue-com.aspose.ms.System.Collections.Generic.Queue-) | Especifica a fila de subtabelas de codificação a serem processadas. |
| [setPreferredCmapEncodingTable](#setPreferredCmapEncodingTable-short-) | Especifica a subtabela que será usada com precedência sobre a subtabela mac (1,0). O valor 'MacTable' da enumeração {@code QueueItem.CMapEncodingTableType} não faz sentido neste caso. |

### PdfASymbolicFontEncodingStrategy {#PdfASymbolicFontEncodingStrategy--}
```
public PdfASymbolicFontEncodingStrategy()
```

Construtor. Define a sub‑tabela padrão (mac 1,0)

### PdfASymbolicFontEncodingStrategy {#PdfASymbolicFontEncodingStrategy-com.aspose.ms.System.Collections.Generic.Queue-}
Construtor. Define a sub‑tabela padrão (mac 1,0)

### PdfASymbolicFontEncodingStrategy {#PdfASymbolicFontEncodingStrategy-short-}
```
public PdfASymbolicFontEncodingStrategy(short preferredEncodingTable)
```

Construtor

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| preferredEncodingTable |  | subtabela de codificação que será usada com precedência sobre a subtabela mac (1,0) @see PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType |

### getCmapEncodingTablesPriorityQueue {#getCmapEncodingTablesPriorityQueue--}
```
public com.aspose.ms.System.Collections.Generic.Queue< PdfASymbolicFontEncodingStrategy.QueueItem > getCmapEncodingTablesPriorityQueue()
```

Especifica a fila de subtabelas de codificação a serem processadas.

**Returns:**
Fila de QueueItem

### getPreferredCmapEncodingTable {#getPreferredCmapEncodingTable--}
```
public short getPreferredCmapEncodingTable()
```

Especifica a subtabela que será usada com precedência sobre a subtabela mac (1,0). O valor 'MacTable' da enumeração {@code QueueItem.CMapEncodingTableType} não faz sentido neste caso.

**Returns:**
elemento CMapEncodingTableType @see PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType

### setCmapEncodingTablesPriorityQueue {#setCmapEncodingTablesPriorityQueue-com.aspose.ms.System.Collections.Generic.Queue-}
Especifica a fila de subtabelas de codificação a serem processadas.

### setPreferredCmapEncodingTable {#setPreferredCmapEncodingTable-short-}
```
public void setPreferredCmapEncodingTable(short value)
```

Especifica a subtabela que será usada com precedência sobre a subtabela mac (1,0). O valor 'MacTable' da enumeração {@code QueueItem.CMapEncodingTableType} não faz sentido neste caso.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | subtabela de codificação preferredEncodingTable que será usada com precedência sobre a subtabela mac(1,0) @see PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType |
