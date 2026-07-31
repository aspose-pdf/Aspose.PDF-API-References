---
title: "Classe SetColor"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.Operators.SetColor classe. Rappresenta la classe per l'operatore sc impostare il colore per operazioni non di tracciatura"
type: docs
weight: 7770
url: /it/net/aspose.pdf.operators/setcolor/
---
## SetColor class

Rappresenta la classe per l'operatore sc (imposta il colore per operazioni di riempimento).

```csharp
public class SetColor : BasicSetColorOperator
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SetColor](setcolor/#constructor)() | Inizializza l'operatore. |
| [SetColor](setcolor/#constructor_1)(double) | Imposta il colore per gli operatori di tratto per gli spazi colore DeviceGray, CalGray e Indexed. |
| [SetColor](setcolor/#constructor_4)(double[]) | Costruttore che consente di specificare i componenti di colore. |
| [SetColor](setcolor/#constructor_2)(double, double, double) | Imposta il colore per l'operatore di tratto per gli spazi colore DeviceRGB, CalRGB e Lab |
| [SetColor](setcolor/#constructor_3)(double, double, double, double) | Imposta il colore per l'operatore non di tracciatura per lo spazio colore CMYK |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolor/b/) { get; set; } | Ottiene o imposta il componente blu. |
| [C](../../aspose.pdf.operators/setcolor/c/) { get; set; } | Ottiene o imposta il componente ciano. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Ottiene l'array dei componenti del colore. |
| [G](../../aspose.pdf.operators/setcolor/g/) { get; set; } | Ottiene o imposta il componente verde. |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Ottiene il componente nero del colore grigio. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Indice dell'operatore nell'elenco degli operatori della pagina. |
| [K](../../aspose.pdf.operators/setcolor/k/) { get; set; } | Ottiene o imposta il componente nero. |
| [M](../../aspose.pdf.operators/setcolor/m/) { get; set; } | Ottiene o imposta il componente magenta. |
| [R](../../aspose.pdf.operators/setcolor/r/) { get; set; } | Ottiene o imposta il componente rosso. |
| [Y](../../aspose.pdf.operators/setcolor/y/) { get; set; } | Ottiene o imposta il componente giallo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolor/accept/)(IOperatorSelector) | Accetta un oggetto visitor per elaborare l'operatore. |
| override [getColor](../../aspose.pdf.operators/setcolor/getcolor/)() | Restituisce il colore specificato dall'operatore. |
| override [ToString](../../aspose.pdf.operators/setcolor/tostring/)() | Restituisce la rappresentazione stringa del colore. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Confronta questa istanza con l'oggetto fornito. |

### Vedi anche

* class [BasicSetColorOperator](../basicsetcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


