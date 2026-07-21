---
title: "Aspose::Pdf::Annotations::MarkupAnnotation::SetReviewState método"
linktitle: "SetReviewState"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::MarkupAnnotation::SetReviewState método. Establece el estado de revisión para una anotación. Los estados Marcado y No Marcado se ignoran ya que no pertenecen al Review StateModel. El estado lo establece el usuario que creó la anotación objetivo. El valor se toma de la propiedad Title de la anotación objetivo. Nota, el estado almacenado en otra anotación de texto que tiene claves state y statemodel en C++."
type: docs
weight: 2200
url: /es/cpp/aspose.pdf.annotations/markupannotation/setreviewstate/
---
## MarkupAnnotation::SetReviewState(AnnotationState) method


Establece el estado de revisión para una anotación. Los estados Marcado y No Marcado se ignoran ya que no pertenecen al Review StateModel. El estado lo establece el usuario que creó la anotación objetivo. El valor se toma de la propiedad Title de la anotación objetivo. [Note](../../../aspose.pdf/note/), el estado almacenado en otra anotación de texto que tiene claves state y statemodel.

```cpp
void Aspose::Pdf::Annotations::MarkupAnnotation::SetReviewState(AnnotationState state)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| state | AnnotationState | Estado para asignación. |

## Ver también

* Enum [AnnotationState](../../annotationstate/)
* Class [MarkupAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## MarkupAnnotation::SetReviewState(AnnotationState, const System::String\&) method


Establece el estado de revisión para una anotación. Los estados Marcado y No Marcado se ignoran ya que no pertenecen al Review StateModel. [Note](../../../aspose.pdf/note/), el estado almacenado en otra anotación de texto que tiene claves state y statemodel.

```cpp
void Aspose::Pdf::Annotations::MarkupAnnotation::SetReviewState(AnnotationState state, const System::String &userName)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| state | AnnotationState | Estado para asignación. |
| userName | const System::String\& | El nombre de usuario que aparece en el encabezado de los comentarios. El nombre puede ser el mismo que el nombre en la Title de la anotación objetivo o diferente si el estado es establecido por otro usuario. |

## Ver también

* Enum [AnnotationState](../../annotationstate/)
* Class [String](../../../system/string/)
* Class [MarkupAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
