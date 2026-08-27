---
title: "FitExplicitDestination"
linktitle: "FitExplicitDestination"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa um destino explícito que exibe a página com seu conteúdo ampliado o suficiente para ajustar a página inteira dentro da janela tanto horizontal quanto verticalmente. Se o"
type: docs
weight: 1550
url: /pt/java/com.aspose.pdf/fitexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitExplicitDestination extends ExplicitDestination
```

Representa um destino explícito que exibe a página com seu conteúdo ampliado apenas o suficiente para que a página inteira caiba na janela, tanto horizontal quanto verticalmente. Se os fatores de ampliação horizontal e vertical necessários forem diferentes, use o menor dos dois, centralizando a página na janela na outra dimensão.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [FitExplicitDestination](#FitExplicitDestination-com.aspose.pdf.Document-int-) | Cria um destino explícito remoto. |
| [FitExplicitDestination](#FitExplicitDestination-int-) | Cria um destino explícito remoto. |
| [FitExplicitDestination](#FitExplicitDestination-com.aspose.pdf.Page-) | Cria um destino explícito local. |

## Métodos

| Método | Descrição |
| --- | --- |
| [toString](#toString--) | Converte o estado do objeto em um valor string. Exemplo: "1 Fit". |

### FitExplicitDestination {#FitExplicitDestination-com.aspose.pdf.Document-int-}
Cria um destino explícito remoto.

### FitExplicitDestination {#FitExplicitDestination-int-}
```
public FitExplicitDestination(int pageNumber)
```

Cria um destino explícito remoto.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pageNumber |  | O número da página de destino do documento remoto. |

### FitExplicitDestination {#FitExplicitDestination-com.aspose.pdf.Page-}
Cria um destino explícito local.

### toString {#toString--}
```
public String toString()
```

Converte o estado do objeto em um valor string. Exemplo: "1 Fit".

**Returns:**
Valor string que representa o estado do objeto.
