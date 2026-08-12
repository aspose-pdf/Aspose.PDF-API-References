---
title: "Aspose::Pdf::Facades::Bookmark clase"
linktitle: "Bookmark"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::Bookmark clase. Representa un marcador en C++."
type: docs
weight: 300
url: /es/cpp/aspose.pdf.facades/bookmark/
---
## Bookmark class


Representa un marcador.

```cpp
class Bookmark : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Bookmark](./bookmark/)() | Inicializa una nueva instancia de la clase [Bookmark](./). |
| [get_Action](./get_action/)() const | Obtiene la acción vinculada al marcador. Si [PageNumber](../../aspose.pdf/pagenumber/) está presente, la acción no puede especificarse. El tipo de acción incluye: "GoTo", "GoToR", "Launch", "Named". |
| [get_BoldFlag](./get_boldflag/)() const | Obtiene la bandera de negrita del título del marcador. |
| [get_ChildItem](./get_childitem/)() | Obtiene los hijos del marcador. |
| [get_ChildItems](./get_childitems/)() const | Obtiene los hijos del marcador. |
| [get_Destination](./get_destination/)() const | Obtiene la página de destino del marcador. Requerido si la acción se establece como string.Empty. |
| [get_ItalicFlag](./get_italicflag/)() const | Obtiene la marca de cursiva del título del marcador. |
| [get_Level](./get_level/)() const | Obtiene el nivel jerárquico del marcador. |
| [get_Open](./get_open/)() const | Obtiene el estado del marcador (abierto, cerrado). |
| [get_PageDisplay](./get_pagedisplay/)() const | Obtiene el tipo de visualización de la página de destino del marcador. |
| [get_PageDisplay_Bottom](./get_pagedisplay_bottom/)() const | Obtiene la coordenada inferior de la visualización de la página. |
| [get_PageDisplay_Left](./get_pagedisplay_left/)() const | Obtiene la coordenada izquierda de la visualización de la página. |
| [get_PageDisplay_Right](./get_pagedisplay_right/)() const | Obtiene la coordenada derecha de la visualización de la página. |
| [get_PageDisplay_Top](./get_pagedisplay_top/)() const | Obtiene la coordenada superior de la visualización de la página. |
| [get_PageDisplay_Zoom](./get_pagedisplay_zoom/)() const | Obtiene el factor de zoom de la visualización de la página. |
| [get_PageNumber](./get_pagenumber/)() const | Obtiene el número de la página de destino del marcador. |
| [get_RemoteFile](./get_remotefile/)() const | Obtiene el archivo (ruta) que se requiere para la acción "GoToR" del marcador. |
| [get_Title](./get_title/)() const | Obtiene el título del marcador. |
| [get_TitleColor](./get_titlecolor/)() const | Obtiene el color del título del marcador. |
| [set_Action](./set_action/)(const System::String\&) | Establece la acción vinculada al marcador. Si [PageNumber](../../aspose.pdf/pagenumber/) está presente, la acción no puede especificarse. El tipo de acción incluye: "GoTo", "GoToR", "Launch", "Named". |
| [set_BoldFlag](./set_boldflag/)(bool) | Establece la marca de negrita del título del marcador. |
| [set_ChildItem](./set_childitem/)(const System::SharedPtr\<Bookmarks\>\&) | Establece los hijos del marcador. |
| [set_ChildItems](./set_childitems/)(const System::SharedPtr\<Bookmarks\>\&) | Establece los hijos del marcador. |
| [set_Destination](./set_destination/)(const System::String\&) | Establece la página de destino del marcador. Requerido si la acción se establece como string.Empty. |
| [set_ItalicFlag](./set_italicflag/)(bool) | Establece la marca de cursiva del título del marcador. |
| [set_Level](./set_level/)(int32_t) | Establece el nivel jerárquico del marcador. |
| [set_Open](./set_open/)(bool) | Establece el estado del marcador (abierto, cerrado). |
| [set_PageDisplay](./set_pagedisplay/)(const System::String\&) | Establece el tipo de visualización de la página de destino del marcador. |
| [set_PageDisplay_Bottom](./set_pagedisplay_bottom/)(int32_t) | Establece la coordenada inferior de la visualización de la página. |
| [set_PageDisplay_Left](./set_pagedisplay_left/)(int32_t) | Establece la coordenada izquierda de la visualización de la página. |
| [set_PageDisplay_Right](./set_pagedisplay_right/)(int32_t) | Establece la coordenada derecha de la visualización de la página. |
| [set_PageDisplay_Top](./set_pagedisplay_top/)(int32_t) | Establece la coordenada superior de la visualización de la página. |
| [set_PageDisplay_Zoom](./set_pagedisplay_zoom/)(int32_t) | Establece el factor de zoom de la visualización de la página. |
| [set_PageNumber](./set_pagenumber/)(int32_t) | Establece el número de página de destino del marcador. |
| [set_RemoteFile](./set_remotefile/)(const System::String\&) | Establece el archivo (ruta) que se requiere para la acción "GoToR" del marcador. |
| [set_Title](./set_title/)(const System::String\&) | Establece el título del marcador. |
| [set_TitleColor](./set_titlecolor/)(System::Drawing::Color) | Establece el color del título del marcador. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
