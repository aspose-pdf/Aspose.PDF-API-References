---
title: "Clase Aspose::Pdf::PdfANonSpecificationFlags"
linktitle: "PdfANonSpecificationFlags"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::PdfANonSpecificationFlags. Esta clase contiene banderas para controlar la conversión PDF/A en casos en que el documento PDF de origen no corresponde a la especificación PDF. Si se usan las banderas de esta clase, disminuye el rendimiento, pero es necesario cuando el documento PDF de origen no puede convertirse al formato PDF/A de la manera habitual. Por defecto, todas las banderas están establecidas en false en C++."
type: docs
weight: 14800
url: /es/cpp/aspose.pdf/pdfanonspecificationflags/
---
## PdfANonSpecificationFlags class


Esta clase contiene banderas para controlar la conversión a PDF/A en casos en que el documento PDF de origen no cumpla con la especificación PDF. Si se usan las banderas de esta clase, disminuye el rendimiento, pero es necesario cuando el documento PDF de origen no puede convertirse al formato PDF/A de la manera habitual. Por defecto, todas las banderas están establecidas en false.

```cpp
class PdfANonSpecificationFlags : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_CheckDifferentNamesInFontDictionaries](./get_checkdifferentnamesinfontdictionaries/)() const | Algunos documentos PDF contienen fuentes que tienen nombres diferentes en los datos internos. El uso de esta bandera impone una lógica de procesamiento especial para los casos en que los campos BaseFont y FontDescriptor.FontName son diferentes. |
| [PdfANonSpecificationFlags](./pdfanonspecificationflags/)() | Constructor. |
| [set_CheckDifferentNamesInFontDictionaries](./set_checkdifferentnamesinfontdictionaries/)(bool) | Algunos documentos PDF contienen fuentes que tienen nombres diferentes en los datos internos. El uso de esta bandera impone una lógica de procesamiento especial para los casos en que los campos BaseFont y FontDescriptor.FontName son diferentes. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
