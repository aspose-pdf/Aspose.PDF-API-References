---
title: Class RunStepListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.RunStepListQueryParameters-Klasse. Abfrageparameterobjekt zum Auflisten von Ausführungsschritten
type: docs
weight: 1040
url: /de/net/aspose.pdf.ai/runsteplistqueryparameters/
---
## Klasse RunStepListQueryParameters

Abfrageparameterobjekt zum Auflisten von Ausführungsschritten.

```csharp
public class RunStepListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [RunStepListQueryParameters](runsteplistqueryparameters/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Ruft einen Cursor für die Verwendung bei der Paginierung ab oder legt ihn fest. after ist eine Objekt-ID, die Ihren Platz in der Liste definiert. Wenn Sie beispielsweise eine Listenanfrage stellen und 100 Objekte erhalten, die mit obj_foo enden, kann Ihr nachfolgender Aufruf after=obj_foo enthalten, um die nächste Seite der Liste abzurufen. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Ruft einen Cursor für die Verwendung bei der Paginierung ab oder legt ihn fest. before ist eine Objekt-ID, die Ihren Platz in der Liste definiert. Wenn Sie beispielsweise eine Listenanfrage stellen und 100 Objekte erhalten, die mit obj_foo enden, kann Ihr nachfolgender Aufruf before=obj_foo enthalten, um die vorherige Seite der Liste abzurufen. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Ruft ein Limit für die Anzahl der zurückzugebenden Objekte ab oder legt es fest. Limit kann zwischen 1 und 100 liegen, und der Standardwert beträgt 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Ruft die Sortierreihenfolge nach dem created_at-Zeitstempel der Objekte ab oder legt sie fest. asc für aufsteigende Reihenfolge und desc für absteigende Reihenfolge. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/runsteplistqueryparameters/getqueryparameters/)() | Ruft die Abfrageparameter zum Auflisten von Ausführungsschritten ab. |

### Siehe auch

* Klasse [BaseListQueryParameters](../baselistqueryparameters/)
* Schnittstelle [IQueryParameters](../iqueryparameters/)
* Namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../)