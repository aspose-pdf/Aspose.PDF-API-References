---
title: Class SetAdvancedColorStroke
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Operators.SetAdvancedColorStroke. Classe che rappresenta l'operatore SCN per impostare il colore per le operazioni di tracciamento
type: docs
weight: 7570
url: /it/net/aspose.pdf.operators/setadvancedcolorstroke/
---
## Classe SetAdvancedColorStroke

Classe che rappresenta l'operatore SCN (imposta il colore per le operazioni di tracciamento).

```csharp
public class SetAdvancedColorStroke : BasicSetColorAndPatternOperator
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor)() | Inizializza l'operatore. |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor_1)(double) | Costruttore per l'operatore scn |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor_4)(double, string) | Costruttore per l'operatore scn. |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor_5)(double[], string) | Costruttore per l'operatore scn. |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor_3)(double, double, double, string) | Costruttore per l'operatore scn. |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor_2)(double, double, double, double, string) | Costruttore per l'operatore scn. |

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
| [PatternName](../../aspose.pdf.operators/basicsetcolorandpatternoperator/patternname/) { get; } | Ottiene il nome del pattern. |
| [R](../../aspose.pdf.operators/basicsetcoloroperator/r/) { get; } | Ottiene il componente rosso del colore |
| [Y](../../aspose.pdf.operators/basicsetcoloroperator/y/) { get; } | Ottiene il componente giallo del colore CMYK. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setadvancedcolorstroke/accept/)(IOperatorSelector) | Accetta l'oggetto visitatore per elaborare l'operatore. |
| override [getColor](../../aspose.pdf.operators/setadvancedcolorstroke/getcolor/)() | Restituisce il colore specificato dall'operatore. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Restituisce il testo dell'operatore e dei suoi parametri. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Confronta questa istanza con l'oggetto fornito. |

### Vedi Anche

* classe [BasicSetColorAndPatternOperator](../basicsetcolorandpatternoperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)