---
title: Class EmbeddedFileCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.EmbeddedFileCollection-Klasse. Klasse, die eine Sammlung eingebetteter Dateien darstellt
type: docs
weight: 4010
url: /de/net/aspose.pdf/embeddedfilecollection/
---
## EmbeddedFileCollection-Klasse

Klasse, die eine Sammlung eingebetteter Dateien darstellt.

```csharp
public class EmbeddedFileCollection : ICollection<FileSpecification>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Count](../../aspose.pdf/embeddedfilecollection/count/) { get; } | Gibt die Anzahl der eingebetteten Dateien in der Sammlung zurück. |
| [IsSynchronized](../../aspose.pdf/embeddedfilecollection/issynchronized/) { get; } | Gibt einen Wert zurück, der angibt, ob der Zugriff auf diese Sammlung synchronisiert ist (thread-sicher). |
| [Item](../../aspose.pdf/embeddedfilecollection/item/) { get; } | Gibt die eingebettete Datei nach ihrem Index zurück. (2 Indizes) |
| [Keys](../../aspose.pdf/embeddedfilecollection/keys/) { get; } | Gibt eine Liste der Schlüssel für Dateianhänge zurück. |
| [SyncRoot](../../aspose.pdf/embeddedfilecollection/syncroot/) { get; } | Gibt ein Objekt zurück, das verwendet werden kann, um den Zugriff auf diese Sammlung zu synchronisieren. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../aspose.pdf/embeddedfilecollection/add/#add)(FileSpecification) | Fügt die Spezifikation einer eingebetteten Datei zur Sammlung hinzu. |
| [Add](../../aspose.pdf/embeddedfilecollection/add/#add_1)(string, FileSpecification) | Fügt eine Datei mit dem angegebenen Schlüssel zu den eingebetteten Dateien hinzu. |
| [CopyTo](../../aspose.pdf/embeddedfilecollection/copyto/)(FileSpecification[], int) | Kopiert ein Array von FileSpecification-Objekten in die Sammlung. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/#delete)() | Entfernt alle eingebetteten Dateien aus dem Dokument. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/#delete_1)(string) | Löscht die eingebettete Datei nach Name. |
| [DeleteByKey](../../aspose.pdf/embeddedfilecollection/deletebykey/)(string) | Löscht die Datei aus der Sammlung nach ihrem Schlüssel in der Sammlung. |
| [FindByName](../../aspose.pdf/embeddedfilecollection/findbyname/)(string) | Gibt die eingebettete Datei nach ihrem Namen zurück. |
| [GetEnumerator](../../aspose.pdf/embeddedfilecollection/getenumerator/)() | Gibt den Enumerator der Sammlung zurück. |

### Siehe auch

* Klasse [FileSpecification](../filespecification/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)