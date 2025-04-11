---
title: Class ThreadMessageListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.ThreadMessageListQueryParameters-Klasse. Abfrageparameterobjekt zum Auflisten von Thread-Nachrichten
type: docs
weight: 1130
url: /de/net/aspose.pdf.ai/threadmessagelistqueryparameters/
---
## Klasse ThreadMessageListQueryParameters

Abfrageparameterobjekt zum Auflisten von Thread-Nachrichten.

```csharp
public class ThreadMessageListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ThreadMessageListQueryParameters](threadmessagelistqueryparameters/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Ruft einen Cursor ab oder legt diesen fest, der für die Paginierung verwendet wird. after ist eine Objekt-ID, die Ihren Platz in der Liste definiert. Wenn Sie beispielsweise eine Listenanfrage stellen und 100 Objekte erhalten, die mit obj_foo enden, kann Ihr nachfolgender Aufruf after=obj_foo enthalten, um die nächste Seite der Liste abzurufen. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Ruft einen Cursor ab oder legt diesen fest, der für die Paginierung verwendet wird. before ist eine Objekt-ID, die Ihren Platz in der Liste definiert. Wenn Sie beispielsweise eine Listenanfrage stellen und 100 Objekte erhalten, die mit obj_foo enden, kann Ihr nachfolgender Aufruf before=obj_foo enthalten, um die vorherige Seite der Liste abzurufen. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Ruft ein Limit für die Anzahl der zurückzugebenden Objekte ab oder legt dieses fest. Limit kann zwischen 1 und 100 liegen, und der Standardwert beträgt 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Ruft die Sortierreihenfolge nach dem created_at-Zeitstempel der Objekte ab oder legt diese fest. asc für aufsteigende Reihenfolge und desc für absteigende Reihenfolge. |
| [RunId](../../aspose.pdf.ai/threadmessagelistqueryparameters/runid/) { get; set; } | Filtert Nachrichten nach der Run-ID, die sie erzeugt hat. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/threadmessagelistqueryparameters/getqueryparameters/)() | Ruft die Abfrageparameter zum Auflisten von Thread-Nachrichten ab. |

### Siehe auch

* Klasse [BaseListQueryParameters](../baselistqueryparameters/)
* Schnittstelle [IQueryParameters](../iqueryparameters/)
* Namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../)