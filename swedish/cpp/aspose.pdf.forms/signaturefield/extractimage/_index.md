---
title: "Aspose::Pdf::Forms::SignatureField::ExtractImage metod"
linktitle: "ExtractImage"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Forms::SignatureField::ExtractImage metod. Extraherar signaturens bild som JPEG‑kodad ström i C++."
type: docs
weight: 400
url: /sv/cpp/aspose.pdf.forms/signaturefield/extractimage/
---
## SignatureField::ExtractImage() method


Extraherar signaturens bild som JPEG-kodad ström.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Pdf::Forms::SignatureField::ExtractImage()
```


### ReturnValue

Om bilden hittades framgångsrikt returneras ett JPEG‑kodad strömobjekt; annars null.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [SignatureField](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## SignatureField::ExtractImage(const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) method


Extraherar signaturens bild som kodad ström.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Pdf::Forms::SignatureField::ExtractImage(const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| format | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | [Image](../../../aspose.pdf/image/) format för kodning. |

### ReturnValue

Om bilden hittades framgångsrikt returneras ett kodad strömobjekt; annars null.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [SignatureField](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
