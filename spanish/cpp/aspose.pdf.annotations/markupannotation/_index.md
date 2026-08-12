---
title: "Aspose::Pdf::Annotations::MarkupAnnotation class"
linktitle: "MarkupAnnotation"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::MarkupAnnotation class. Clase abstracta que representa una anotación de marcado en C++."
type: docs
weight: 6100
url: /es/cpp/aspose.pdf.annotations/markupannotation/
---
## MarkupAnnotation class


Clase abstracta que representa una anotación de marcado.

```cpp
class MarkupAnnotation : public Aspose::Pdf::Annotations::Annotation,
                         public Aspose::Pdf::Annotations::Annotation::ITitledAnnotation
```

## Métodos

| Método | Descripción |
| --- | --- |
| [ClearState](./clearstate/)() | Borra el estado y el modelo de estado de la anotación. Por ejemplo, borra el estado de revisión de una anotación. [Note](../../aspose.pdf/note/), el estado almacenado en otra anotación de texto que tiene claves de estado y modelo de estado. |
| [get_CreationDate](./get_creationdate/)() | Obtiene la fecha y hora en que se creó la anotación. |
| [get_InReplyTo](./get_inreplyto/)() | Una referencia a la anotación a la que esta anotación está "en respuesta a". Ambas anotaciones deben estar en la misma página del documento. |
| [get_Opacity](./get_opacity/)() | Obtiene el valor constante de opacidad que se utilizará al pintar la anotación. |
| [get_Popup](./get_popup/)() | Anotación emergente para ingresar o editar el texto asociado a esta anotación. |
| [get_ReplyType](./get_replytype/)() | Una cadena que especifica la relación (el "tipo de respuesta") entre esta anotación y la especificada por InReplyTo. |
| [get_RichText](./get_richtext/)() | Obtiene una cadena de texto enriquecido que se mostrará en la ventana emergente cuando se abra la anotación. |
| [get_Subject](./get_subject/)() | Obtiene el texto que representa la descripción del objeto. |
| [get_Title](./get_title/)() override | Obtiene una etiqueta de texto que se mostrará en la barra de título de la ventana emergente de la anotación cuando esté abierta y activa. Esta entrada debe identificar al usuario que agregó la anotación. |
| [GetState](./getstate/)() | Obtiene el estado de la anotación. [Note](../../aspose.pdf/note/), el estado almacenado en otra anotación de texto que tiene claves state y statemodel. |
| [GetStateModel](./getstatemodel/)() | Obtiene el modelo de estado de la anotación. [Note](../../aspose.pdf/note/), el estado almacenado en otra anotación de texto que tiene claves state y statemodel. |
| [MarkupAnnotation](./markupannotation/)(const System::SharedPtr\<Document\>\&) | Constructor para anotación de marcado. |
| [set_CreationDate](./set_creationdate/)(System::DateTime) | Obtiene la fecha y hora en que se creó la anotación. |
| [set_InReplyTo](./set_inreplyto/)(const System::SharedPtr\<Annotation\>\&) | Una referencia a la anotación a la que esta anotación está "en respuesta a". Ambas anotaciones deben estar en la misma página del documento. |
| [set_Opacity](./set_opacity/)(double) | Establece el valor constante de opacidad que se utilizará al dibujar la anotación. |
| [set_Popup](./set_popup/)(const System::SharedPtr\<PopupAnnotation\>\&) | Anotación emergente para ingresar o editar el texto asociado a esta anotación. |
| [set_ReplyType](./set_replytype/)(Aspose::Pdf::Annotations::ReplyType) | Una cadena que especifica la relación (el "tipo de respuesta") entre esta anotación y la especificada por InReplyTo. |
| [set_RichText](./set_richtext/)(const System::String\&) | Establece una cadena de texto enriquecido que se mostrará en la ventana emergente cuando se abra la anotación. |
| [set_Subject](./set_subject/)(const System::String\&) | Obtiene el texto que representa la descripción del objeto. |
| [set_Title](./set_title/)(System::String) override | Establece una etiqueta de texto que se mostrará en la barra de título de la ventana emergente de la anotación cuando esté abierta y activa. Esta entrada debe identificar al usuario que agregó la anotación. |
| [SetMarkedState](./setmarkedstate/)(bool) | Establece los estados Marcado y No Marcado para la anotación. [Note](../../aspose.pdf/note/), el estado almacenado en otra anotación de texto que tiene claves state y statemodel. |
| [SetReviewState](./setreviewstate/)(AnnotationState, const System::String\&) | Establece el estado de revisión para una anotación. Los estados Marcado y No Marcado se ignoran ya que no pertenecen al Review StateModel. [Note](../../aspose.pdf/note/), el estado almacenado en otra anotación de texto que tiene claves state y statemodel. |
| [SetReviewState](./setreviewstate/)(AnnotationState) | Establece el estado de revisión para una anotación. Los estados Marcado y No Marcado se ignoran ya que no pertenecen al Review StateModel. El estado lo establece el usuario que creó la anotación de destino. El valor se toma de la propiedad Title de la anotación de destino. [Note](../../aspose.pdf/note/), el estado almacenado en otra anotación de texto que tiene claves state y statemodel. |
## Ver también

* Class [Annotation](../annotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
