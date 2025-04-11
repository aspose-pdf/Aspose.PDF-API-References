---
title: Class Operator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operator class. Abstract class representing operator
type: docs
weight: 7070
url: /it/net/aspose.pdf/operator/
---
## Classe Operatore

Classe astratta che rappresenta un operatore.

```csharp
public abstract class Operator
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Indice dell'operatore nell'elenco degli operatori della pagina. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| abstract [Accept](../../aspose.pdf/operator/accept/)(IOperatorSelector) | Accetta il visitatore IOperatorSelector che fornisce l'elaborazione degli operatori. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Restituisce il testo dell'operatore e i suoi parametri. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Confronta questa istanza con l'oggetto fornito. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(Operator) | Determina se l'operatore è un operatore responsabile dell'output di testo (Tj, TJ, ecc.) |

### Vedi Anche

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)