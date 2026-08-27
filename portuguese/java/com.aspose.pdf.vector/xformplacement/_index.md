---
title: "XFormPlacement"
linktitle: "XFormPlacement"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa o posicionamento do XForm. Se o XForm for exibido na página mais de uma vez, todas as XformPlacements associadas a este XForm terão elementos gráficos comuns, mas."
type: docs
weight: 70
url: /pt/java/com.aspose.pdf.vector/xformplacement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement com.aspose.pdf.vector.XFormPlacement, com.aspose.pdf.vector.GraphicElement, com.aspose.pdf.vector.XFormPlacement

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class XFormPlacement extends GraphicElement
```

Representa o posicionamento do XForm. Se o XForm for exibido na página mais de uma vez, todos os XformPlacements associados a esse XForm terão elementos gráficos comuns, mas estados gráficos diferentes.

## Métodos

| Método | Descrição |
| --- | --- |
| [addOnPage](#addOnPage-com.aspose.pdf.Page-) | Adiciona o elemento atual na página. Se houver muitos elementos para adicionar, é melhor usar Page#addGraphics(GraphicElementCollection,Rectangle). |
| [getElements](#getElements--) | Obtém os elementos gráficos dentro deste XForm. |
| [getName](#getName--) | Obtém o nome do XForm. |
| [getRectangle](#getRectangle--) | Obtém o retângulo delimitador do GraphicElement. |
| [getXForm](#getXForm--) | Obtém o XForm associado a este XFormPlacement. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Obtém ou define a posição no espaço de coordenadas atual. |

### addOnPage {#addOnPage-com.aspose.pdf.Page-}
Adiciona o elemento atual na página. Se houver muitos elementos para adicionar, é melhor usar Page#addGraphics(GraphicElementCollection,Rectangle).

### getElements {#getElements--}
```
public final GraphicElementCollection getElements()
```

Obtém os elementos gráficos dentro deste XForm.

**Returns:**
Instância de GraphicElementCollection

### getName {#getName--}
```
public final String getName()
```

Obtém o nome do XForm.

**Returns:**
valor String

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtém o retângulo delimitador do GraphicElement.

**Returns:**
Instância de Rectangle

### getXForm {#getXForm--}
```
public final XForm getXForm()
```

Obtém o XForm associado a este XFormPlacement.

**Returns:**
Instância de XForm

### setPosition {#setPosition-com.aspose.pdf.Point-}
Obtém ou define a posição no espaço de coordenadas atual.
