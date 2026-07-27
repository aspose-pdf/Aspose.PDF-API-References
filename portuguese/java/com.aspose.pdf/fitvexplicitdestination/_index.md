---
title: "FitVExplicitDestination"
linktitle: "FitVExplicitDestination"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa um destino explícito que exibe a página com a coordenada horizontal esquerda posicionada na borda esquerda da janela e o conteúdo da página apenas ampliado."
type: docs
weight: 1580
url: /pt/java/com.aspose.pdf/fitvexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitVExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitVExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitVExplicitDestination extends ExplicitDestination
```

Representa um destino explícito que exibe a página com a coordenada horizontal esquerda posicionada na borda esquerda da janela e o conteúdo da página ampliado apenas o suficiente para que toda a altura da página caiba na janela. Um valor nulo para left indica que o valor atual desse parâmetro deve ser mantido inalterado.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [FitVExplicitDestination](#FitVExplicitDestination-com.aspose.pdf.Document-int-double-) | Cria um destino explícito remoto. |
| [FitVExplicitDestination](#FitVExplicitDestination-int-double-) | Cria um destino explícito remoto. |
| [FitVExplicitDestination](#FitVExplicitDestination-com.aspose.pdf.Page-double-) | Cria a instância e a inicializa pelo objeto de página DOM e pelo parâmetro left. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getLeft](#getLeft--) | Obtém a coordenada horizontal esquerda posicionada na borda esquerda da janela. |
| [toString](#toString--) | Converte o estado do objeto em valor de string. Exemplo: "1 FitV 100". |

### FitVExplicitDestination {#FitVExplicitDestination-com.aspose.pdf.Document-int-double-}
Cria um destino explícito remoto.

### FitVExplicitDestination {#FitVExplicitDestination-int-double-}
```
public FitVExplicitDestination(int pageNumber, double left)
```

Cria um destino explícito remoto.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pageNumber |  | O número da página de destino do documento remoto. |
| esquerda |  | A coordenada horizontal esquerda posicionada na borda esquerda da janela. |

### FitVExplicitDestination {#FitVExplicitDestination-com.aspose.pdf.Page-double-}
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

Converte o estado do objeto em valor de string. Exemplo: "1 FitV 100".

**Returns:**
Valor string que representa o estado do objeto.
