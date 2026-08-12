---
title: "Aspose::Pdf::Annotations::SoundAnnotation clase"
linktitle: "SoundAnnotation"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::SoundAnnotation clase. Representa una anotación de sonido que contiene sonido grabado desde el micrófono del ordenador o importado desde un archivo en C++."
type: docs
weight: 10000
url: /es/cpp/aspose.pdf.annotations/soundannotation/
---
## SoundAnnotation class


Representa una anotación de sonido que contiene audio grabado desde el micrófono de la computadora o importado desde un archivo.

```cpp
class SoundAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Acepta un objeto visitante para procesar la anotación. |
| [get_AnnotationType](./get_annotationtype/)() override | Obtiene el tipo de anotación. |
| [get_Icon](./get_icon/)() | Obtiene un ícono que se usará al mostrar la anotación. |
| [get_SoundData](./get_sounddata/)() | Obtiene un objeto de sonido que define el sonido que se reproducirá cuando se active la anotación. |
| [set_Icon](./set_icon/)(SoundIcon) | Establece un ícono que se usará al mostrar la anotación. |
| [SoundAnnotation](./soundannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::String\&) | Crea una nueva anotación de sonido en la página especificada. |
| [SoundAnnotation](./soundannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::String\&, const System::SharedPtr\<SoundSampleData\>\&) | Crea una nueva anotación de sonido en la página especificada. |
## Ver también

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
