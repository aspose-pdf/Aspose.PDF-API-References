---
title: Class SetColor
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Operators.SetColor. Rappresenta la classe per l'operatore sc per impostare il colore per operazioni non di tracciamento
type: docs
weight: 7630
url: /it/net/aspose.pdf.operators/setcolor/
---
## Classe SetColor

Rappresenta la classe per l'operatore sc (imposta il colore per operazioni non di tracciamento).

```csharp
public class SetColor : BasicSetColorOperator
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SetColor](setcolor/#constructor)() | Inizializza l'operatore. |
| [SetColor](setcolor/#constructor_1)(double) | Imposta il colore per gli operatori di tracciamento per gli spazi colore DeviceGray, CalGray e Indexed. |
| [SetColor](setcolor/#constructor_4)(double[]) | Costruttore che consente di specificare i componenti del colore. |
| [SetColor](setcolor/#constructor_2)(double, double, double) | Imposta il colore per l'operatore di tracciamento per gli spazi colore DeviceRGB, CalRGB e Lab. |
| [SetColor](setcolor/#constructor_3)(double, double, double, double) | Imposta il colore per l'operatore non di tracciamento per lo spazio colore CMYK. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolor/b/) { get; set; } | Ottiene o imposta il componente blu. |
| [C](../../aspose.pdf.operators/setcolor/c/) { get; set; } | Ottiene o imposta il componente ciano. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Ottiene l'array dei componenti del colore. |
| [G](../../aspose.pdf.operators/setcolor/g/) { get; set; } | Ottiene o imposta il componente verde. |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Ottiene il componente nero del colore grigio. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Indice dell'operatore nell'elenco degli operatori di pagina. |
| [K](../../aspose.pdf.operators/setcolor/k/) { get; set; } | Ottiene o imposta il componente nero. |
| [M](../../aspose.pdf.operators/setcolor/m/) { get; set; } | Ottiene o imposta il componente magenta. |
| [R](../../aspose.pdf.operators/setcolor/r/) { get; set; } | Ottiene o imposta il componente rosso. |
| [Y](../../aspose.pdf.operators/setcolor/y/) { get; set; } | Ottiene o imposta il componente giallo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolor/accept/)(IOperatorSelector) | Accetta l'oggetto visitatore per elaborare l'operatore. |
| override [getColor](../../aspose.pdf.operators/setcolor/getcolor/)() | Restituisce il colore specificato dall'operatore. |
| override [ToString](../../aspose.pdf.operators/setcolor/tostring/)() | Restituisce la rappresentazione in stringa del colore. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Confronta questa istanza con l'oggetto fornito. |

### Vedi Anche

* classe [BasicSetColorOperator](../basicsetcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)