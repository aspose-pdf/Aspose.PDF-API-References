---
title: "XYZExplicitDestination"
linktitle: "XYZExplicitDestination"
second_title: "Referência da API Aspose.PDF para Java"
description: "<p> Representa um destino explícito que exibe a página com as coordenadas (esquerda, superior) posicionadas no canto superior esquerdo da janela e o conteúdo da página."
type: docs
weight: 5800
url: /pt/java/com.aspose.pdf/xyzexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.XYZExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.XYZExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class XYZExplicitDestination extends ExplicitDestination
```

<p> Representa destino explícito que exibe a página com as coordenadas (esquerda, superior) posicionadas no canto superior esquerdo da janela e o conteúdo da página ampliado pelo fator zoom. Um valor nulo para qualquer um dos parâmetros esquerda, superior ou zoom especifica que o valor atual desse parâmetro deve ser mantido inalterado. Um valor de zoom igual a 0 tem o mesmo significado que um valor nulo. </p> <hr> <p> <code> Document doc = new Document("example.pdf"); XYZExplicitDestination dest = (XYZExplicitDestination)doc.getOutlines().get_Item(1).getDestination(); String left = dest.getLeft(); String top = dest.getTop(); String zoom = dest.getZoom(); </code> </p>

## Construtores

| Construtor | Descrição |
| --- | --- |
| [XYZExplicitDestination](#XYZExplicitDestination-com.aspose.pdf.IDocument-int-double-double-double-) | Cria um destino explícito remoto. |
| [XYZExplicitDestination](#XYZExplicitDestination-int-double-double-double-) | Cria um destino explícito remoto. |
| [XYZExplicitDestination](#XYZExplicitDestination-com.aspose.pdf.Page-double-double-double-) | Cria a instância e a inicializa pelo objeto de página DOM e pelos parâmetros visíveis. |

## Métodos

| Método | Descrição |
| --- | --- |
| [createDestination](#createDestination-com.aspose.pdf.Page-double-double-double-boolean-) | Cria o destino para a localização especificada da página, considerando a rotação da página se necessário. |
| [createDestinationToUpperLeftCorner](#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-) | Cria o destino para a página especificada. |
| [createDestinationToUpperLeftCorner](#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-double-) | Cria o destino para o canto superior esquerdo da página especificada. |
| [getLeft](#getLeft--) | Obtém a coordenada horizontal esquerda do canto superior esquerdo da janela. |
| [getTop](#getTop--) | Obtém a coordenada vertical superior do canto superior esquerdo da janela. |
| [getZoom](#getZoom--) | Obtém o fator de zoom. |
| [toString](#toString--) | Converte o estado do objeto em valor de string. Exemplo: "1 XYZ 100 200 3". |

### XYZExplicitDestination {#XYZExplicitDestination-com.aspose.pdf.IDocument-int-double-double-double-}
Cria um destino explícito remoto.

### XYZExplicitDestination {#XYZExplicitDestination-int-double-double-double-}
```
public XYZExplicitDestination(int pageNumber, double left, double top, double zoom)
```

Cria um destino explícito remoto.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pageNumber |  | O número da página de destino do documento remoto. |
| esquerda |  | Coordenada horizontal esquerda do canto superior esquerdo da janela. |
| superior |  | Coordenada vertical superior do canto superior esquerdo da janela. |
| zoom |  | Fator de zoom. |

### XYZExplicitDestination {#XYZExplicitDestination-com.aspose.pdf.Page-double-double-double-}
Cria a instância e a inicializa pelo objeto de página DOM e pelos parâmetros visíveis.

### createDestination {#createDestination-com.aspose.pdf.Page-double-double-double-boolean-}
Cria o destino para a localização especificada da página, considerando a rotação da página se necessário.

### createDestinationToUpperLeftCorner {#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-}
Cria o destino para a página especificada.

### createDestinationToUpperLeftCorner {#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-double-}
Cria o destino para o canto superior esquerdo da página especificada.

### getLeft {#getLeft--}
```
public double getLeft()
```

Obtém a coordenada horizontal esquerda do canto superior esquerdo da janela.

**Returns:**
double

### getTop {#getTop--}
```
public double getTop()
```

Obtém a coordenada vertical superior do canto superior esquerdo da janela.

**Returns:**
double

### getZoom {#getZoom--}
```
public double getZoom()
```

Obtém o fator de zoom.

**Returns:**
double

### toString {#toString--}
```
public String toString()
```

Converte o estado do objeto em valor de string. Exemplo: "1 XYZ 100 200 3".

**Returns:**
Valor string que representa o estado do objeto.
