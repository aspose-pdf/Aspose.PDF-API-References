---
title: Class TextShowOperator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.TextShowOperator-Klasse. Abstrakte Basisklasse für alle Operatoren, die zum Ausgeben von Text verwendet werden.
type: docs
weight: 7920
url: /de/net/aspose.pdf.operators/textshowoperator/
---
## TextShowOperator-Klasse

Abstrakte Basisklasse für alle Operatoren, die zum Ausgeben von Text verwendet werden (Tj, TJ usw.).

```csharp
public class TextShowOperator : TextOperator
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TextShowOperator](textshowoperator/#constructor)() | Initialisiert TextShowOperator. |
| [TextShowOperator](textshowoperator/#constructor_1)(TextProperties) | Initialisiert TextShowOperator, der es ermöglicht, TextProperties zu übergeben. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operatorindex in der Liste der Seitenoperatoren. |
| virtual [Text](../../aspose.pdf.operators/textshowoperator/text/) { get; set; } | Gibt den Text zurück, den der Operator auf der Seite ausgibt. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/textoperator/accept/)(IOperatorSelector) | Akzeptiert das Besucherobjekt zur Verarbeitung des Operators. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Gibt den Text des Operators und dessen Parameter zurück. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Vergleicht diese Instanz mit dem angegebenen Objekt. |

### Siehe auch

* Klasse [TextOperator](../textoperator/)
* Namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* Assembly [Aspose.PDF](../../)