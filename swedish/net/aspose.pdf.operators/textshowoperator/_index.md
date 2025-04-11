---
title: Class TextShowOperator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.TextShowOperator klass. Abstrakt basklass för alla operatörer som används för att visa text Tj TJ etc
type: docs
weight: 7920
url: /sv/net/aspose.pdf.operators/textshowoperator/
---
## TextShowOperator klass

Abstrakt basklass för alla operatörer som används för att visa text (Tj, TJ, etc).

```csharp
public class TextShowOperator : TextOperator
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TextShowOperator](textshowoperator/#constructor)() | Initierar TextShowOperator. |
| [TextShowOperator](textshowoperator/#constructor_1)(TextProperties) | Initierar TextShowOperator som tillåter att skicka TextProperties. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operatörens index i sidans operatörslista. |
| virtual [Text](../../aspose.pdf.operators/textshowoperator/text/) { get; set; } | Hämtar text som operatören visar på sidan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/textoperator/accept/)(IOperatorSelector) | Accepterar besöksobjekt för att bearbeta operatören. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Returnerar texten av operatören och dess parametrar. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Jämför denna instans med det givna objektet. |

### Se Även

* klass [TextOperator](../textoperator/)
* namnrymd [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)