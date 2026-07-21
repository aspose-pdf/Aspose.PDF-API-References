---
title: "Aspose::Pdf::Annotations::MovieAnnotation class"
linktitle: "MovieAnnotation"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::MovieAnnotation class. Representa una anotación de película que contiene gráficos animados y sonido para ser presentados en la pantalla del ordenador y a través de los altavoces. Cuando la anotación se activa, la película se reproduce en C++."
type: docs
weight: 6700
url: /es/cpp/aspose.pdf.annotations/movieannotation/
---
## MovieAnnotation class


Representa una anotación de película que contiene gráficos animados y sonido para presentarse en la pantalla del ordenador y a través de los altavoces. Cuando la anotación se activa, la película se reproduce.

```cpp
class MovieAnnotation : public Aspose::Pdf::Annotations::Annotation,
                        public Aspose::Pdf::Annotations::Annotation::ITitledAnnotation
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Acepta un objeto visitante para procesar la anotación. |
| [get_AnnotationType](./get_annotationtype/)() override | Obtiene el tipo de anotación. |
| [get_Aspect](./get_aspect/)() | Obtiene el ancho y la altura del cuadro delimitador de la película, en píxeles. |
| [get_File](./get_file/)() | Obtiene una especificación de archivo que identifica un archivo de película autodescriptivo. |
| [get_Poster](./get_poster/)() | Obtiene una bandera o flujo que especifica si y cómo se debe mostrar una imagen de póster que representa la película. Si es verdadero, la imagen del póster se obtendrá del archivo de la película; si es falso, no se mostrará ningún póster. |
| [get_Rotate](./get_rotate/)() | Obtiene el número de grados en que la película debe rotarse en sentido horario respecto a la página. El valor debe ser un múltiplo de 90. |
| [get_Title](./get_title/)() override | Obtiene el título de la anotación de película. |
| [MovieAnnotation](./movieannotation/)(const System::SharedPtr\<Document\>\&, const System::String\&) | Constructor para usar con Generator. |
| [MovieAnnotation](./movieannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::String\&) | Crea una nueva anotación de sonido en la página especificada. |
| [set_Aspect](./set_aspect/)(const System::SharedPtr\<Point\>\&) | Establece el ancho y la altura del cuadro delimitador de la película, en píxeles. |
| [set_File](./set_file/)(const System::SharedPtr\<FileSpecification\>\&) | Establece una especificación de archivo que identifica un archivo de película autodescriptivo. |
| [set_Poster](./set_poster/)(bool) | Establece una bandera o flujo que especifica si y cómo se debe mostrar una imagen de póster que representa la película. Si es verdadero, la imagen del póster se obtendrá del archivo de la película; si es falso, no se mostrará ningún póster. |
| [set_Rotate](./set_rotate/)(int32_t) | Establece el número de grados en que la película debe rotarse en sentido horario respecto a la página. El valor debe ser un múltiplo de 90. |
| [set_Title](./set_title/)(System::String) override | Establece el título de la anotación de película. |
## Ver también

* Class [Annotation](../annotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
