---
title: "GraphicElement"
linktitle: "GraphicElement"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa a classe base para objeto gráfico na página."
type: docs
weight: 10
url: /pt/java/com.aspose.pdf.vector/graphicelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public abstract class GraphicElement extends Object implements com.aspose.ms.System.IDisposable
```

Representa a classe base para objeto gráfico na página.

## Métodos

| Método | Descrição |
| --- | --- |
| [addOnPage](#addOnPage-com.aspose.pdf.Page-) | Adiciona o elemento atual na página. Se houver muitos elementos para adicionar, é melhor usar Page#addGraphics(GraphicElementCollection,Rectangle). |
| [dispose](#dispose--) | Libera todos os recursos usados pela classe {@link GraphicElement}. |
| [getMatrix](#getMatrix--) | Obtém a matriz do elemento gráfico. A matriz é definida quando o elemento é criado. Ela muda quando SetPosition() é chamado. |
| [getOperators](#getOperators--) | Obtém uma coleção de operadores que representam o elemento. |
| [getParent](#getParent--) | Obtém o {@link XFormPlacement} atual no qual o elemento está localizado. |
| [getPosition](#getPosition--) | Obtém ou define a posição no espaço de coordenadas atual. Se Parent #getParent/#setParent(XFormPlacement) não for nulo, então o elemento terá espaço de coordenadas xForm. |
| [getRectangle](#getRectangle--) | Obtém o retângulo delimitador do {@link GraphicElement}. |
| [getSourcePage](#getSourcePage--) | Obtém a página da qual o elemento gráfico é extraído. |
| [remove](#remove--) | Remove o elemento atual da página. Se houver muitos elementos para remover, é melhor usar Page#deleteGraphics(GraphicElementCollection). |
| [saveToSvg](#saveToSvg--) | Converte o elemento em uma única imagem SVG. |
| [saveToSvg](#saveToSvg-java.lang.String-) | Converte o elemento em uma única imagem SVG. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Obtém ou define a posição no espaço de coordenadas atual. Se Parent #getParent/#setParent(XFormPlacement) não for nulo, então o elemento terá espaço de coordenadas xForm. |

### addOnPage {#addOnPage-com.aspose.pdf.Page-}
Adiciona o elemento atual na página. Se houver muitos elementos para adicionar, é melhor usar Page#addGraphics(GraphicElementCollection,Rectangle).

### dispose {#dispose--}
```
public final void dispose()
```

Libera todos os recursos usados pela classe {@link GraphicElement}.

### getMatrix {#getMatrix--}
```
public final Matrix getMatrix()
```

Obtém a matriz do elemento gráfico. A matriz é definida quando o elemento é criado. Ela muda quando SetPosition() é chamado.

**Returns:**
Instância da matriz

### getOperators {#getOperators--}
```
public final List < Operator > getOperators()
```

Obtém uma coleção de operadores que representam o elemento.

**Returns:**
Lista de instâncias de Operador

### getParent {#getParent--}
```
public final XFormPlacement getParent()
```

Obtém o {@link XFormPlacement} atual no qual o elemento está localizado.

**Returns:**
Instância de XFormPlacement

### getPosition {#getPosition--}
```
public Point getPosition()
```

Obtém ou define a posição no espaço de coordenadas atual. Se Parent #getParent/#setParent(XFormPlacement) não for nulo, então o elemento terá espaço de coordenadas xForm.

**Returns:**
Instância de Point

### getRectangle {#getRectangle--}
```
public abstract Rectangle getRectangle()
```

Obtém o retângulo delimitador do {@link GraphicElement}.

**Returns:**
Instância de Rectangle

### getSourcePage {#getSourcePage--}
```
public final Page getSourcePage()
```

Obtém a página da qual o elemento gráfico é extraído.

**Returns:**
Instância da Página

### remove {#remove--}
```
public final void remove()
```

Remove o elemento atual da página. Se houver muitos elementos para remover, é melhor usar Page#deleteGraphics(GraphicElementCollection).

### saveToSvg {#saveToSvg--}
```
public final String saveToSvg()
```

Converte o elemento em uma única imagem SVG.

**Returns:**
A string SVG.

### saveToSvg {#saveToSvg-java.lang.String-}
Converte o elemento em uma única imagem SVG.

**Returns:**
A string SVG.

### setPosition {#setPosition-com.aspose.pdf.Point-}
Obtém ou define a posição no espaço de coordenadas atual. Se Parent #getParent/#setParent(XFormPlacement) não for nulo, então o elemento terá espaço de coordenadas xForm.
