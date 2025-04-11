---
title: Class VectorStoreFileBatchFileListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.VectorStoreFileBatchFileListQueryParameters-Klasse. Abfrageparameterobjekt zum Auflisten von Vektorspeicher-Dateibatchdateien
type: docs
weight: 1290
url: /de/net/aspose.pdf.ai/vectorstorefilebatchfilelistqueryparameters/
---
## Klasse VectorStoreFileBatchFileListQueryParameters

Abfrageparameterobjekt zum Auflisten von Vektorspeicher-Dateibatchdateien.

```csharp
public class VectorStoreFileBatchFileListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [VectorStoreFileBatchFileListQueryParameters](vectorstorefilebatchfilelistqueryparameters/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Ruft einen Cursor ab oder legt diesen fest, der für die Paginierung verwendet wird. after ist eine Objekt-ID, die Ihren Platz in der Liste definiert. Wenn Sie beispielsweise eine Listenanfrage stellen und 100 Objekte erhalten, die mit obj_foo enden, kann Ihr nachfolgender Aufruf after=obj_foo enthalten, um die nächste Seite der Liste abzurufen. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Ruft einen Cursor ab oder legt diesen fest, der für die Paginierung verwendet wird. before ist eine Objekt-ID, die Ihren Platz in der Liste definiert. Wenn Sie beispielsweise eine Listenanfrage stellen und 100 Objekte erhalten, die mit obj_foo enden, kann Ihr nachfolgender Aufruf before=obj_foo enthalten, um die vorherige Seite der Liste abzurufen. |
| [Filter](../../aspose.pdf.ai/vectorstorefilebatchfilelistqueryparameters/filter/) { get; set; } | Ruft einen Filter nach Dateistatus ab oder legt diesen fest. Einer von in_progress, completed, failed, cancelled. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Ruft ein Limit für die Anzahl der zurückzugebenden Objekte ab oder legt dieses fest. Limit kann zwischen 1 und 100 liegen, und der Standardwert beträgt 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Ruft die Sortierreihenfolge nach dem created_at-Zeitstempel der Objekte ab oder legt diese fest. asc für aufsteigende Reihenfolge und desc für absteigende Reihenfolge. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/vectorstorefilebatchfilelistqueryparameters/getqueryparameters/)() | Ruft die Abfrageparameter zum Auflisten von Speicherdatenbatchdateien ab. |

### Siehe auch

* Klasse [BaseListQueryParameters](../baselistqueryparameters/)
* Schnittstelle [IQueryParameters](../iqueryparameters/)
* Namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../)