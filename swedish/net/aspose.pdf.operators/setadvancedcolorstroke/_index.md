---
title: Class SetAdvancedColorStroke
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.SetAdvancedColorStroke klass. Klass som representerar SCN-operatorn för att ställa in färg för strekningsoperationer
type: docs
weight: 7570
url: /sv/net/aspose.pdf.operators/setadvancedcolorstroke/
---
## SetAdvancedColorStroke klass

Klass som representerar SCN-operatorn (ställer in färg för strekningsoperationer).

```csharp
public class SetAdvancedColorStroke : BasicSetColorAndPatternOperator
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor)() | Initierar operator. |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor_1)(double) | Konstruktör för scn-operator. |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor_4)(double, string) | Konstruktör för scn-operator. |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor_5)(double[], string) | Konstruktör för scn-operator. |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor_3)(double, double, double, string) | Konstruktör för scn-operator. |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor_2)(double, double, double, double, string) | Konstruktör för scn-operator. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [B](../../aspose.pdf.operators/basicsetcoloroperator/b/) { get; } | Hämtar röd komponent av färg |
| [C](../../aspose.pdf.operators/basicsetcoloroperator/c/) { get; } | Hämtar cyan komponent av CMYK-färg. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Hämtar array av färgkomponenter. |
| [G](../../aspose.pdf.operators/basicsetcoloroperator/g/) { get; } | Hämtar grön komponent av färg |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Hämtar svart komponent av grå färg. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operatorindex i listan över sidoperatorer. |
| [K](../../aspose.pdf.operators/basicsetcoloroperator/k/) { get; } | Hämtar svart komponent av CMYK-färg. |
| [M](../../aspose.pdf.operators/basicsetcoloroperator/m/) { get; } | Hämtar magenta komponent av CMYK-färg. |
| [PatternName](../../aspose.pdf.operators/basicsetcolorandpatternoperator/patternname/) { get; } | Hämtar mönsternamn. |
| [R](../../aspose.pdf.operators/basicsetcoloroperator/r/) { get; } | Hämtar röd komponent av färg |
| [Y](../../aspose.pdf.operators/basicsetcoloroperator/y/) { get; } | Hämtar gul komponent av CMYK-färg. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setadvancedcolorstroke/accept/)(IOperatorSelector) | Accepterar besöksobjekt för att bearbeta operator. |
| override [getColor](../../aspose.pdf.operators/setadvancedcolorstroke/getcolor/)() | Returnerar färg som specificeras av operator. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Returnerar text av operator och dess parametrar. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Jämför denna instans med det givna objektet. |

### Se Även

* klass [BasicSetColorAndPatternOperator](../basicsetcolorandpatternoperator/)
* namnrymd [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)