---
title: Class BlockTextOperator
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Operators.BlockTextOperator. Classe base astratta per operatori di blocco di testo, ovvero operatori di inizio e fine testo BT/ET
type: docs
weight: 7170
url: /it/net/aspose.pdf.operators/blocktextoperator/
---
## Classe BlockTextOperator

Classe base astratta per operatori di blocco di testo, ovvero operatori di inizio e fine testo (BT/ET)

```csharp
public class BlockTextOperator : TextOperator
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [BlockTextOperator](blocktextoperator/#constructor)() | Inizializza l'operatore. |
| [BlockTextOperator](blocktextoperator/#constructor_1)(TextProperties) | Inizializza BlockTextOperator che accetta TextProperties. |

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