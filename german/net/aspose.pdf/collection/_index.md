---
title: Class Collection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Collection-Klasse. Repräsentiert die Klasse für Collection12.3.5 Sammlungen
type: docs
weight: 3020
url: /de/net/aspose.pdf/collection/
---
## Sammlungsklasse

Repräsentiert die Klasse für Collection(12.3.5 Sammlungen).

```csharp
public class Collection : EmbeddedFileCollection
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Collection](collection/)() | Initialisiert ein neues Collection-Objekt. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Count](../../aspose.pdf/embeddedfilecollection/count/) { get; } | Gibt die Anzahl der eingebetteten Dateien in der Sammlung zurück. |
| [DefaultEntry](../../aspose.pdf/collection/defaultentry/) { get; } | Standardname der eingebetteten Datei. |
| [IsSynchronized](../../aspose.pdf/embeddedfilecollection/issynchronized/) { get; } | Gibt einen Wert zurück, der angibt, ob der Zugriff auf diese Sammlung synchronisiert ist (thread-sicher). |
| [Item](../../aspose.pdf/embeddedfilecollection/item/) { get; } | Gibt die eingebettete Datei nach ihrem Index zurück. (2 Indizes) |
| [Keys](../../aspose.pdf/embeddedfilecollection/keys/) { get; } | Gibt eine Liste der Schlüssel für Dateianhänge zurück. |
| [Schema](../../aspose.pdf/collection/schema/) { get; } | Gibt ein "Schema" einer Dokumentensammlung zurück. |
| [SyncRoot](../../aspose.pdf/embeddedfilecollection/syncroot/) { get; } | Gibt ein Objekt zurück, das verwendet werden kann, um den Zugriff auf diese Sammlung zu synchronisieren. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(FileSpecification) | Fügt die Spezifikation der eingebetteten Datei in die Sammlung ein. |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(string, FileSpecification) | Fügt eine Datei zu den eingebetteten Dateien mit dem angegebenen Schlüssel hinzu. |
| [CopyTo](../../aspose.pdf/embeddedfilecollection/copyto/)(FileSpecification[], int) | Kopiert ein Array von FileSpecification-Objekten in die Sammlung. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)() | Entfernt alle eingebetteten Dateien aus dem Dokument. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)(string) | Löscht die eingebettete Datei nach Namen. |
| [DeleteByKey](../../aspose.pdf/embeddedfilecollection/deletebykey/)(string) | Löscht die Datei aus der Sammlung nach ihrem Schlüssel in der Sammlung. |
| [FindByName](../../aspose.pdf/embeddedfilecollection/findbyname/)(string) | Gibt die eingebettete Datei nach ihrem Namen zurück. |
| [GetEnumerator](../../aspose.pdf/embeddedfilecollection/getenumerator/)() | Gibt den Enumerator der Sammlung zurück. |
| [GetSortedCollection](../../aspose.pdf/collection/getsortedcollection/)() | Gibt eine Sammlung von Dateien zurück, die gemäß der Spezifikation sortiert sind. |

### Siehe auch

* Klasse [EmbeddedFileCollection](../embeddedfilecollection/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)