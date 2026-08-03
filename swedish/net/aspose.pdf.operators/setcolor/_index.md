---
title: "Klass SetColor"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Operators.SetColor class. Representerar klass för sc-operatorn som sätter färg för icke‑strykoperationer"
type: docs
weight: 7770
url: /sv/net/aspose.pdf.operators/setcolor/
---
## SetColor class

Representerar klass för sc-operatorn (ställer in färg för icke‑strokande operationer).

```csharp
public class SetColor : BasicSetColorOperator
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SetColor](setcolor/#constructor)() | Initierar operatorn. |
| [SetColor](setcolor/#constructor_1)(double) | Ställ in färg för streckningsoperatorer för DeviceGray-, CalGray- och Indexed-färgrymder. |
| [SetColor](setcolor/#constructor_4)(double[]) | Konstruktor som tillåter att specificera färgkomponenter. |
| [SetColor](setcolor/#constructor_2)(double, double, double) | Ställ in färg för streckningsoperator för DeviceRGB-, CalRGB- och Lab-färgrymder |
| [SetColor](setcolor/#constructor_3)(double, double, double, double) | Sätt färg för icke‑strykoperator i CMYK-färgrymden |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolor/b/) { get; set; } | Hämtar eller anger den blå komponenten. |
| [C](../../aspose.pdf.operators/setcolor/c/) { get; set; } | Hämtar eller anger cyan-komponenten. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Hämtar en array av färgkomponenter. |
| [G](../../aspose.pdf.operators/setcolor/g/) { get; set; } | Hämtar eller anger den gröna komponenten. |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Hämtar den svarta komponenten i grå färg. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operatorindex i Page-operatorlistan. |
| [K](../../aspose.pdf.operators/setcolor/k/) { get; set; } | Hämtar eller anger den svarta komponenten. |
| [M](../../aspose.pdf.operators/setcolor/m/) { get; set; } | Hämtar eller anger magentakomponenten. |
| [R](../../aspose.pdf.operators/setcolor/r/) { get; set; } | Hämtar eller anger den röda komponenten. |
| [Y](../../aspose.pdf.operators/setcolor/y/) { get; set; } | Hämtar eller anger den gula komponenten. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolor/accept/)(IOperatorSelector) | Accepterar besökarobjekt för att bearbeta operatorn. |
| override [getColor](../../aspose.pdf.operators/setcolor/getcolor/)() | Returnerar färg som specificerats av operatorn. |
| override [ToString](../../aspose.pdf.operators/setcolor/tostring/)() | Returnerar strängrepresentation av färg. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Jämför denna instans med det angivna objektet. |

### Se även

* class [BasicSetColorOperator](../basicsetcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


