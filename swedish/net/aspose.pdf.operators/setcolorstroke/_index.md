---
title: Class SetColorStroke
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.SetColorStroke klass. Klass som representerar SC-operatorn för att ställa in färg för strekningsfärgsoperatorer
type: docs
weight: 7680
url: /sv/net/aspose.pdf.operators/setcolorstroke/
---
## SetColorStroke klass

Klass som representerar SC-operatorn för att ställa in färg för strekningsfärgsoperatorer.

```csharp
public class SetColorStroke : BasicSetColorOperator
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SetColorStroke](setcolorstroke/#constructor)() | Initierar operator. |
| [SetColorStroke](setcolorstroke/#constructor_1)(double) | Ställer in färg för strekningsoperatorer för DeviceGray, CalGray och Indexed färgrum. |
| [SetColorStroke](setcolorstroke/#constructor_4)(double[]) | Konstruktör som tillåter att ställa in färgkomponenter. |
| [SetColorStroke](setcolorstroke/#constructor_2)(double, double, double) | Ställer in färg för strekningsoperator för DeviceRGB, CalRGB och Lab färgrum |
| [SetColorStroke](setcolorstroke/#constructor_3)(double, double, double, double) | Ställer in färg för strekningsoperator för CMYK färgrum |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolorstroke/b/) { get; set; } | Hämtar eller ställer in den blå komponenten. |
| [C](../../aspose.pdf.operators/setcolorstroke/c/) { get; set; } | Hämtar eller ställer in den cyan komponenten. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Hämtar array av färgkomponenter. |
| [G](../../aspose.pdf.operators/setcolorstroke/g/) { get; set; } | Hämtar eller ställer in den gröna komponenten. |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Hämtar den svarta komponenten av grå färg. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operatorindex i listan över sidoperatorer. |
| [K](../../aspose.pdf.operators/setcolorstroke/k/) { get; set; } | Hämtar eller ställer in den svarta komponenten. |
| [M](../../aspose.pdf.operators/setcolorstroke/m/) { get; set; } | Hämtar eller ställer in den magenta komponenten. |
| [R](../../aspose.pdf.operators/setcolorstroke/r/) { get; set; } | Hämtar eller ställer in den röda komponenten. |
| [Y](../../aspose.pdf.operators/setcolorstroke/y/) { get; set; } | Hämtar eller ställer in den gula komponenten. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolorstroke/accept/)(IOperatorSelector) | Accepterar besökarobjekt för att bearbeta operator. |
| override [getColor](../../aspose.pdf.operators/setcolorstroke/getcolor/)() | Returnerar färg som specificeras av operator. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Returnerar text av operator och dess parametrar. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Jämför denna instans med det givna objektet. |

### Se Även

* klass [BasicSetColorOperator](../basicsetcoloroperator/)
* namnrymd [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* sammansättning [Aspose.PDF](../../)