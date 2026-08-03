---
title: "Klass SetColorStroke"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Operators.SetColorStroke klass. Klass som representerar SC-operator som sätter färg för streckningsfärgsoperatorer"
type: docs
weight: 7820
url: /sv/net/aspose.pdf.operators/setcolorstroke/
---
## SetColorStroke class

Klass som representerar SC-operatorn (ställer in färg för strokande färgoperatorer).

```csharp
public class SetColorStroke : BasicSetColorOperator
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SetColorStroke](setcolorstroke/#constructor)() | Initierar operatorn. |
| [SetColorStroke](setcolorstroke/#constructor_1)(double) | Ställ in färg för streckningsoperatorer för DeviceGray-, CalGray- och Indexed-färgrymder. |
| [SetColorStroke](setcolorstroke/#constructor_4)(double[]) | Konstruktor som tillåter att sätta färgkomponenter. |
| [SetColorStroke](setcolorstroke/#constructor_2)(double, double, double) | Ställ in färg för streckningsoperator för DeviceRGB-, CalRGB- och Lab-färgrymder |
| [SetColorStroke](setcolorstroke/#constructor_3)(double, double, double, double) | Ställ in färg för streckningsoperator för CMYK-färgrymd |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolorstroke/b/) { get; set; } | Hämtar eller anger den blå komponenten. |
| [C](../../aspose.pdf.operators/setcolorstroke/c/) { get; set; } | Hämtar eller anger cyan-komponenten. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Hämtar en array av färgkomponenter. |
| [G](../../aspose.pdf.operators/setcolorstroke/g/) { get; set; } | Hämtar eller anger den gröna komponenten. |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Hämtar den svarta komponenten i grå färg. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operatorindex i Page-operatorlistan. |
| [K](../../aspose.pdf.operators/setcolorstroke/k/) { get; set; } | Hämtar eller anger den svarta komponenten. |
| [M](../../aspose.pdf.operators/setcolorstroke/m/) { get; set; } | Hämtar eller anger magentakomponenten. |
| [R](../../aspose.pdf.operators/setcolorstroke/r/) { get; set; } | Hämtar eller anger den röda komponenten. |
| [Y](../../aspose.pdf.operators/setcolorstroke/y/) { get; set; } | Hämtar eller anger den gula komponenten. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolorstroke/accept/)(IOperatorSelector) | Accepterar besökarobjekt för att bearbeta operatorn. |
| override [getColor](../../aspose.pdf.operators/setcolorstroke/getcolor/)() | Returnerar färgen som specificerats av operatorn. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Returnerar operatorns text och dess parametrar. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Jämför denna instans med det angivna objektet. |

### Se även

* class [BasicSetColorOperator](../basicsetcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


