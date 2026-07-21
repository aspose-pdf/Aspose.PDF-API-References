---
title: "Clase Aspose::Pdf::Facades::PdfPageEditor"
linktitle: "PdfPageEditor"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Facades::PdfPageEditor. Representa una clase para editar la página del archivo PDF, incluyendo rotar la página, hacer zoom, mover la posición y cambiar el tamaño de la página en C++."
type: docs
weight: 2800
url: /es/cpp/aspose.pdf.facades/pdfpageeditor/
---
## PdfPageEditor class


Representa una clase para editar la página del archivo PDF, incluyendo rotar la página, hacer zoom, mover la posición y cambiar el tamaño de la página.

```cpp
class PdfPageEditor : public Aspose::Pdf::Facades::SaveableFacade
```

## Métodos

| Método | Descripción |
| --- | --- |
| [ApplyChanges](./applychanges/)() | Aplica los cambios realizados en las páginas del documento. |
| [get_DisplayDuration](./get_displayduration/)() | Obtiene la duración de visualización de las páginas. |
| [get_HorizontalAlignment](./get_horizontalalignment/)() | Obtiene la alineación horizontal del contenido PDF original en la página resultante, el valor predeterminado es AlignmentType.Left. |
| [get_PageRotations](./get_pagerotations/)() | Una tabla hash contiene el número de página y el grado de rotación; la clave representa el número de página y el valor de la clave representa la rotación en grados. |
| [get_PageSize](./get_pagesize/)() | Obtiene el tamaño de página del archivo de salida. |
| [get_ProcessPages](./get_processpages/)() | Obtiene los números de página que se editarán. Por defecto, se editará cada página. |
| [get_Rotation](./get_rotation/)() | Obtiene la rotación de las páginas; la rotación debe ser 0, 90, 180 o 270. El valor predeterminado es 0. |
| [get_TransitionDuration](./get_transitionduration/)() | Obtiene la duración del efecto de transición. |
| [get_TransitionType](./get_transitiontype/)() | Obtiene el estilo de transición a usar al pasar a esta página desde otra durante una presentación. |
| [get_VerticalAlignmentType](./get_verticalalignmenttype/)() | Obtiene o establece la alineación vertical del contenido PDF original en la página resultante, el valor predeterminado es VerticalAlignmentType.Bottom. |
| [get_Zoom](./get_zoom/)() | Obtiene o establece el coeficiente de zoom. El valor 1.0 corresponde al 100 %. El valor predeterminado es 1.0. |
| [GetPageBoxSize](./getpageboxsize/)(int32_t, const System::String\&) | Devuelve el tamaño del cuadro especificado en el documento. |
| [GetPageRotation](./getpagerotation/)(int32_t) | Devuelve la rotación de la página especificada. |
| [GetPages](./getpages/)() | Devuelve el número total de páginas. |
| [GetPageSize](./getpagesize/)(int32_t) | Devuelve el tamaño de página de la página especificada. |
| [MovePosition](./moveposition/)(float, float) | Mueve el origen de (0, 0) al punto designado. El origen está en la esquina inferior izquierda y la unidad es punto (1 pulgada = 72 puntos). |
| [PdfPageEditor](./pdfpageeditor/)() | Constructor para la clase [PdfPageEditor](./). |
| [PdfPageEditor](./pdfpageeditor/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Constructor para la clase [PdfPageEditor](./). |
| [Save](./save/)(System::String) override | Guarda el documento modificado en un archivo. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>) override | Guarda el documento modificado en un flujo. |
| [set_DisplayDuration](./set_displayduration/)(int32_t) | Establece la duración de visualización de las páginas. |
| [set_HorizontalAlignment](./set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) | Establece la alineación horizontal del contenido PDF original en la página resultante, el valor predeterminado es AlignmentType.Left. |
| [set_PageRotations](./set_pagerotations/)(const System::SharedPtr\<System::Collections::Generic::Dictionary\<int32_t, int32_t\>\>\&) | Una tabla hash contiene el número de página y el grado de rotación; la clave representa el número de página y el valor de la clave representa la rotación en grados. |
| [set_PageSize](./set_pagesize/)(const System::SharedPtr\<Aspose::Pdf::PageSize\>\&) | Establece el tamaño de página del archivo de salida. |
| [set_ProcessPages](./set_processpages/)(const System::ArrayPtr\<int32_t\>\&) | Establece los números de página que se editarán. Por defecto, se editará cada página. |
| [set_Rotation](./set_rotation/)(int32_t) | Establece la rotación de las páginas, la rotación debe ser 0, 90, 180 o 270. El valor predeterminado es 0. |
| [set_TransitionDuration](./set_transitionduration/)(int32_t) | Establece la duración del efecto de transición. |
| [set_TransitionType](./set_transitiontype/)(int32_t) | Establece el estilo de transición a usar al pasar a esta página desde otra durante una presentación. |
| [set_VerticalAlignmentType](./set_verticalalignmenttype/)(Aspose::Pdf::VerticalAlignment) | Obtiene o establece la alineación vertical del contenido PDF original en la página resultante, el valor predeterminado es VerticalAlignmentType.Bottom. |
| [set_Zoom](./set_zoom/)(float) | Obtiene o establece el coeficiente de zoom. El valor 1.0 corresponde al 100 %. El valor predeterminado es 1.0. |
## Campos

| Campo | Descripción |
| --- | --- |
| static constexpr [BLINDH](./blindh/) | Persianas verticales. |
| static constexpr [BLINDV](./blindv/) | Persianas verticales. |
| static constexpr [BTWIPE](./btwipe/) | Deslizamiento de abajo a arriba. |
| static constexpr [DGLITTER](./dglitter/) | Brillo diagonal. |
| static constexpr [DISSOLVE](./dissolve/) | La página anterior se disuelve. |
| static constexpr [INBOX](./inbox/) | Caja interna. |
| static constexpr [LRGLITTER](./lrglitter/) | Brillo izquierda-derecha. |
| static constexpr [LRWIPE](./lrwipe/) | Deslizamiento izquierda-derecha. |
| static constexpr [OUTBOX](./outbox/) | Caja externa. |
| static constexpr [RLWIPE](./rlwipe/) | Deslizamiento derecha-izquierda. |
| static constexpr [SPLITHIN](./splithin/) | División horizontal IN. |
| static constexpr [SPLITHOUT](./splithout/) | División horizontal Out. |
| static constexpr [SPLITVIN](./splitvin/) | División vertical In. |
| static constexpr [SPLITVOUT](./splitvout/) | División vertical Out. |
| static constexpr [TBGLITTER](./tbglitter/) | Brillo arriba-abajo. |
| static constexpr [TBWIPE](./tbwipe/) | Deslizamiento arriba-abajo. |
## Ver también

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
