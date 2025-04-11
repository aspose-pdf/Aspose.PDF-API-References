---
title: Class SetColorStroke
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Operators.SetColorStroke. Classe che rappresenta l'operatore SC per impostare il colore per gli operatori di colore di tracciamento
type: docs
weight: 7680
url: /it/net/aspose.pdf.operators/setcolorstroke/
---
## Classe SetColorStroke

Classe che rappresenta l'operatore SC per impostare il colore per gli operatori di colore di tracciamento.

```csharp
public class SetColorStroke : BasicSetColorOperator
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SetColorStroke](setcolorstroke/#constructor)() | Inizializza l'operatore. |
| [SetColorStroke](setcolorstroke/#constructor_1)(double) | Imposta il colore per gli operatori di tracciamento per gli spazi colore DeviceGray, CalGray e Indexed. |
| [SetColorStroke](setcolorstroke/#constructor_4)(double[]) | Costruttore che consente di impostare i componenti di colore. |
| [SetColorStroke](setcolorstroke/#constructor_2)(double, double, double) | Imposta il colore per l'operatore di tracciamento per gli spazi colore DeviceRGB, CalRGB e Lab. |
| [SetColorStroke](setcolorstroke/#constructor_3)(double, double, double, double) | Imposta il colore per l'operatore di tracciamento per lo spazio colore CMYK. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolorstroke/b/) { get; set; } | Ottiene o imposta il componente blu. |
| [C](../../aspose.pdf.operators/setcolorstroke/c/) { get; set; } | Ottiene o imposta il componente ciano. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Ottiene l'array dei componenti di colore. |
| [G](../../aspose.pdf.operators/setcolorstroke/g/) { get; set; } | Ottiene o imposta il componente verde. |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Ottiene il componente nero del colore grigio. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Indice dell'operatore nell'elenco degli operatori di pagina. |
| [K](../../aspose.pdf.operators/setcolorstroke/k/) { get; set; } | Ottiene o imposta il componente nero. |
| [M](../../aspose.pdf.operators/setcolorstroke/m/) { get; set; } | Ottiene o imposta il componente magenta. |
| [R](../../aspose.pdf.operators/setcolorstroke/r/) { get; set; } | Ottiene o imposta il componente rosso. |
| [Y](../../aspose.pdf.operators/setcolorstroke/y/) { get; set; } | Ottiene o imposta il componente giallo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolorstroke/accept/)(IOperatorSelector) | Accetta l'oggetto visitatore per elaborare l'operatore. |
| override [getColor](../../aspose.pdf.operators/setcolorstroke/getcolor/)() | Restituisce il colore specificato dall'operatore. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Restituisce il testo dell'operatore e i suoi parametri. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Confronta questa istanza con l'oggetto fornito. |

### Vedi Anche

* classe [BasicSetColorOperator](../basicsetcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)