---
title: GifDevice
second_title: Aspose.PDF für .NET-API-Referenz
description: Stellt ein Bildgerät dar das hilft PDF-Dokumentseiten in GIF zu speichern.
type: docs
weight: 1700
url: /de/net/aspose.pdf.devices/gifdevice/
---
## GifDevice class

Stellt ein Bildgerät dar, das hilft, PDF-Dokumentseiten in GIF zu speichern.

```csharp
public sealed class GifDevice : ImageDevice
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [GifDevice](gifdevice#constructor)() | Initialisiert eine neue Instanz von[`GifDevice`](../gifdevice) Klasse mit Standardauflösung. |
| [GifDevice](gifdevice#constructor_2)(PageSize) | Initialisiert eine neue Instanz von[`GifDevice`](../gifdevice) Klasse mit angegebener Seitengröße, Standardauflösung (=150). |
| [GifDevice](gifdevice#constructor_1)(Resolution) | Initialisiert eine neue Instanz von[`GifDevice`](../gifdevice) Klasse.  Auflösung für die Ergebnisbilddatei, siehe[`Resolution`](../resolution) Klasse. |
| [GifDevice](gifdevice#constructor_4)(int, int) | Initialisiert eine neue Instanz von[`GifDevice`](../gifdevice) Klasse mit bereitgestellten Bildabmessungen, Standardauflösung (=150). |
| [GifDevice](gifdevice#constructor_3)(PageSize, Resolution) | Initialisiert eine neue Instanz von[`GifDevice`](../gifdevice)Klasse mit angegebener Seitengröße und Auflösung. |
| [GifDevice](gifdevice#constructor_5)(int, int, Resolution) | Initialisiert eine neue Instanz von[`GifDevice`](../gifdevice) Klasse mit bereitgestellten Bildabmessungen und Auflösung. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype) { get; set; } | Holt oder setzt den Seitenkoordinatentyp (Media/Crop-Boxen). CropBox-Wert wird standardmäßig verwendet. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode) { get; set; } | Ruft den Präsentationsmodus des Formulars ab oder legt ihn fest. |
| [Height](../../aspose.pdf.devices/imagedevice/height) { get; } | Ruft die Bildausgabehöhe ab. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions) { get; set; } | Ruft Wiedergabeoptionen ab oder legt sie fest. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution) { get; } | Ruft die Bildauflösung ab. |
| [Width](../../aspose.pdf.devices/imagedevice/width) { get; } | Ruft die Bildausgabebreite ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Process](../../aspose.pdf.devices/gifdevice/process#process)(Page, Stream) | Wandelt die Seite in gif um und speichert sie im Ausgabestream. |
| [Process](../../aspose.pdf.devices/pagedevice/process)(Page, string) | Führt einige Operationen auf der angegebenen Seite aus und speichert die Ergebnisse in der Datei. |

### Siehe auch

* class [ImageDevice](../imagedevice)
* namensraum [Aspose.Pdf.Devices](../../aspose.pdf.devices)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->