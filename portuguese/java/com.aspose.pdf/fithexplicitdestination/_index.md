---
title: "FitHExplicitDestination"
linktitle: "FitHExplicitDestination"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa um destino explícito que exibe a página com a coordenada vertical superior posicionada na borda superior da janela e o conteúdo da página ampliado apenas."
type: docs
weight: 1560
url: /pt/java/com.aspose.pdf/fithexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitHExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitHExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitHExplicitDestination extends ExplicitDestination
```

Representa um destino explícito que exibe a página com a coordenada vertical superior posicionada na borda superior da janela e o conteúdo da página ampliado apenas o suficiente para que toda a largura da página caiba na janela. Um valor nulo para top indica que o valor atual desse parâmetro deve ser mantido inalterado.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [FitHExplicitDestination](#FitHExplicitDestination-com.aspose.pdf.Document-int-double-) | Cria um destino explícito remoto. |
| [FitHExplicitDestination](#FitHExplicitDestination-int-double-) | Cria um destino explícito remoto. |
| [FitHExplicitDestination](#FitHExplicitDestination-com.aspose.pdf.Page-double-) | Cria a instância e a inicializa com o objeto de página DOM e o parâmetro top. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getTop](#getTop--) | Obtém a coordenada vertical superior posicionada na borda superior da janela. |
| [toString](#toString--) | Converte o estado do objeto em valor de string. Exemplo: "1 FitH 100". |

### FitHExplicitDestination {#FitHExplicitDestination-com.aspose.pdf.Document-int-double-}
Cria um destino explícito remoto.

### FitHExplicitDestination {#FitHExplicitDestination-int-double-}
```
public FitHExplicitDestination(int pageNumber, double top)
```

Cria um destino explícito remoto.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pageNumber |  | O número da página de destino do documento remoto. |
| superior |  | A coordenada vertical superior posicionada na borda superior da janela. |

### FitHExplicitDestination {#FitHExplicitDestination-com.aspose.pdf.Page-double-}
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

Converte o estado do objeto em valor de string. Exemplo: "1 FitH 100".

**Returns:**
Valor string que representa o estado do objeto.
