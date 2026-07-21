---
title: "Aspose::Pdf::Forms::SignatureField::ExtractImage método"
linktitle: "ExtractImage"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Forms::SignatureField::ExtractImage method. Extrae la imagen de la firma como flujo codificado en jpeg en C++."
type: docs
weight: 400
url: /es/cpp/aspose.pdf.forms/signaturefield/extractimage/
---
## SignatureField::ExtractImage() method


Extrae la imagen de la firma como un flujo codificado en JPEG.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Pdf::Forms::SignatureField::ExtractImage()
```


### ReturnValue

Si la imagen se encontró correctamente, devuelve el objeto de flujo codificado en jpeg; de lo contrario, null.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [SignatureField](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## SignatureField::ExtractImage(const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) method


Extrae la imagen de la firma como un flujo codificado.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Pdf::Forms::SignatureField::ExtractImage(const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| format | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | [Image](../../../aspose.pdf/image/) formato para codificación. |

### ReturnValue

Si la imagen se encontró correctamente, devuelve el objeto encodedstream; de lo contrario, null.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [SignatureField](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
