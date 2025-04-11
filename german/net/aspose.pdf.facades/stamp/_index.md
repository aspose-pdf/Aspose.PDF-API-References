---
title: Class Stamp
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.Stamp-Klasse. Klasse, die einen Stempel darstellt
type: docs
weight: 4720
url: /de/net/aspose.pdf.facades/stamp/
---
## Klasse Stamp

Klasse, die einen Stempel darstellt.

```csharp
public sealed class Stamp
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Stamp](stamp/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BlendingSpace](../../aspose.pdf.facades/stamp/blendingspace/) { get; set; } | Ruft einen BlendingColorSpace-Wert ab oder legt ihn fest, der einen Farbraum definiert, der verwendet wird, um Transparenz- und Mischoperationen auf der Seite durchzuführen. |
| [IsBackground](../../aspose.pdf.facades/stamp/isbackground/) { get; set; } | Ruft den Hintergrundstatus ab oder legt ihn fest. Wenn wahr, wird der Stempel als Hintergrund der gestempelten Seite platziert. Standardmäßig ist er auf falsch gesetzt. |
| [Opacity](../../aspose.pdf.facades/stamp/opacity/) { get; set; } | Ruft die Opazität des Stempels ab oder legt sie fest. |
| [PageNumber](../../aspose.pdf.facades/stamp/pagenumber/) { get; set; } | Ruft die Seitenzahl ab oder legt sie fest. |
| [Pages](../../aspose.pdf.facades/stamp/pages/) { get; set; } | Ruft ein Array mit Seitenzahlen ab oder legt es fest, die vom Stempel betroffen sind. Wenn Pages = null, sind alle Seiten des Dokuments betroffen. |
| [Quality](../../aspose.pdf.facades/stamp/quality/) { get; set; } | Ruft die Qualität des Bildstempels in Prozent ab oder legt sie fest. Gültige Werte 0..100%. |
| [Rotation](../../aspose.pdf.facades/stamp/rotation/) { get; set; } | Ruft die Rotation des Stempels in Grad ab oder legt sie fest. |
| [StampId](../../aspose.pdf.facades/stamp/stampid/) { get; set; } | Ruft die Kennung des Stempels ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage)(Stream) | Legt das Bild fest, das als Stempel verwendet wird. |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage_1)(string) | Legt das Bild als Stempel fest. |
| [BindLogo](../../aspose.pdf.facades/stamp/bindlogo/)(FormattedText) | Legt den Text als Stempel fest. |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf)(Stream, int) | Legt die PDF-Datei und die Seitenzahl fest, die als Stempel verwendet werden. |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf_1)(string, int) | Legt die PDF-Datei und die Seitenzahl fest, die als Stempel verwendet werden. |
| [BindTextState](../../aspose.pdf.facades/stamp/bindtextstate/)(TextState) | Legt den Textzustand des Stempeltextes fest. |
| [SetImageSize](../../aspose.pdf.facades/stamp/setimagesize/)(float, float) | Legt die Größe des Bildstempels fest. Das Bild wird gemäß den angegebenen Werten skaliert. |
| [SetOrigin](../../aspose.pdf.facades/stamp/setorigin/)(float, float) | Legt die Position auf der Seite fest, an der der Stempel platziert wird. |

### Siehe auch

* Namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../)