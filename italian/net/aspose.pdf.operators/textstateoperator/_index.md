---
title: Class TextStateOperator
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Operators.TextStateOperator. Classe base astratta per operatori che cambiano lo stato del testo corrente Tc Tf TL ecc
type: docs
weight: 7930
url: /it/net/aspose.pdf.operators/textstateoperator/
---
## Classe TextStateOperator

Classe base astratta per operatori che cambiano lo stato del testo corrente (Tc, Tf, TL, ecc).

```csharp
public class TextStateOperator : TextOperator
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextStateOperator](textstateoperator/#constructor)() | Inizializza TextStateOperator. |
| [TextStateOperator](textstateoperator/#constructor_1)(TextProperties) | Inizializza TextStateOperator che consente di passare TextProperties. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Indice dell'operatore nell'elenco degli operatori di pagina. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/textoperator/accept/)(IOperatorSelector) | Accetta l'oggetto visitatore per elaborare l'operatore. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Restituisce il testo dell'operatore e i suoi parametri. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Confronta questa istanza con l'oggetto fornito. |

### Vedi Anche

* classe [TextOperator](../textoperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)