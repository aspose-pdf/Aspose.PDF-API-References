---
title: "Aspose::Pdf::Annotations::RichMediaAnnotation clase"
linktitle: "RichMediaAnnotation"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::RichMediaAnnotation clase. La clase describe RichMediaAnnotation que permite incrustar datos de video/audio en un documento PDF en C++."
type: docs
weight: 9700
url: /es/cpp/aspose.pdf.annotations/richmediaannotation/
---
## RichMediaAnnotation class


La clase describe [RichMediaAnnotation](./) que permite incrustar datos de video/audio en un documento PDF.

```cpp
class RichMediaAnnotation : public Aspose::Pdf::Annotations::Annotation
```

## Enums

| Enumeración | Descripción |
| --- | --- |
| [ActivationEvent](./activationevent/) | Evento que activa la anotación. |
| [ContentType](./contenttype/) | Tipo del multimedia. |
## Métodos

| Método | Descripción |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Acepta visitante para esta anotación. |
| [AddCustomData](./addcustomdata/)(const System::String\&, const System::SharedPtr\<System::IO::Stream\>\&) | Agregar datos nombrados personalizados (por ejemplo, requeridos para el script flash). |
| [get_ActivateOn](./get_activateon/)() | Evento que activa la aplicación. |
| [get_AnnotationType](./get_annotationtype/)() override | Obtiene el tipo de anotación. |
| [get_Content](./get_content/)() | Datos del contenido Rich Media. |
| [get_CustomFlashVariables](./get_customflashvariables/)() const | Establece o obtiene variables flash que se pasan al reproductor. |
| [get_CustomPlayer](./get_customplayer/)() const | Establece o obtiene el reproductor flash personalizado para reproducir datos de video/audio. |
| [get_Type](./get_type/)() | Obtiene el tipo de contenido. Valores posibles: Audio, Video. |
| [RichMediaAnnotation](./richmediaannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Inicializa [RichMediaAnnotation](./). |
| [set_ActivateOn](./set_activateon/)(RichMediaAnnotation::ActivationEvent) | Evento que activa la aplicación. |
| [set_CustomFlashVariables](./set_customflashvariables/)(const System::String\&) | Establece o obtiene variables flash que se pasan al reproductor. |
| [set_CustomPlayer](./set_customplayer/)(const System::SharedPtr\<System::IO::Stream\>\&) | Establece o obtiene el reproductor flash personalizado para reproducir datos de video/audio. |
| [set_Type](./set_type/)(RichMediaAnnotation::ContentType) | Establece el tipo de contenido. Valores posibles: Audio, Video. |
| [SetContent](./setcontent/)(const System::String\&, const System::SharedPtr\<System::IO::Stream\>\&) | Establecer flujo de contenido. |
| [SetPoster](./setposter/)(const System::SharedPtr\<System::IO::Stream\>\&) | Establecer póster de la anotación. |
| [Update](./update/)() | Actualiza los datos con los parámetros especificados. |
## Ver también

* Class [Annotation](../annotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
