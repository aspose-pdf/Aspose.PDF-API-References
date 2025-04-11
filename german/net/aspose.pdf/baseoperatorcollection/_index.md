---
title: Class BaseOperatorCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.BaseOperatorCollection-Klasse. Stellt die Basisklasse für die Operatorensammlung dar
type: docs
weight: 2830
url: /de/net/aspose.pdf/baseoperatorcollection/
---
## Klasse BaseOperatorCollection

Stellt die Basisklasse für die Operatorensammlung dar.

```csharp
public abstract class BaseOperatorCollection : ICollection<Operator>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| abstract [Count](../../aspose.pdf/baseoperatorcollection/count/) { get; } | Gibt die Anzahl der Operatoren in der Sammlung zurück. |
| abstract [IsFastTextExtractionMode](../../aspose.pdf/baseoperatorcollection/isfasttextextractionmode/) { get; } | Gibt an, ob die Sammlung auf die schnelle Textextraktion beschränkt ist. |
| abstract [IsReadOnly](../../aspose.pdf/baseoperatorcollection/isreadonly/) { get; } | Gibt true zurück, wenn die Sammlung schreibgeschützt ist. |
| abstract [Item](../../aspose.pdf/baseoperatorcollection/item/) { get; set; } | Gibt den Operator anhand seines Index zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| abstract [Add](../../aspose.pdf/baseoperatorcollection/add/)(Operator) | Fügt einen neuen Operator zur Sammlung hinzu. |
| abstract [CancelUpdate](../../aspose.pdf/baseoperatorcollection/cancelupdate/)() | Storniert das letzte Update. Diese Methode kann aufgerufen werden, wenn die Änderung kein Inhaltsupdate auslösen soll. |
| abstract [Clear](../../aspose.pdf/baseoperatorcollection/clear/)() | Löscht die Sammlung. |
| abstract [Contains](../../aspose.pdf/baseoperatorcollection/contains/)(Operator) | Überprüft, ob der Operator in der Sammlung vorhanden ist. |
| abstract [CopyTo](../../aspose.pdf/baseoperatorcollection/copyto/)(Operator[], int) | Kopiert Operatoren in die Operatorenliste. |
| abstract [GetEnumerator](../../aspose.pdf/baseoperatorcollection/getenumerator/)() | Gibt einen Enumerator für die Sammlung zurück. |
| abstract [Insert](../../aspose.pdf/baseoperatorcollection/insert/)(int, Operator) | Fügt einen Operator in die Sammlung ein. |
| abstract [Remove](../../aspose.pdf/baseoperatorcollection/remove/)(Operator) | Entfernt einen Operator aus der Sammlung. |
| abstract [ResumeUpdate](../../aspose.pdf/baseoperatorcollection/resumeupdate/)() | Setzt das Dokumentenupdate fort. Aktualisiert den Inhaltsstream, falls Änderungen ausstehen. |
| abstract [SuppressUpdate](../../aspose.pdf/baseoperatorcollection/suppressupdate/)() | Unterdrückt die Aktualisierung der Inhaltsdaten. Der Inhaltsstream wird nicht aktualisiert, bis ResumeUpdate aufgerufen wird. |

### Siehe auch

* Klasse [Operator](../operator/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)