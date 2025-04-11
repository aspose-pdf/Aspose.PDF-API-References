---
title: Class XImageCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XImageCollection-Klasse. Klasse, die eine XImage-Sammlung darstellt
type: docs
weight: 11360
url: /de/net/aspose.pdf/ximagecollection/
---
## XImageCollection-Klasse

Klasse, die eine XImage-Sammlung darstellt.

```csharp
public sealed class XImageCollection : ICollection<XImage>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Count](../../aspose.pdf/ximagecollection/count/) { get; } | Anzahl der Bilder in der Sammlung. |
| [IsReadOnly](../../aspose.pdf/ximagecollection/isreadonly/) { get; } | Gibt einen Wert zurück, der angibt, ob die Sammlung schreibgeschützt ist. |
| [IsSynchronized](../../aspose.pdf/ximagecollection/issynchronized/) { get; } | Gibt true zurück, wenn das Objekt synchronisiert ist. |
| [Item](../../aspose.pdf/ximagecollection/item/) { get; } | Holt ein Bild aus der Sammlung nach seinem Index. (2 Indizes) |
| [Names](../../aspose.pdf/ximagecollection/names/) { get; } | Holt ein Array von Bildnamen. |
| [SyncRoot](../../aspose.pdf/ximagecollection/syncroot/) { get; } | Gibt das Synchronisationsobjekt zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../aspose.pdf/ximagecollection/add/#add)(BitmapInfo) | Fügt eine Entität am Ende der Sammlung hinzu, sodass die Entität über den letzten Index zugänglich ist. |
| [Add](../../aspose.pdf/ximagecollection/add/#add_3)(Stream) | Fügt eine Entität am Ende der Sammlung hinzu, sodass die Entität über den letzten Index zugänglich ist. |
| [Add](../../aspose.pdf/ximagecollection/add/#add_2)(XImage) | Fügt ein neues Bild zur Bildliste hinzu. Diese Methode fügt das Bild als Referenz zum gleichen PdfObject hinzu (was die Dateigröße verringern kann). |
| [Add](../../aspose.pdf/ximagecollection/add/#add_1)(BitmapInfo, ImageFilterType) | Fügt eine Entität am Ende der Sammlung hinzu, sodass die Entität über den letzten Index zugänglich ist. |
| [Add](../../aspose.pdf/ximagecollection/add/#add_4)(Stream, ImageFilterType) | Fügt eine Entität am Ende der Sammlung hinzu, sodass die Entität über den letzten Index zugänglich ist. |
| [Add](../../aspose.pdf/ximagecollection/add/#add_5)(Stream, int) | Fügt eine Entität am Ende der Sammlung hinzu, sodass die Entität über den letzten Index zugänglich ist. |
| [Clear](../../aspose.pdf/ximagecollection/clear/)() | Löscht alle Elemente aus der Sammlung. |
| [Contains](../../aspose.pdf/ximagecollection/contains/)(XImage) | Bestimmt, ob die Sammlung einen bestimmten Wert enthält. |
| [CopyTo](../../aspose.pdf/ximagecollection/copyto/)(XImage[], int) | Kopiert ein Array von Bildern in die Sammlung. |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete)() | Löscht Bilder aus der Sammlung. |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_1)(int) | Entfernt den Index aus der Sammlung nach Index. |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_3)(string) | Entfernt ein Element aus der Sammlung nach Name. |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_2)(int, ImageDeleteAction) | Entfernt ein Bild aus der Sammlung nach Index und führt die durch den Aktionsparameter angegebene Aktion aus. |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_4)(string, ImageDeleteAction) | Entfernt ein Element aus der Sammlung nach Name. |
| [GetEnumerator](../../aspose.pdf/ximagecollection/getenumerator/)() | Gibt den Enumerator der Sammlung zurück. |
| [GetImageName](../../aspose.pdf/ximagecollection/getimagename/)(XImage) | Gibt den Namen in der Bilderliste zurück, der der Schlüssel des angegebenen Bildes ist. |
| [Remove](../../aspose.pdf/ximagecollection/remove/)(XImage) | Entfernt ein Element aus der Sammlung, wirft NotImplementedException. |
| [Replace](../../aspose.pdf/ximagecollection/replace/#replace)(int, Stream) | Ersetzt ein Bild in der Sammlung durch ein anderes Bild. |
| [Replace](../../aspose.pdf/ximagecollection/replace/#replace_1)(int, Stream, int) | Ersetzt ein Bild in der Sammlung durch ein anderes Bild. |
| [Replace](../../aspose.pdf/ximagecollection/replace/#replace_2)(int, Stream, int, bool) | Ersetzt ein Bild in der Sammlung durch ein anderes Bild. |

### Siehe auch

* Klasse [XImage](../ximage/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)