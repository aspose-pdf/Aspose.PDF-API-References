---
title: Class DicomDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.DicomDevice-Klasse. Stellt ein Bildgerät dar, das hilft, PDF-Dokumentseiten im Dicom-Format zu speichern
type: docs
weight: 3560
url: /de/net/aspose.pdf.devices/dicomdevice/
---
## DicomDevice-Klasse

Stellt ein Bildgerät dar, das hilft, PDF-Dokumentseiten im Dicom-Format zu speichern.

```csharp
public sealed class DicomDevice : ImageDevice
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [DicomDevice](dicomdevice/#constructor)() | Initialisiert eine neue Instanz der `DicomDevice`-Klasse mit der Standardauflösung. |
| [DicomDevice](dicomdevice/#constructor_2)(PageSize) | Initialisiert eine neue Instanz der `DicomDevice`-Klasse mit der angegebenen Seitengröße, mit der Standardauflösung (=150). |
| [DicomDevice](dicomdevice/#constructor_1)(Resolution) | Initialisiert eine neue Instanz der `DicomDevice`-Klasse. Auflösung für die resultierende Bilddatei, siehe [`Resolution`](../resolution/) Klasse. |
| [DicomDevice](dicomdevice/#constructor_4)(int, int) | Initialisiert eine neue Instanz der `DicomDevice`-Klasse mit den angegebenen Bilddimensionen, mit der Standardauflösung (=150). |
| [DicomDevice](dicomdevice/#constructor_3)(PageSize, Resolution) | Initialisiert eine neue Instanz der `DicomDevice`-Klasse mit der angegebenen Seitengröße und Auflösung. |
| [DicomDevice](dicomdevice/#constructor_5)(int, int, Resolution) | Initialisiert eine neue Instanz der `DicomDevice`-Klasse mit den angegebenen Bilddimensionen und der Auflösung. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Ruft den Seitensystemtyp (Media/Crop-Boxen) ab oder legt ihn fest. Der Wert CropBox wird standardmäßig verwendet. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Ruft den Formularpräsentationsmodus ab oder legt ihn fest. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Ruft die Bildausgabehöhe ab. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Ruft die Rendering-Optionen ab oder legt sie fest. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Ruft die Bildauflösung ab. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Ruft die Bildausgabebreite ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Process](../../aspose.pdf.devices/dicomdevice/process/#process)(Page, Stream) | Konvertiert die Seite in Dicom und speichert sie im Ausgabestream. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Führt eine Operation auf der angegebenen Seite aus und speichert die Ergebnisse in der Datei. |

### Siehe auch

* Klasse [ImageDevice](../imagedevice/)
* Namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* Assembly [Aspose.PDF](../../)