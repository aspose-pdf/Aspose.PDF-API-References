---
title: "Aspose::Pdf::Facades::PdfFileSignature::ExtractImage método"
linktitle: "ExtractImage"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfFileSignature::ExtractImage método. Extrae la imagen de la firma en C++."
type: docs
weight: 900
url: /es/cpp/aspose.pdf.facades/pdffilesignature/extractimage/
---
## PdfFileSignature::ExtractImage(const System::SharedPtr\<SignatureName\>\&) method


Extrae la imagen de la firma.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Pdf::Facades::PdfFileSignature::ExtractImage(const System::SharedPtr<SignatureName> &signName)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | El nombre de la firma. |

### ReturnValue

Si la imagen se encontró correctamente, devuelve el objeto de secuencia; de lo contrario, null.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [SignatureName](../../signaturename/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::ExtractImage(const System::String\&) method


Extrae la imagen de la firma.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Pdf::Facades::PdfFileSignature::ExtractImage(const System::String &signName)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signName | const System::String\& | El nombre de la firma. |

### ReturnValue

Si la imagen se encontró correctamente, devuelve el objeto de secuencia; de lo contrario, null.

## Deprecated
Utilice el método ExtractImage(SignatureName) en su lugar.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
