---
title: "SubPathContainer"
linktitle: "SubPathContainer"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma classe contêiner para elementos gráficos."
type: docs
weight: 10
url: /pt/java/com.aspose.pdf.vector.extraction/subpathcontainer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.extraction.SubPathContainer

**All Implemented Interfaces:**
com.aspose.pdf.engine.utils.clustering.hierarchicalagglomerativeclustering.IDistanceMetric< SubPathContainer >, Comparable < SubPathContainer >

```
public class SubPathContainer extends Object implements com.aspose.pdf.engine.utils.clustering.hierarchicalagglomerativeclustering.IDistanceMetric< SubPathContainer >, Comparable < SubPathContainer >
```

Representa uma classe contêiner para elementos gráficos.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [SubPathContainer](#SubPathContainer--) | Instancia uma classe de contêiner para elementos gráficos. |
| [SubPathContainer](#SubPathContainer-com.aspose.pdf.vector.GraphicElement-) | Instancia uma classe de contêiner para elementos gráficos. |
| [SubPathContainer](#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-) | Instancia uma classe de contêiner para elementos gráficos. |
| [SubPathContainer](#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-com.aspose.pdf.Rectangle-) | Instancia uma classe de contêiner para elementos gráficos. |
| [SubPathContainer](#SubPathContainer-com.aspose.pdf.Rectangle-) | Instancia uma classe de contêiner para elementos gráficos. |

## Métodos

| Método | Descrição |
| --- | --- |
| [calculateDistance](#calculateDistance-com.aspose.pdf.vector.extraction.SubPathContainer-com.aspose.pdf.vector.extraction.SubPathContainer-) | Calcula a distância entre dois contêineres. |
| [compareTo](#compareTo-com.aspose.pdf.vector.extraction.SubPathContainer-) | Compara o objeto SubPathContainer atual com outro objeto SubPathContainer e retorna um inteiro que indica se o objeto atual é menor, igual ou maior que o outro objeto. Os objetos são comparados pelo seu ID numérico. |
| [distanceTo](#distanceTo-com.aspose.pdf.vector.extraction.SubPathContainer-) | Calcula a distância entre este contêiner e outro contêiner. |
| [getGraphElement](#getGraphElement--) | Obtém o elemento gráfico contido. |
| [getId](#getId--) | Obtém o Id do SubPathContainer. O Id é necessário para facilitar a depuração e a ordenação dos elementos durante a renderização. |
| [getRect](#getRect--) | Representa um retângulo do elemento contido. |
| [toString](#toString--) | {@code } |

### SubPathContainer {#SubPathContainer--}
```
public SubPathContainer()
```

Instancia uma classe de contêiner para elementos gráficos.

### SubPathContainer {#SubPathContainer-com.aspose.pdf.vector.GraphicElement-}
Instancia uma classe de contêiner para elementos gráficos.

### SubPathContainer {#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-}
Instancia uma classe de contêiner para elementos gráficos.

### SubPathContainer {#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-com.aspose.pdf.Rectangle-}
Instancia uma classe de contêiner para elementos gráficos.

### SubPathContainer {#SubPathContainer-com.aspose.pdf.Rectangle-}
Instancia uma classe de contêiner para elementos gráficos.

### calculateDistance {#calculateDistance-com.aspose.pdf.vector.extraction.SubPathContainer-com.aspose.pdf.vector.extraction.SubPathContainer-}
Calcula a distância entre dois contêineres.

### compareTo {#compareTo-com.aspose.pdf.vector.extraction.SubPathContainer-}
Compara o objeto SubPathContainer atual com outro objeto SubPathContainer e retorna um inteiro que indica se o objeto atual é menor, igual ou maior que o outro objeto. Os objetos são comparados pelo seu ID numérico.

### distanceTo {#distanceTo-com.aspose.pdf.vector.extraction.SubPathContainer-}
Calcula a distância entre este contêiner e outro contêiner.

### getGraphElement {#getGraphElement--}
```
public final GraphicElement getGraphElement()
```

Obtém o elemento gráfico contido.

**Returns:**
Instância de GraphicElement

### getId {#getId--}
```
public final int getId()
```

Obtém o Id do SubPathContainer. O Id é necessário para facilitar a depuração e a ordenação dos elementos durante a renderização.

**Returns:**
valor int

### getRect {#getRect--}
```
public final Rectangle getRect()
```

Representa um retângulo do elemento contido.

**Returns:**
Instância de Rectangle

### toString {#toString--}
```
public String toString()
```

{@code }
