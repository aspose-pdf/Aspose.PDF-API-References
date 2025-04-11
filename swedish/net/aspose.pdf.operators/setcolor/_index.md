---
title: Class SetColor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.SetColor klass. Representerar klass för sc-operatorn som sätter färg för icke-stroke operationer
type: docs
weight: 7630
url: /sv/net/aspose.pdf.operators/setcolor/
---
## SetColor klass

Representerar klass för sc-operatorn (sätter färg för icke-stroke operationer).

```csharp
public class SetColor : BasicSetColorOperator
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SetColor](setcolor/#constructor)() | Initierar operator. |
| [SetColor](setcolor/#constructor_1)(double) | Sätter färg för stroke-operatorer för DeviceGray, CalGray och Indexed färgrum. |
| [SetColor](setcolor/#constructor_4)(double[]) | Konstruktör som tillåter att specificera färgkomponenter. |
| [SetColor](setcolor/#constructor_2)(double, double, double) | Sätter färg för stroke-operator för DeviceRGB, CalRGB och Lab färgrum |
| [SetColor](setcolor/#constructor_3)(double, double, double, double) | Sätter färg för icke-stroke operator för CMYK färgrum |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolor/b/) { get; set; } | Hämtar eller sätter den blå komponenten. |
| [C](../../aspose.pdf.operators/setcolor/c/) { get; set; } | Hämtar eller sätter den cyan komponenten. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Hämtar array av färgkomponenter. |
| [G](../../aspose.pdf.operators/setcolor/g/) { get; set; } | Hämtar eller sätter den gröna komponenten. |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Hämtar den svarta komponenten av grå färg. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operatorindex i sidans operatorlista. |
| [K](../../aspose.pdf.operators/setcolor/k/) { get; set; } | Hämtar eller sätter den svarta komponenten. |
| [M](../../aspose.pdf.operators/setcolor/m/) { get; set; } | Hämtar eller sätter den magenta komponenten. |
| [R](../../aspose.pdf.operators/setcolor/r/) { get; set; } | Hämtar eller sätter den röda komponenten. |
| [Y](../../aspose.pdf.operators/setcolor/y/) { get; set; } | Hämtar eller sätter den gula komponenten. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolor/accept/)(IOperatorSelector) | Accepterar besökarobjekt för att bearbeta operator. |
| override [getColor](../../aspose.pdf.operators/setcolor/getcolor/)() | Returnerar färg som specificeras av operatorn. |
| override [ToString](../../aspose.pdf.operators/setcolor/tostring/)() | Returnerar strängrepresentation av färg. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Jämför denna instans med det givna objektet. |

### Se Även

* klass [BasicSetColorOperator](../basicsetcoloroperator/)
* namnrymd [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)