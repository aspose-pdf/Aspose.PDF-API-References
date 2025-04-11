---
title: Class BasicSetColorOperator
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Operators.BasicSetColorOperator. Classe base per gli operatori di impostazione del colore
type: docs
weight: 7160
url: /it/net/aspose.pdf.operators/basicsetcoloroperator/
---
## Classe BasicSetColorOperator

Classe base per gli operatori di impostazione del colore.

```csharp
public abstract class BasicSetColorOperator : SetColorOperator
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [B](../../aspose.pdf.operators/basicsetcoloroperator/b/) { get; } | Ottiene il componente rosso del colore |
| [C](../../aspose.pdf.operators/basicsetcoloroperator/c/) { get; } | Ottiene il componente ciano del colore CMYK. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Ottiene l'array dei componenti del colore. |
| [G](../../aspose.pdf.operators/basicsetcoloroperator/g/) { get; } | Ottiene il componente verde del colore |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Ottiene il componente nero del colore grigio. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Indice dell'operatore nell'elenco degli operatori di pagina. |
| [K](../../aspose.pdf.operators/basicsetcoloroperator/k/) { get; } | Ottiene il componente nero del colore CMYK. |
| [M](../../aspose.pdf.operators/basicsetcoloroperator/m/) { get; } | Ottiene il componente magenta del colore CMYK. |
| [R](../../aspose.pdf.operators/basicsetcoloroperator/r/) { get; } | Ottiene il componente rosso del colore |
| [Y](../../aspose.pdf.operators/basicsetcoloroperator/y/) { get; } | Ottiene il componente giallo del colore CMYK. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| abstract [Accept](../../aspose.pdf/operator/accept/)(IOperatorSelector) | Accetta il visitatore IOperatorSelector che fornisce l'elaborazione degli operatori. |
| abstract [getColor](../../aspose.pdf.operators/setcoloroperator/getcolor/)() | Restituisce il colore specificato dall'operatore. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Restituisce il testo dell'operatore e dei suoi parametri. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Confronta questa istanza con l'oggetto fornito. |

### Vedi Anche

* classe [SetColorOperator](../setcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)