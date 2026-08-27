---
title: "FitBHExplicitDestination"
linktitle: "FitBHExplicitDestination"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa um destino explícito que exibe a página com a coordenada vertical superior posicionada na borda superior da janela e o conteúdo da página ampliado apenas."
type: docs
weight: 1530
url: /pt/java/com.aspose.pdf/fitbhexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitBHExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitBHExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitBHExplicitDestination extends ExplicitDestination
```

Representa um destino explícito que exibe a página com a coordenada vertical superior posicionada na borda superior da janela e o conteúdo da página ampliado apenas o suficiente para que toda a largura de sua caixa delimitadora caiba na janela. Um valor nulo para top indica que o valor atual desse parâmetro deve ser mantido inalterado.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [FitBHExplicitDestination](#FitBHExplicitDestination-com.aspose.pdf.Document-int-double-) | Cria um destino explícito remoto. |
| [FitBHExplicitDestination](#FitBHExplicitDestination-int-double-) | Cria um destino explícito remoto. |
| [FitBHExplicitDestination](#FitBHExplicitDestination-com.aspose.pdf.Page-double-) | Cria a instância e a inicializa com o objeto de página DOM e o parâmetro top. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getTop](#getTop--) | Obtém a coordenada vertical superior posicionada na borda superior da janela. |
| [toString](#toString--) | Converte o estado do objeto em valor de string. Exemplo: "1 FitBH 100". |

### FitBHExplicitDestination {#FitBHExplicitDestination-com.aspose.pdf.Document-int-double-}
Cria um destino explícito remoto.

### FitBHExplicitDestination {#FitBHExplicitDestination-int-double-}
```
public FitBHExplicitDestination(int pageNumber, double top)
```

Cria um destino explícito remoto.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pageNumber |  | O número da página de destino do documento remoto. |
| superior |  | A coordenada vertical superior posicionada na borda superior da janela. |

### FitBHExplicitDestination {#FitBHExplicitDestination-com.aspose.pdf.Page-double-}
Cria a instância e a inicializa com o objeto de página DOM e o parâmetro top.

### getTop {#getTop--}
```
public double getTop()
```

Obtém a coordenada vertical superior posicionada na borda superior da janela.

**Returns:**
valor double

### toString {#toString--}
```
public String toString()
```

Converte o estado do objeto em valor de string. Exemplo: "1 FitBH 100".

**Returns:**
Valor string que representa o estado do objeto.
