---
title: Class SetDash
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.SetDash klass. Klass som representerar d operator set line dash-mönster
type: docs
weight: 7690
url: /sv/net/aspose.pdf.operators/setdash/
---
## SetDash klass

Klass som representerar d operator (set line dash-mönster).

```csharp
public class SetDash : Operator
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SetDash](setdash/)(int[], int) | Skapar set dash-mönsteroperator. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Operatörens index i sidans operatörslista. |
| [Pattern](../../aspose.pdf.operators/setdash/pattern/) { get; set; } | Dash-mönster. Arrayens element ska vara siffror som specificerar längderna på växlande streck och luckor. I fallet med en element-array är längderna på streck och luckor lika. |
| [Phase](../../aspose.pdf.operators/setdash/phase/) { get; set; } | Dash-fas. Innan man börjar stryka en väg ska dash-arrayen cyklas igenom, och längderna på strecken och luckorna ska adderas. När den ackumulerade längden är lika med det värde som specificeras av dash-fasen, ska strykningen av vägen börja, och dash-arrayen ska användas cykliskt från den punkten och framåt. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setdash/accept/)(IOperatorSelector) | Accepterar besöksobjekt för att bearbeta operatören. |
| override [ToString](../../aspose.pdf.operators/setdash/tostring/)() | Hämtar operatörens strängrepresentation. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Jämför denna instans med det givna objektet. |

### Se Även

* klass [Operator](../../aspose.pdf/operator/)
* namnrymd [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)