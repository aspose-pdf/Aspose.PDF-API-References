---
title: "HeadingLevels"
linktitle: "HeadingLevels"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma classe para trabalhar com níveis de cabeçalho baseados no tamanho da fonte."
type: docs
weight: 20
url: /pt/java/com.aspose.pdf.markdownoptions/headinglevels/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.markdownoptions.HeadingLevels

```
public class HeadingLevels extends Object
```

Representa uma classe para trabalhar com níveis de cabeçalho baseados no tamanho da fonte.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [HeadingLevels](#HeadingLevels--) | Cria uma nova instância da classe HeadingLevels. |
| [HeadingLevels](#HeadingLevels-double-) | Cria uma nova instância da classe HeadingLevels. |

## Métodos

| Método | Descrição |
| --- | --- |
| [addLevels](#addLevels-java.lang.Iterable-) | Adiciona níveis de cabeçalho. |
| [estimateLevel](#estimateLevel-double-) | Estima o nível de cabeçalho possível. Se fontSize não for encontrado na lista de níveis, será retornado o nível mais próximo desse valor de tamanho de fonte. Se fontSize estiver fora dos níveis mínimo e máximo de cabeçalho especificados, o método retornará false. |
| [findLevel](#findLevel-double-int:A-) | Encontra o nível correspondente ao tamanho de fonte. Procurando por correspondência exata. |
| [getAllLevels](#getAllLevels--) | Obtém todos os níveis de cabeçalho. |

### HeadingLevels {#HeadingLevels--}
```
public HeadingLevels()
```

Cria uma nova instância da classe HeadingLevels.

### HeadingLevels {#HeadingLevels-double-}
```
public HeadingLevels(double threshold)
```

Cria uma nova instância da classe HeadingLevels.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| threshold |  | O valor de limiar para comparar tamanhos de fonte. Dentro do limiar, os níveis de cabeçalho são os mesmos. O valor padrão do limiar é 0.01. |

### addLevels {#addLevels-java.lang.Iterable-}
Adiciona níveis de cabeçalho.

### estimateLevel {#estimateLevel-double-}
```
public final int estimateLevel(double fontSize)
```

Estima o nível de cabeçalho possível. Se fontSize não for encontrado na lista de níveis, será retornado o nível mais próximo desse valor de tamanho de fonte. Se fontSize estiver fora dos níveis mínimo e máximo de cabeçalho especificados, o método retornará false.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontSize |  | O tamanho da fonte. |

**Returns:**
Nível de cabeçalho.

### findLevel {#findLevel-double-int:A-}
```
public final boolean findLevel(double fontSize, int[] level)
```

Encontra o nível correspondente ao tamanho de fonte. Procurando por correspondência exata.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontSize |  | O tamanho da fonte. |
| level |  | O nível de cabeçalho correspondente ao tamanho de fonte fornecido. |

**Returns:**
False Se o fontSize não estiver dentro do intervalo especificado.

### getAllLevels {#getAllLevels--}
```
public final com.aspose.ms.System.Collections.IEnumerable< Double > getAllLevels()
```

Obtém todos os níveis de cabeçalho.

**Returns:**
IEnumerable of Double
