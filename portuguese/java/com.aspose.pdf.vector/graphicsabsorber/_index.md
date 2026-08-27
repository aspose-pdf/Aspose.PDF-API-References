---
title: "GraphicsAbsorber"
linktitle: "GraphicsAbsorber"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa um objeto absorvedor de elementos gráficos. Executa a busca de gráficos e fornece acesso aos resultados da busca via {@code GraphicsAbsorber.Elements}({@link."
type: docs
weight: 30
url: /pt/java/com.aspose.pdf.vector/graphicsabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicsAbsorber

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public class GraphicsAbsorber extends Object implements com.aspose.ms.System.IDisposable
```

Representa um objeto absorvedor de elementos gráficos. Executa a busca gráfica e fornece acesso aos resultados da busca via coleção {@code GraphicsAbsorber.Elements}({@link GraphicsAbsorber#getElements}).

## Construtores

| Construtor | Descrição |
| --- | --- |
| [GraphicsAbsorber](#GraphicsAbsorber--) |  |

## Métodos

| Método | Descrição |
| --- | --- |
| [dispose](#dispose--) | Libera todos os recursos usados pela classe {@link GraphicsAbsorber}. |
| [getElements](#getElements--) | Obtém a coleção de ocorrências de pesquisa que são apresentadas com objetos {@link GraphicElement}. |
| [resumeUpdate](#resumeUpdate--) | Retoma a atualização para forPage#getContents e todos @link XForm#getContents. Foi feita para aumento de desempenho, veja também. |
| [suppressUpdate](#suppressUpdate--) | Suprime a atualização para Page#getContents e todos @link XForm#getContents. Foi feita para aumento de desempenho, veja também. |
| [visit](#visit-com.aspose.pdf.Page-) | Executa a pesquisa na página especificada. |

### GraphicsAbsorber {#GraphicsAbsorber--}
```
public GraphicsAbsorber()
```



### dispose {#dispose--}
```
public final void dispose()
```

Libera todos os recursos usados pela classe {@link GraphicsAbsorber}.

### getElements {#getElements--}
```
public final GraphicElementCollection getElements()
```

Obtém a coleção de ocorrências de pesquisa que são apresentadas com objetos {@link GraphicElement}.

**Returns:**
Instância de GraphicElementCollection

### resumeUpdate {#resumeUpdate--}
```
public final void resumeUpdate()
```

Retoma a atualização para forPage#getContents e todos @link XForm#getContents. Foi feita para aumento de desempenho, veja também.

### suppressUpdate {#suppressUpdate--}
```
public final void suppressUpdate()
```

Suprime a atualização para Page#getContents e todos @link XForm#getContents. Foi feita para aumento de desempenho, veja também.

### visit {#visit-com.aspose.pdf.Page-}
Executa a pesquisa na página especificada.
