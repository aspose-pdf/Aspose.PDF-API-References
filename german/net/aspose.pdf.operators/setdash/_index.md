---
title: Class SetDash
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.SetDash-Klasse. Klasse, die den d-Operator zum Setzen des Linienstil-Musters darstellt
type: docs
weight: 7690
url: /de/net/aspose.pdf.operators/setdash/
---
## SetDash-Klasse

Klasse, die den d-Operator (Linienstil-Muster setzen) darstellt.

```csharp
public class SetDash : Operator
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SetDash](setdash/)(int[], int) | Erstellt den Operator zum Setzen des Linienstil-Musters. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operatorindex in der Liste der Seitenoperatoren. |
| [Pattern](../../aspose.pdf.operators/setdash/pattern/) { get; set; } | Linienstil-Muster. Die Elemente des Arrays müssen Zahlen sein, die die Längen der abwechselnden Striche und Lücken angeben. Im Falle eines ein-elementigen Arrays sind die Längen von Strich und Lücke gleich. |
| [Phase](../../aspose.pdf.operators/setdash/phase/) { get; set; } | Linienstil-Phase. Bevor ein Pfad gestrichen wird, muss das Linienstilmuster durchlaufen werden, wobei die Längen der Striche und Lücken addiert werden. Wenn die akkumulierte Länge dem Wert entspricht, der durch die Linienstil-Phase angegeben ist, beginnt das Streichen des Pfades, und das Linienstilmuster wird ab diesem Punkt zyklisch verwendet. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setdash/accept/)(IOperatorSelector) | Akzeptiert das Besucherobjekt zur Verarbeitung des Operators. |
| override [ToString](../../aspose.pdf.operators/setdash/tostring/)() | Gibt die String-Darstellung des Operators zurück. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Vergleicht diese Instanz mit dem angegebenen Objekt. |

### Siehe auch

* Klasse [Operator](../../aspose.pdf/operator/)
* Namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* Assembly [Aspose.PDF](../../)