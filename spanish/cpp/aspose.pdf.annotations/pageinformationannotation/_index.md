---
title: "Clase Aspose::Pdf::Annotations::PageInformationAnnotation"
linktitle: "PageInformationAnnotation"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Annotations::PageInformationAnnotation. Representa una anotación de Información de Página en un documento PDF. Esta anotación contiene el nombre del archivo, el número de página y la fecha y hora de creación de la anotación en C++."
type: docs
weight: 7000
url: /es/cpp/aspose.pdf.annotations/pageinformationannotation/
---
## PageInformationAnnotation class


Representa una anotación de Información de [Página](../../aspose.pdf/page/) en un documento PDF. Esta anotación contiene el nombre del archivo, el número de página y la fecha y hora de creación de la anotación.

```cpp
class PageInformationAnnotation : public Aspose::Pdf::Annotations::PrinterMarkAnnotation
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Acepta un visitante para el procesamiento de anotaciones. |
| [get_AnnotationType](./get_annotationtype/)() override | Obtiene el tipo de anotación. |
| [PageInformationAnnotation](./pageinformationannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Inicializa una nueva instancia de la clase [PageInformationAnnotation](./) en la página dada en la ubicación especificada. |
## Observaciones


Esta clase se utiliza principalmente para agregar metadatos a una página específica del documento PDF, lo que puede ser útil para propósitos de seguimiento y referencia. Por ejemplo, puede usarse para marcar páginas durante el proceso de impresión o para proporcionar información adicional sobre la página al visualizar el documento.
## Ver también

* Class [PrinterMarkAnnotation](../printermarkannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
