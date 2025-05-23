---
title: Class PdfASymbolicFontEncodingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfASymbolicFontEncodingStrategy classe. Esta classe descreve regras que podem ser usadas para ajustar o processo de cópia dos dados de codificação para casos em que uma fonte TrueType simbólica possui mais de uma codificação.
type: docs
weight: 8330
url: /pt/net/aspose.pdf/pdfasymbolicfontencodingstrategy/
---
## Classe PdfASymbolicFontEncodingStrategy

Esta classe descreve regras que podem ser usadas para ajustar o processo de cópia dos dados de codificação para casos em que uma fonte TrueType simbólica possui mais de uma codificação. Alguns documentos PDF, após a conversão para o formato PDF/A, podem apresentar o erro "Mais de uma codificação no cmap da fonte TrueType simbólica". Qual é a razão deste erro? Todas as fontes TrueType simbólicas possuem uma tabela especial "cmap" em seus dados internos. Esta tabela mapeia códigos de caracteres para índices de glifos. E essa tabela pode conter diferentes subtabelas de codificação que descrevem as codificações utilizadas. Veja informações avançadas sobre tabelas cmap em https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html. Geralmente, a tabela cmap contém várias subtabelas de codificação, mas o padrão PDF/A exige que ou apenas uma subtabela de codificação seja mantida para essa fonte no documento PDF/A, ou que haja uma subtabela de codificação (3,0) entre as subtabelas dessa fonte. E a questão principal aqui - quais dados devem ser extraídos de outras subtabelas para copiar para a tabela de codificação de destino (3,0)? A maioria das fontes possui tabelas cmap "bem formadas", onde cada subtabela de codificação é totalmente consistente com as demais. Mas algumas fontes possuem tabelas cmap com colisões - onde, por exemplo, uma subtabela possui o índice de glifo 100 para o unicode 100, mas outra subtabela possui o índice de glifo 200 para o mesmo unicode 100. Para resolver esses problemas, é necessária uma estratégia especial. Por padrão, a seguinte estratégia é utilizada: procura-se a subtabela mac (1,0). Se essa tabela for encontrada, apenas esses dados são usados para preencher a tabela de destino (3,0). Se a subtabela mac não for encontrada, então todas as subtabelas, exceto (3,0), são iteradas e utilizadas para copiar os dados para a subtabela de destino (3,0). Também o mapeamento para cada (unicode, índice de glifo) é copiado para a tabela de destino somente se esta não possuir o unicode no momento. Assim, por exemplo, se a primeira subtabela possui o índice de glifo 100 para o unicode 100 e a próxima subtabela possui o índice de glifo 200 para o mesmo unicode 100, apenas os dados da primeira subtabela (unicode=100, índice de glifo = 100) serão copiados. Portanto, cada subtabela anterior tem precedência sobre as seguintes. As propriedades desta classe `PdfASymbolicFontEncodingStrategy` ajudam a ajustar o comportamento padrão. Se a propriedade [`PreferredCmapEncodingTable`](./preferredcmapencodingtable/) do tipo [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) estiver definida, a subtabela relevante será utilizada com precedência em relação à subtabela mac (1,0). O valor "MacTable" da enumeração [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) não faz sentido neste caso, pois ele aponta para a mesma subtabela mac (1,0) que será utilizada por padrão. A propriedade [`CmapEncodingTablesPriorityQueue`](./cmapencodingtablespriorityqueue/) descarta todas as prioridades para qualquer subtabela. Se essa propriedade estiver definida, somente as subtabelas da fila declarada serão utilizadas na ordem especificada. Se as subtabelas especificadas não forem encontradas, a iteração padrão de todas as subtabelas e a estratégia de cópia descrita acima serão utilizadas. O objeto [`QueueItem`](../pdfasymbolicfontencodingstrategy.queueitem/) especifica a subtabela de codificação utilizada. Essa subtabela pode ser definida através da combinação dos membros (PlatformID, PlatformSpecificId) ou pela enumeração [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/). No caso de a fonte não possuir a subtabela (3,0), alguma outra subtabela será utilizada para manter a compatibilidade com PDF/A. A escolha da subtabela a ser utilizada é feita sob as mesmas regras descritas anteriormente, de forma que as propriedades [`PreferredCmapEncodingTable`](./preferredcmapencodingtable/) e [`CmapEncodingTablesPriorityQueue`](./cmapencodingtablespriorityqueue/) são usadas para determinar a subtabela resultante, e se a fonte não possuir as subtabelas solicitadas, qualquer subtabela existente será utilizada.

```csharp
public class PdfASymbolicFontEncodingStrategy
```

## Construtores

| Name | Description |
| --- | --- |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor)() | Construtor. Define a subtabela padrão (mac 1,0) |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor_1)(CMapEncodingTableType) | Construtor |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor_2)(Queue&lt;QueueItem&gt;) | Construtor |

## Propriedades

| Name | Description |
| --- | --- |
| [CmapEncodingTablesPriorityQueue](../../aspose.pdf/pdfasymbolicfontencodingstrategy/cmapencodingtablespriorityqueue/) { get; set; } | Especifica a fila de subtabelas de codificação a ser processada. |
| [PreferredCmapEncodingTable](../../aspose.pdf/pdfasymbolicfontencodingstrategy/preferredcmapencodingtable/) { get; set; } | Especifica a subtabela que será utilizada com precedência em relação à subtabela mac (1,0). O valor "MacTable" da enumeração [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) não faz sentido neste caso. |

### Veja Também

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)