---
title: Class SetColor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.SetColor-Klasse. Stellt die Klasse für den sc-Operator dar, um die Farbe für nicht-streichende Operationen festzulegen
type: docs
weight: 7630
url: /de/net/aspose.pdf.operators/setcolor/
---
## SetColor-Klasse

Stellt die Klasse für den sc-Operator (Farbe für nicht-streichende Operationen festlegen) dar.

```csharp
public class SetColor : BasicSetColorOperator
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SetColor](setcolor/#constructor)() | Initialisiert den Operator. |
| [SetColor](setcolor/#constructor_1)(double) | Legt die Farbe für streichende Operatoren für DeviceGray, CalGray und indizierte Farbräume fest. |
| [SetColor](setcolor/#constructor_4)(double[]) | Konstruktor, der es ermöglicht, Farbkomponenten anzugeben. |
| [SetColor](setcolor/#constructor_2)(double, double, double) | Legt die Farbe für den streichenden Operator für DeviceRGB, CalRGB und Lab-Farbräume fest. |
| [SetColor](setcolor/#constructor_3)(double, double, double, double) | Legt die Farbe für den nicht-streichenden Operator für den CMYK-Farbraum fest. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolor/b/) { get; set; } | Ruft die blaue Komponente ab oder legt sie fest. |
| [C](../../aspose.pdf.operators/setcolor/c/) { get; set; } | Ruft die cyanfarbene Komponente ab oder legt sie fest. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Ruft das Array der Farbkomponenten ab. |
| [G](../../aspose.pdf.operators/setcolor/g/) { get; set; } | Ruft die grüne Komponente ab oder legt sie fest. |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Ruft die schwarze Komponente der grauen Farbe ab. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operatorindex in der Liste der Seitenoperatoren. |
| [K](../../aspose.pdf.operators/setcolor/k/) { get; set; } | Ruft die schwarze Komponente ab oder legt sie fest. |
| [M](../../aspose.pdf.operators/setcolor/m/) { get; set; } | Ruft die magentafarbene Komponente ab oder legt sie fest. |
| [R](../../aspose.pdf.operators/setcolor/r/) { get; set; } | Ruft die rote Komponente ab oder legt sie fest. |
| [Y](../../aspose.pdf.operators/setcolor/y/) { get; set; } | Ruft die gelbe Komponente ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolor/accept/)(IOperatorSelector) | Akzeptiert das Besucherobjekt zur Verarbeitung des Operators. |
| override [getColor](../../aspose.pdf.operators/setcolor/getcolor/)() | Gibt die vom Operator angegebene Farbe zurück. |
| override [ToString](../../aspose.pdf.operators/setcolor/tostring/)() | Gibt die stringbasierte Darstellung der Farbe zurück. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Vergleicht diese Instanz mit dem angegebenen Objekt. |

### Siehe auch

* Klasse [BasicSetColorOperator](../basicsetcoloroperator/)
* Namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* Assembly [Aspose.PDF](../../)