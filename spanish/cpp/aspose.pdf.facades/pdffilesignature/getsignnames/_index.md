---
title: "Aspose::Pdf::Facades::PdfFileSignature::GetSignNames método"
linktitle: "GetSignNames"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfFileSignature::GetSignNames método. Obtiene los nombres de todas las firmas no vacías en C++."
type: docs
weight: 2500
url: /es/cpp/aspose.pdf.facades/pdffilesignature/getsignnames/
---
## PdfFileSignature::GetSignNames method


Obtiene los nombres de todas las firmas no vacías.

```cpp
System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Pdf::Facades::PdfFileSignature::GetSignNames(bool onlyActive=true)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| onlyActive | bool | si es verdadero, devuelve solo firmas activas; de lo contrario, devuelve todas las firmas. |

### ReturnValue

Devuelve un IList<string>.

## Deprecated
El método puede producir los mismos nombres de firma, que no pueden distinguirse durante la verificación. Utilice GetSignatureNames(bool onlyActive) en su lugar.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [String](../../../system/string/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
