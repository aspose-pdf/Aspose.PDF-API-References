---
title: "Aspose::Pdf::Annotations::FileAttachmentAnnotation clase"
linktitle: "FileAttachmentAnnotation"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::FileAttachmentAnnotation clase. La clase describe la anotación de adjunto de archivo en C++."
type: docs
weight: 3000
url: /es/cpp/aspose.pdf.annotations/fileattachmentannotation/
---
## FileAttachmentAnnotation class


Clase que describe la anotación de adjunto de archivo.

```cpp
class FileAttachmentAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Acepta un objeto visitante para procesar la anotación. |
| [FileAttachmentAnnotation](./fileattachmentannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::SharedPtr\<FileSpecification\>\&) | Crea una nueva anotación FileAttachment en la página especificada. |
| [get_AnnotationType](./get_annotationtype/)() override | Obtiene el tipo de anotación. |
| [get_File](./get_file/)() | La especificación del archivo asociado a esta anotación. |
| [get_Icon](./get_icon/)() | Obtiene el ícono que se usará al mostrar la anotación. |
| [get_Opacity](./get_opacity/)() | Obtiene la opacidad del ícono de 0 a 1: 0 - completamente transparente, 1 - completamente opaco. |
| [set_File](./set_file/)(const System::SharedPtr\<FileSpecification\>\&) | La especificación del archivo asociado a esta anotación. |
| [set_Icon](./set_icon/)(FileIcon) | Establece el ícono que se usará al mostrar la anotación. |
| [set_Opacity](./set_opacity/)(double) | Establece la opacidad del ícono de 0 a 1: 0 - completamente transparente, 1 - completamente opaco. |
## Ver también

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
