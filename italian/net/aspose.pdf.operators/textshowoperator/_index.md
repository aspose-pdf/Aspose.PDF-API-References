---
title: "Classe TextShowOperator"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Operators.TextShowOperator. Classe base astratta per tutti gli operatori utilizzati per emettere testo Tj TJ ecc."
type: docs
weight: 8060
url: /it/net/aspose.pdf.operators/textshowoperator/
---
## TextShowOperator class

Classe base astratta per tutti gli operatori utilizzati per l'output del testo (Tj, TJ, ecc.).

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
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Indice dell'operatore nell'elenco degli operatori della pagina. |
| virtual [Text](../../aspose.pdf.operators/textshowoperator/text/) { get; set; } | Ottiene il testo che l'operatore restituisce sulla pagina. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/textoperator/accept/)(IOperatorSelector) | Accetta un oggetto visitor per elaborare l'operatore. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Restituisce il testo dell'operatore e i suoi parametri. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Confronta questa istanza con l'oggetto fornito. |

### Vedi anche

* class [TextOperator](../textoperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


