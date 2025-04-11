---
title: Class SetAdvancedColor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.SetAdvancedColor klass. Klass som representerar scn-operatorn för att ställa in färg för icke-stroke operationer
type: docs
weight: 7560
url: /sv/net/aspose.pdf.operators/setadvancedcolor/
---
## SetAdvancedColor klass

Klass som representerar scn-operatorn (ställer in färg för icke-stroke operationer).

```csharp
public class SetAdvancedColor : BasicSetColorAndPatternOperator
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SetAdvancedColor](setadvancedcolor/#constructor)() | Initierar operator. |
| [SetAdvancedColor](setadvancedcolor/#constructor_1)(double) | Konstruktör för scn-operator. |
| [SetAdvancedColor](setadvancedcolor/#constructor_6)(string) | Konstruktör för scn-operator. |
| [SetAdvancedColor](setadvancedcolor/#constructor_4)(double, string) | Konstruktör för scn-operator. |
| [SetAdvancedColor](setadvancedcolor/#constructor_5)(double[], string) | Konstruktör för scn-operator. |
| [SetAdvancedColor](setadvancedcolor/#constructor_3)(double, double, double, string) | Konstruktör för scn-operator. |
| [SetAdvancedColor](setadvancedcolor/#constructor_2)(double, double, double, double, string) | Konstruktör för scn-operator. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [B](../../aspose.pdf.operators/basicsetcoloroperator/b/) { get; } | Hämtar röd komponent av färg |
| [C](../../aspose.pdf.operators/basicsetcoloroperator/c/) { get; } | Hämtar cyan komponent av CMYK-färg. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Hämtar array av färgkomponenter. |
| [G](../../aspose.pdf.operators/basicsetcoloroperator/g/) { get; } | Hämtar grön komponent av färg |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Hämtar svart komponent av grå färg. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operatorindex i sidans operatorlista. |
| [K](../../aspose.pdf.operators/basicsetcoloroperator/k/) { get; } | Hämtar svart komponent av CMYK-färg. |
| [M](../../aspose.pdf.operators/basicsetcoloroperator/m/) { get; } | Hämtar magenta komponent av CMYK-färg. |
| [PatternName](../../aspose.pdf.operators/basicsetcolorandpatternoperator/patternname/) { get; } | Hämtar mönster namn. |
| [R](../../aspose.pdf.operators/basicsetcoloroperator/r/) { get; } | Hämtar röd komponent av färg |
| [Y](../../aspose.pdf.operators/basicsetcoloroperator/y/) { get; } | Hämtar gul komponent av CMYK-färg. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setadvancedcolor/accept/)(IOperatorSelector) | Accepterar besökarobjekt för att bearbeta operator. |
| override [getColor](../../aspose.pdf.operators/setadvancedcolor/getcolor/)() | Returnerar färg som specificeras av operator. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Returnerar text av operator och dess parametrar. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Jämför denna instans med det givna objektet. |

### Se Även

* klass [BasicSetColorAndPatternOperator](../basicsetcolorandpatternoperator/)
* namnrum [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* samling [Aspose.PDF](../../)