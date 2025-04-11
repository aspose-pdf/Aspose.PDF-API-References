---
title: Class TextShowOperator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.TextShowOperator class. Abstract base class for all operators which used to out text Tj TJ etc
type: docs
weight: 7920
url: /it/net/aspose.pdf.operators/textshowoperator/
---
## Classe TextShowOperator

Classe base astratta per tutti gli operatori utilizzati per visualizzare testo (Tj, TJ, ecc).

```csharp
public class TextShowOperator : TextOperator
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextShowOperator](textshowoperator/#constructor)() | Inizializza TextShowOperator. |
| [TextShowOperator](textshowoperator/#constructor_1)(TextProperties) | Inizializza TextShowOperator che consente di passare TextProperties. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Indice dell'operatore nell'elenco degli operatori di pagina. |
| virtual [Text](../../aspose.pdf.operators/textshowoperator/text/) { get; set; } | Ottiene il testo che l'operatore visualizza sulla pagina. |

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