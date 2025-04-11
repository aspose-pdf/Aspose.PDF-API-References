---
title: Class SetColorStroke
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.SetColorStroke-Klasse. Klasse, die den SC-Operator zum Setzen der Farbe für Strichfarbenoperatoren darstellt
type: docs
weight: 7680
url: /de/net/aspose.pdf.operators/setcolorstroke/
---
## SetColorStroke-Klasse

Klasse, die den SC-Operator zum Setzen der Farbe für Strichfarbenoperatoren darstellt.

```csharp
public class SetColorStroke : BasicSetColorOperator
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SetColorStroke](setcolorstroke/#constructor)() | Initialisiert den Operator. |
| [SetColorStroke](setcolorstroke/#constructor_1)(double) | Setzt die Farbe für Strichoperatoren für DeviceGray, CalGray und indizierte Farbräume. |
| [SetColorStroke](setcolorstroke/#constructor_4)(double[]) | Konstruktor, der das Setzen von Farbkomponenten ermöglicht. |
| [SetColorStroke](setcolorstroke/#constructor_2)(double, double, double) | Setzt die Farbe für den Strichoperator für DeviceRGB, CalRGB und Lab-Farbräume |
| [SetColorStroke](setcolorstroke/#constructor_3)(double, double, double, double) | Setzt die Farbe für den Strichoperator für den CMYK-Farbraum |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolorstroke/b/) { get; set; } | Ruft die blaue Komponente ab oder setzt sie. |
| [C](../../aspose.pdf.operators/setcolorstroke/c/) { get; set; } | Ruft die cyanfarbene Komponente ab oder setzt sie. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Ruft das Array der Farbkomponenten ab. |
| [G](../../aspose.pdf.operators/setcolorstroke/g/) { get; set; } | Ruft die grüne Komponente ab oder setzt sie. |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Ruft die schwarze Komponente der Graufarbe ab. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operatorindex in der Liste der Seitenoperatoren. |
| [K](../../aspose.pdf.operators/setcolorstroke/k/) { get; set; } | Ruft die schwarze Komponente ab oder setzt sie. |
| [M](../../aspose.pdf.operators/setcolorstroke/m/) { get; set; } | Ruft die magentafarbene Komponente ab oder setzt sie. |
| [R](../../aspose.pdf.operators/setcolorstroke/r/) { get; set; } | Ruft die rote Komponente ab oder setzt sie. |
| [Y](../../aspose.pdf.operators/setcolorstroke/y/) { get; set; } | Ruft die gelbe Komponente ab oder setzt sie. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolorstroke/accept/)(IOperatorSelector) | Akzeptiert das Besucherobjekt zur Verarbeitung des Operators. |
| override [getColor](../../aspose.pdf.operators/setcolorstroke/getcolor/)() | Gibt die vom Operator angegebene Farbe zurück. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Gibt den Text des Operators und seiner Parameter zurück. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Vergleicht diese Instanz mit dem angegebenen Objekt. |

### Siehe auch

* Klasse [BasicSetColorOperator](../basicsetcoloroperator/)
* Namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* Assembly [Aspose.PDF](../../)