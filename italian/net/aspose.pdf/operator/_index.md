---
title: "Classe Operator"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Operator. Classe astratta che rappresenta un operatore."
type: docs
weight: 7210
url: /it/net/aspose.pdf/operator/
---
## Operator class

Classe astratta che rappresenta l'operatore.

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
| abstract [Accept](../../aspose.pdf/operator/accept/)(IOperatorSelector) | Accetta il visitor IOperatorSelector che fornisce l'elaborazione degli operatori. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Restituisce il testo dell'operatore e i suoi parametri. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Confronta questa istanza con l'oggetto fornito. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(Operator) | Determina se l'operatore è quello responsabile dell'output di testo (Tj, TJ, ecc). |

### Vedi anche

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


