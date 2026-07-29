---
title: "FitRExplicitDestination"
linktitle: "FitRExplicitDestination"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa um destino explícito que exibe a página com seu conteúdo ampliado apenas o suficiente para caber no retângulo especificado pelas coordenadas esquerda, inferior, direita e."
type: docs
weight: 1570
url: /pt/java/com.aspose.pdf/fitrexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitRExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitRExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitRExplicitDestination extends ExplicitDestination
```

Representa um destino explícito que exibe a página com seu conteúdo ampliado apenas o suficiente para que o retângulo especificado pelas coordenadas left, bottom, right e top caiba totalmente na janela, tanto horizontal quanto verticalmente. Se os fatores de ampliação horizontal e vertical necessários forem diferentes, use o menor dos dois, centralizando o retângulo na janela na outra dimensão. Um valor nulo para qualquer um dos parâmetros pode resultar em comportamento imprevisível.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [FitRExplicitDestination](#FitRExplicitDestination-com.aspose.pdf.Document-int-double-double-double-double-) | Cria um destino explícito remoto. |
| [FitRExplicitDestination](#FitRExplicitDestination-int-double-double-double-double-) | Cria um destino explícito remoto. |
| [FitRExplicitDestination](#FitRExplicitDestination-com.aspose.pdf.Page-double-double-double-double-) | Cria a instância e a inicializa pelo objeto de página DOM e pelos parâmetros visíveis. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getBottom](#getBottom--) | Obtém a coordenada vertical inferior do retângulo visível. |
| [getLeft](#getLeft--) | Obtém a coordenada horizontal esquerda do retângulo visível. |
| [getRight](#getRight--) | Obtém a coordenada horizontal direita do retângulo visível. |
| [getTop](#getTop--) | Obtém a coordenada vertical superior do retângulo visível. |
| [toString](#toString--) | Converte o estado do objeto em valor de string. Exemplo: "1 FitR 100 200 300 400". |

### FitRExplicitDestination {#FitRExplicitDestination-com.aspose.pdf.Document-int-double-double-double-double-}
Cria um destino explícito remoto.

### FitRExplicitDestination {#FitRExplicitDestination-int-double-double-double-double-}
```
public FitRExplicitDestination(int pageNumber, double left, double bottom, double right, double top)
```

Cria um destino explícito remoto.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pageNumber |  | O número da página de destino do documento remoto. |
| esquerda |  | Coordenada horizontal esquerda do retângulo visível. |
| inferior |  | Coordenada vertical inferior do retângulo visível. |
| direita |  | Coordenada horizontal direita do retângulo visível. |
| superior |  | Coordenada vertical superior do retângulo visível. |

### FitRExplicitDestination {#FitRExplicitDestination-com.aspose.pdf.Page-double-double-double-double-}
Cria a instância e a inicializa pelo objeto de página DOM e pelos parâmetros visíveis.

### getBottom {#getBottom--}
```
public double getBottom()
```

Obtém a coordenada vertical inferior do retângulo visível.

**Returns:**
valor double

### getLeft {#getLeft--}
```
public double getLeft()
```

Obtém a coordenada horizontal esquerda do retângulo visível.

**Returns:**
valor double

### getRight {#getRight--}
```
public double getRight()
```

Obtém a coordenada horizontal direita do retângulo visível.

**Returns:**
valor double

### getTop {#getTop--}
```
public double getTop()
```

Obtém a coordenada vertical superior do retângulo visível.

**Returns:**
valor double

### toString {#toString--}
```
public String toString()
```

Converte o estado do objeto em valor de string. Exemplo: "1 FitR 100 200 300 400".

**Returns:**
Valor string que representa o estado do objeto.
