---
title: "Aspose::Pdf::PdfPageStamp clase"
linktitle: "PdfPageStamp"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::PdfPageStamp clase. Clase que representa un sello que utiliza una página PDF como sello en C++."
type: docs
weight: 15100
url: /es/cpp/aspose.pdf/pdfpagestamp/
---
## PdfPageStamp class


Clase que representa un sello que utiliza una página PDF como sello.

```cpp
class PdfPageStamp : public Aspose::Pdf::Stamp
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_PdfPage](./get_pdfpage/)() const | Obtiene la página que se usará como sello. |
| [PdfPageStamp](./pdfpagestamp/)(const System::SharedPtr\<Page\>\&) | Constructor de [PdfPageStamp](./). |
| [PdfPageStamp](./pdfpagestamp/)(const System::String\&, int32_t) | Crea un sello de página [Pdf](../) a partir de la página especificada del documento en el archivo especificado. |
| [PdfPageStamp](./pdfpagestamp/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t) | Crea un sello de página [Pdf](../) a partir de la página especificada en el documento desde el flujo. |
| [Put](./put/)(System::SharedPtr\<Page\>) override | Coloca el sello en la página especificada. |
| [set_PdfPage](./set_pdfpage/)(const System::SharedPtr\<Page\>\&) | Establece la página que se usará como sello. |
## Ver también

* Class [Stamp](../stamp/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
