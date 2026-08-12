---
title: "Aspose::Pdf::ImagePlacement class"
linktitle: "ImagePlacement"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::ImagePlacement class. Representerar egenskaper hos en bild som placerats på en Pdf-dokumentsida i C++."
type: docs
weight: 8000
url: /sv/cpp/aspose.pdf/imageplacement/
---
## ImagePlacement class


Representerar egenskaper hos en bild som placerats på en [Pdf](../) dokumentsida.

```cpp
class ImagePlacement : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_CompositingParameters](./get_compositingparameters/)() const | Hämtar sammansättningsparametrar för grafikstatus som är aktiv för bilden som placerats på sidan. |
| [get_Image](./get_image/)() const | Hämtar relaterat [XImage](../ximage/) resursobjekt. |
| [get_Matrix](./get_matrix/)() const | Aktuell transformationsmatris för denna bild. |
| [get_Operator](./get_operator/)() const | [Operator](../operator/) som används för att visa bilden. |
| [get_Page](./get_page/)() const | Hämtar sidan som innehåller bilden. |
| [get_Rectangle](./get_rectangle/)() const | Hämtar rektangeln för [Image](../image/). |
| [get_Resolution](./get_resolution/)() const | Hämtar upplösningen för [Image](../image/). |
| [get_Rotation](./get_rotation/)() const | Hämtar rotationsvinkeln för [Image](../image/). |
| [Hide](./hide/)() | Ta bort bilden från sidan. |
| [Replace](./replace/)(const System::SharedPtr\<System::IO::Stream\>\&) | Ersätt bild i samlingen med en annan bild. |
| [Save](./save/)(const System::SharedPtr\<System::IO::Stream\>\&) | Sparar bilden med motsvarande transformationer: skalning, rotation och upplösning. |
| [Save](./save/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) | Sparar bilden med motsvarande transformationer: skalning, rotation och upplösning. |
## Anmärkningar


När en bild placeras på en sida kan den ha andra dimensioner än de fysiska dimensioner som definieras i [Resources](../resources/). Objektet [ImagePlacement](./) är avsett att tillhandahålla sådan information som dimensioner, upplösning och så vidare.
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
