---
title: "Klass SetDash"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Operators.SetDash class. Klass som representerar d-operatorn för att sätta linjestreckmönster"
type: docs
weight: 7830
url: /sv/net/aspose.pdf.operators/setdash/
---
## SetDash class

Klass som representerar d-operatorn (ställer in streckmönster för linje).

```csharp
public class SetDash : Operator
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SetDash](setdash/)(int[], int) | Skapar operator för att sätta streckmönster. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operatorindex i Page-operatorlistan. |
| [Pattern](../../aspose.pdf.operators/setdash/pattern/) { get; set; } | Streckmönster. Arrayens element ska vara tal som specificerar längderna på alternerande streck och mellanrum. Om arrayen har ett element är streck- och mellanrumslängderna lika. |
| [Phase](../../aspose.pdf.operators/setdash/phase/) { get; set; } | Streckfas. Innan en bana sträcks, ska streckarrayen cyklas igenom och summan av streck- och mellanrumslängderna beräknas. När den ackumulerade längden motsvarar värdet som anges av streckfasen, ska sträckning av banan påbörjas, och streckarrayen ska användas cykliskt från den punkten och framåt. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setdash/accept/)(IOperatorSelector) | Accepterar besökarobjekt för att bearbeta operatorn. |
| override [ToString](../../aspose.pdf.operators/setdash/tostring/)() | Hämtar operatorns strängrepresentation. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Jämför denna instans med det angivna objektet. |

### Se även

* class [Operator](../../aspose.pdf/operator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


