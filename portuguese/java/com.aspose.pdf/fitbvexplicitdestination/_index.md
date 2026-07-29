---
title: "FitBVExplicitDestination"
linktitle: "FitBVExplicitDestination"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa um destino explícito que exibe a página com a coordenada horizontal esquerda posicionada na borda esquerda da janela e o conteúdo da página apenas ampliado."
type: docs
weight: 1540
url: /pt/java/com.aspose.pdf/fitbvexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitBVExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitBVExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitBVExplicitDestination extends ExplicitDestination
```

Representa um destino explícito que exibe a página com a coordenada horizontal esquerda posicionada na borda esquerda da janela e o conteúdo da página ampliado apenas o suficiente para que toda a altura de sua caixa delimitadora caiba na janela. Um valor nulo para left indica que o valor atual desse parâmetro deve ser mantido inalterado.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [FitBVExplicitDestination](#FitBVExplicitDestination-com.aspose.pdf.Document-int-double-) | Cria um destino explícito remoto. |
| [FitBVExplicitDestination](#FitBVExplicitDestination-int-double-) | Cria um destino explícito remoto. |
| [FitBVExplicitDestination](#FitBVExplicitDestination-com.aspose.pdf.Page-double-) | Cria a instância e a inicializa pelo objeto de página DOM e pelo parâmetro left. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getLeft](#getLeft--) | Obtém a coordenada horizontal esquerda posicionada na borda esquerda da janela. |
| [toString](#toString--) | Converte o estado do objeto em valor de string. Exemplo: "1 FitBV 100". |

### FitBVExplicitDestination {#FitBVExplicitDestination-com.aspose.pdf.Document-int-double-}
Cria um destino explícito remoto.

### FitBVExplicitDestination {#FitBVExplicitDestination-int-double-}
```
public FitBVExplicitDestination(int pageNumber, double left)
```

Cria um destino explícito remoto.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pageNumber |  | O número da página de destino do documento remoto. |
| esquerda |  | A coordenada horizontal esquerda posicionada na borda esquerda da janela. |

### FitBVExplicitDestination {#FitBVExplicitDestination-com.aspose.pdf.Page-double-}
Cria a instância e a inicializa pelo objeto de página DOM e pelo parâmetro left.

### getLeft {#getLeft--}
```
public double getLeft()
```

Obtém a coordenada horizontal esquerda posicionada na borda esquerda da janela.

**Returns:**
valor double

### toString {#toString--}
```
public String toString()
```

Converte o estado do objeto em valor de string. Exemplo: "1 FitBV 100".

**Returns:**
Valor string que representa o estado do objeto.
