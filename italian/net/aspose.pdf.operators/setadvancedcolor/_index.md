---
title: Class SetAdvancedColor
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Operators.SetAdvancedColor. Classe che rappresenta l'operatore scn per impostare il colore per operazioni non di tracciamento
type: docs
weight: 7560
url: /it/net/aspose.pdf.operators/setadvancedcolor/
---
## Classe SetAdvancedColor

Classe che rappresenta l'operatore scn (imposta il colore per operazioni non di tracciamento).

```csharp
public class SetAdvancedColor : BasicSetColorAndPatternOperator
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SetAdvancedColor](setadvancedcolor/#constructor)() | Inizializza l'operatore. |
| [SetAdvancedColor](setadvancedcolor/#constructor_1)(double) | Costruttore per l'operatore scn. |
| [SetAdvancedColor](setadvancedcolor/#constructor_6)(string) | Costruttore per l'operatore scn. |
| [SetAdvancedColor](setadvancedcolor/#constructor_4)(double, string) | Costruttore per l'operatore scn. |
| [SetAdvancedColor](setadvancedcolor/#constructor_5)(double[], string) | Costruttore per l'operatore scn. |
| [SetAdvancedColor](setadvancedcolor/#constructor_3)(double, double, double, string) | Costruttore per l'operatore scn. |
| [SetAdvancedColor](setadvancedcolor/#constructor_2)(double, double, double, double, string) | Costruttore per l'operatore scn. |

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
| override [Accept](../../aspose.pdf.operators/setadvancedcolor/accept/)(IOperatorSelector) | Accetta l'oggetto visitatore per elaborare l'operatore. |
| override [getColor](../../aspose.pdf.operators/setadvancedcolor/getcolor/)() | Restituisce il colore specificato dall'operatore. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Restituisce il testo dell'operatore e dei suoi parametri. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Confronta questa istanza con l'oggetto fornito. |

### Vedi Anche

* classe [BasicSetColorAndPatternOperator](../basicsetcolorandpatternoperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)