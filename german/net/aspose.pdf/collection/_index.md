---
title: Collection
second_title: Aspose.PDF für .NET-API-Referenz
description: Repräsentiert die Klasse für Collection 12.3.5 Collections.
type: docs
weight: 1480
url: /de/net/aspose.pdf/collection/
---
## Collection class

Repräsentiert die Klasse für Collection (12.3.5 Collections).

```csharp
public class Collection : EmbeddedFileCollection
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Collection](collection)() | Initialisiert ein neues Sammlungsobjekt. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Count](../../aspose.pdf/embeddedfilecollection/count) { get; } | Ruft die Anzahl der eingebetteten Dateien in der Sammlung ab. |
| [DefaultEntry](../../aspose.pdf/collection/defaultentry) { get; } | Standardname der eingebetteten Datei. |
| [IsSynchronized](../../aspose.pdf/embeddedfilecollection/issynchronized) { get; } | Ruft einen Wert ab, der angibt, ob der Zugriff auf diese Sammlung synchronisiert (threadsicher) ist. |
| [Item](../../aspose.pdf/embeddedfilecollection/item) { get; } | Ruft die eingebettete Datei nach ihrem Index ab. (2 indexers) |
| [Keys](../../aspose.pdf/embeddedfilecollection/keys) { get; } | Gibt eine Liste der Dateianhangsschlüssel zurück. |
| [SyncRoot](../../aspose.pdf/embeddedfilecollection/syncroot) { get; } | Ruft ein Objekt ab, das verwendet werden kann, um den Zugriff auf diese Sammlung zu synchronisieren. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../aspose.pdf/embeddedfilecollection/add)(FileSpecification) | Fügt der Sammlung eingebettete Dateispezifikationen hinzu. |
| [Add](../../aspose.pdf/embeddedfilecollection/add)(string, FileSpecification) | Fügt eine Datei zu eingebetteten Dateien mit dem angegebenen Schlüssel hinzu. |
| [CopyTo](../../aspose.pdf/embeddedfilecollection/copyto)(FileSpecification[], int) | Kopiert das Array des FileSpecification-Objekts in die Sammlung. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete)() | Alle eingebetteten Dateien aus dem Dokument entfernen. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete)(string) | Eingebettete Datei nach Namen löschen. |
| [DeleteByKey](../../aspose.pdf/embeddedfilecollection/deletebykey)(string) | Löscht die Datei anhand ihres Schlüssels in der Sammlung aus der Sammlung. |
| [FindByName](../../aspose.pdf/embeddedfilecollection/findbyname)(string) | Gibt die eingebettete Datei nach ihrem Namen zurück. |
| [GetEnumerator](../../aspose.pdf/embeddedfilecollection/getenumerator)() | Gibt den Auflistungszähler zurück. |

### Siehe auch

* class [EmbeddedFileCollection](../embeddedfilecollection)
* namensraum [Aspose.Pdf](../../aspose.pdf)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
