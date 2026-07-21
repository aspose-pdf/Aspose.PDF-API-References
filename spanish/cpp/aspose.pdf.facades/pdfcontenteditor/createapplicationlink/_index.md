---
title: "Aspose::Pdf::Facades::PdfContentEditor::CreateApplicationLink método"
linktitle: "CreateApplicationLink"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfContentEditor::CreateApplicationLink método. Crea un enlace para lanzar una aplicación en un documento PDF en C++."
type: docs
weight: 700
url: /es/cpp/aspose.pdf.facades/pdfcontenteditor/createapplicationlink/
---
## PdfContentEditor::CreateApplicationLink(System::Drawing::Rectangle, const System::String\&, int32_t) method


Crea un enlace para lanzar una aplicación en el documento PDF.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateApplicationLink(System::Drawing::Rectangle rect, const System::String &application, int32_t page)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | El rectángulo para clic activo. |
| application | const System::String\& | La ruta de la aplicación que se lanzará. |
| página | int32_t | El número de la página original donde se creará el rectángulo vinculado con el enlace. |

## Ver también

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreateApplicationLink(System::Drawing::Rectangle, const System::String\&, int32_t, System::Drawing::Color) method


Crea un enlace para lanzar una aplicación en el documento PDF.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateApplicationLink(System::Drawing::Rectangle rect, const System::String &application, int32_t page, System::Drawing::Color clr)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | El rectángulo para clic activo. |
| application | const System::String\& | La ruta de la aplicación que se lanzará. |
| página | int32_t | El número de la página original donde se creará el rectángulo vinculado con el enlace. |
| clr | System::Drawing::Color | El color del rectángulo para clic activo. |

## Ver también

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreateApplicationLink(System::Drawing::Rectangle, const System::String\&, int32_t, System::Drawing::Color, const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\&) method


Crea un enlace para lanzar una aplicación en el documento PDF.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateApplicationLink(System::Drawing::Rectangle rect, const System::String &application, int32_t page, System::Drawing::Color clr, const System::ArrayPtr<System::SharedPtr<System::BoxedValueBase>> &actionName)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | El rectángulo para clic activo. |
| application | const System::String\& | La ruta de la aplicación que se lanzará. |
| página | int32_t | El número de la página original donde se creará el rectángulo vinculado con el enlace. |
| clr | System::Drawing::Color | El color del rectángulo para clic activo. |
| actionName | const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\& | La matriz de acciones (miembros del enum PredefinedAction) correspondiente a la ejecución de elementos del menú en el visor Acrobat. |
## Observaciones



///
## Ver también

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [BoxedValueBase](../../../system/boxedvaluebase/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
