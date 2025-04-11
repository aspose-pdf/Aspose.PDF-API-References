---
title: Class FileSpecification
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.FileSpecification-Klasse. Klasse, die eine eingebettete Datei darstellt
type: docs
weight: 4850
url: /de/net/aspose.pdf/filespecification/
---
## FileSpecification-Klasse

Klasse, die eine eingebettete Datei darstellt.

```csharp
public sealed class FileSpecification : IDisposable
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [FileSpecification](filespecification/#constructor)() | Erstellt eine neue leere Dateispezifikation. |
| [FileSpecification](filespecification/#constructor_3)(string) | Konstruktor für FileSpecification |
| [FileSpecification](filespecification/#constructor_1)(Stream, string) | Konstruktor für Dateispezifikation. |
| [FileSpecification](filespecification/#constructor_4)(string, Annotation) | Konstruktor für FileSpecification. |
| [FileSpecification](filespecification/#constructor_5)(string, string) | Konstruktor für FileSpecification. |
| [FileSpecification](filespecification/#constructor_2)(Stream, string, string) | Konstruktor für FileSpecification. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AFRelationship](../../aspose.pdf/filespecification/afrelationship/) { get; set; } | Zugehörige Datei-Beziehung. |
| [CollectionItem](../../aspose.pdf/filespecification/collectionitem/) { get; } | Gibt ein Sammlungsobjekt der Dateispezifikation zurück. |
| [Contents](../../aspose.pdf/filespecification/contents/) { get; set; } | Ruft die Inhaltsdatei ab oder legt sie fest. Diese Eigenschaft gibt Daten zurück, die im Speicher geladen sind, was bei großen Daten zu einer Out of Memory-Ausnahme führen kann. Um den Speicherverbrauch zu verringern, verwenden Sie bitte StreamContents. |
| [Description](../../aspose.pdf/filespecification/description/) { get; set; } | Ruft den mit der Dateispezifikation verbundenen Text ab oder legt ihn fest. |
| [Encoding](../../aspose.pdf/filespecification/encoding/) { get; set; } | Ruft das Kodierungsformat ab oder legt es fest. Mögliche Werte: Zip - Datei ist mit ZIP komprimiert, None - Datei ist nicht komprimiert. |
| [EncryptedPayload](../../aspose.pdf/filespecification/encryptedpayload/) { get; } | Ruft die verschlüsselte Nutzlast ab. |
| [FileSystem](../../aspose.pdf/filespecification/filesystem/) { get; set; } | Ruft den Namen des Dateisystems ab oder legt ihn fest. |
| [IncludeContents](../../aspose.pdf/filespecification/includecontents/) { get; set; } | Wenn wahr, werden die Inhalte der Datei in die Dateispezifikation aufgenommen. |
| [MIMEType](../../aspose.pdf/filespecification/mimetype/) { get; set; } | Ruft den Subtyp der eingebetteten Datei ab |
| [Name](../../aspose.pdf/filespecification/name/) { get; set; } | Ruft den Namen der Dateispezifikation ab oder legt ihn fest. |
| [Params](../../aspose.pdf/filespecification/params/) { get; set; } | Ruft die Dateiparameter ab. |
| [StreamContents](../../aspose.pdf/filespecification/streamcontents/) { get; } | Ruft die Inhalte der Datei als Stream ab. Inhalte werden nicht in den Speicher geladen, was den Speicherverbrauch verringert. Aber dieser Stream unterstützt keine Positionierung und die Length-Eigenschaft. Wenn Sie diese Funktionen benötigen, verwenden Sie bitte stattdessen die Contents-Eigenschaft. |
| [UnicodeName](../../aspose.pdf/filespecification/unicodename/) { get; set; } | Ruft den Unicode-Namen der Dateispezifikation ab oder legt ihn fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../aspose.pdf/filespecification/dispose/)() | Gibt die Inhalte frei. |
| [GetValue](../../aspose.pdf/filespecification/getvalue/)(string) | Ruft anwendungsspezifischen Parameter ab. |
| [SetValue](../../aspose.pdf/filespecification/setvalue/)(string, string) | Legt anwendungsspezifischen Parameter fest. |

### Siehe auch

* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)