---
title: "FitBExplicitDestination"
linktitle: "FitBExplicitDestination"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa um destino explícito que exibe a página com seu conteúdo ampliado o suficiente para que sua caixa delimitadora caiba inteiramente na janela tanto horizontalmente quanto verticalmente."
type: docs
weight: 1520
url: /pt/java/com.aspose.pdf/fitbexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitBExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitBExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitBExplicitDestination extends ExplicitDestination
```

Representa um destino explícito que exibe a página com seu conteúdo ampliado apenas o suficiente para que sua caixa delimitadora caiba totalmente na janela, tanto horizontal quanto verticalmente. Se os fatores de ampliação horizontal e vertical necessários forem diferentes, use o menor dos dois, centralizando a caixa delimitadora na janela na outra dimensão.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [FitBExplicitDestination](#FitBExplicitDestination-com.aspose.pdf.Document-int-) | Cria um destino explícito remoto. |
| [FitBExplicitDestination](#FitBExplicitDestination-int-) | Cria um destino explícito remoto. |
| [FitBExplicitDestination](#FitBExplicitDestination-com.aspose.pdf.Page-) | Cria a instância e a inicializa pelo objeto de página DOM. |

## Métodos

| Método | Descrição |
| --- | --- |
| [toString](#toString--) | Converte o estado do objeto em valor de string. Exemplo: "1 FitB". |

### FitBExplicitDestination {#FitBExplicitDestination-com.aspose.pdf.Document-int-}
Cria um destino explícito remoto.

### FitBExplicitDestination {#FitBExplicitDestination-int-}
```
public FitBExplicitDestination(int pageNumber)
```

Cria um destino explícito remoto.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pageNumber |  | O número da página de destino do documento remoto. |

### FitBExplicitDestination {#FitBExplicitDestination-com.aspose.pdf.Page-}
Cria a instância e a inicializa pelo objeto de página DOM.

### toString {#toString--}
```
public String toString()
```

Converte o estado do objeto em valor de string. Exemplo: "1 FitB".

**Returns:**
Valor string que representa o estado do objeto.
