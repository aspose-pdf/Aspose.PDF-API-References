---
title: Class OperatorCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.OperatorCollection-Klasse. Klasse repräsentiert eine Sammlung von Operatoren
type: docs
weight: 7080
url: /de/net/aspose.pdf/operatorcollection/
---
## OperatorCollection-Klasse

Klasse repräsentiert eine Sammlung von Operatoren

```csharp
public class OperatorCollection : BaseOperatorCollection, IDisposable
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [Count](../../aspose.pdf/operatorcollection/count/) { get; } | Gibt die Anzahl der Operatoren in der Sammlung zurück. |
| override [IsFastTextExtractionMode](../../aspose.pdf/operatorcollection/isfasttextextractionmode/) { get; } | Gibt an, ob die Sammlung auf die schnelle Textextraktion beschränkt ist. |
| override [IsReadOnly](../../aspose.pdf/operatorcollection/isreadonly/) { get; } | Gibt einen Wert zurück, der angibt, ob die Sammlung schreibgeschützt ist. |
| override [Item](../../aspose.pdf/operatorcollection/item/) { get; set; } | Gibt den Operator anhand seines Index zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Accept](../../aspose.pdf/operatorcollection/accept/)(IOperatorSelector) | Akzeptiert das IOperatorSelector-Besucherobjekt zur Verarbeitung von Operatoren. |
| [Add](../../aspose.pdf/operatorcollection/add/#add_2)(ICollection&lt;Operator&gt;) | Fügt der Sammlung alle Operatoren aus einer anderen Sammlung hinzu. |
| override [Add](../../aspose.pdf/operatorcollection/add/#add)(Operator) | Fügt einen neuen Operator zur Sammlung hinzu. |
| [Add](../../aspose.pdf/operatorcollection/add/#add_1)(Operator[]) | Fügt Operatoren am Ende der Inhaltsoperatoren hinzu. |
| override [CancelUpdate](../../aspose.pdf/operatorcollection/cancelupdate/)() | Storniert das letzte Update. Diese Methode kann aufgerufen werden, wenn die Änderung kein Inhaltsupdate auslösen soll. |
| override [Clear](../../aspose.pdf/operatorcollection/clear/)() | Entfernt alle Operatoren aus der Liste. |
| override [Contains](../../aspose.pdf/operatorcollection/contains/)(Operator) | Gibt true zurück, wenn die Sammlung den angegebenen Operator enthält. |
| override [CopyTo](../../aspose.pdf/operatorcollection/copyto/)(Operator[], int) | Kopiert Operatoren in die Operatorenliste. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_2)(IList&lt;Operator&gt;) | Löscht Operatoren aus der Sammlung. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_1)(int) | Löscht einen Operator aus der Sammlung. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete)(Operator[]) | Löscht Operatoren aus der Sammlung. |
| [Dispose](../../aspose.pdf/operatorcollection/dispose/)() | Führt anwendungsdefinierte Aufgaben aus, die mit dem Freigeben, Zurücksetzen oder Freigeben von nicht verwalteten Ressourcen verbunden sind. |
| override [GetEnumerator](../../aspose.pdf/operatorcollection/getenumerator/)() | Gibt einen Enumerator für die Sammlung zurück |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_2)(int, IList&lt;Operator&gt;) | Fügt Operatoren an der angegebenen Position ein. |
| override [Insert](../../aspose.pdf/operatorcollection/insert/#insert)(int, Operator) | Fügt einen Operator in die Sammlung ein. |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_1)(int, Operator[]) | Fügt Operatoren an der angegebenen Position ein. |
| override [Remove](../../aspose.pdf/operatorcollection/remove/)(Operator) | Entfernt einen Operator aus der Sammlung. |
| [Replace](../../aspose.pdf/operatorcollection/replace/)(IList&lt;Operator&gt;) | Ersetzt Operatoren in der Sammlung durch andere Operatoren. |
| override [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate)() | Setzt das Dokumentenupdate fort. Aktualisiert den Inhaltsstream, falls Änderungen ausstehen. |
| [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate_1)(bool) | Setzt das Dokumentenupdate fort. Aktualisiert den Inhaltsstream, falls Änderungen ausstehen. Markiert alle Operatoren als "geändert", wenn der Parameter invalidate true ist. |
| override [SuppressUpdate](../../aspose.pdf/operatorcollection/suppressupdate/)() | Unterdrückt die Aktualisierung der Inhaltsdaten. Der Inhaltsstream wird nicht aktualisiert, bis ResumeUpdate aufgerufen wird. |
| override [ToString](../../aspose.pdf/operatorcollection/tostring/)() | Gibt die textuelle Darstellung des Operators zurück. |

### Siehe auch

* Klasse [BaseOperatorCollection](../baseoperatorcollection/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)