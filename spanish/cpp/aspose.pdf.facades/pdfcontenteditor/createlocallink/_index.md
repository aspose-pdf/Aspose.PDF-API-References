---
title: "Aspose::Pdf::Facades::PdfContentEditor::CreateLocalLink método"
linktitle: "CreateLocalLink"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfContentEditor::CreateLocalLink método. Crea un enlace local en un documento PDF en C++."
type: docs
weight: 1500
url: /es/cpp/aspose.pdf.facades/pdfcontenteditor/createlocallink/
---
## PdfContentEditor::CreateLocalLink(System::Drawing::Rectangle, int32_t, int32_t) method


Crea un enlace local en el documento PDF.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateLocalLink(System::Drawing::Rectangle rect, int32_t desPage, int32_t originalPage)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | El rectángulo para clic activo. |
| desPage | int32_t | La página de destino. |
| originalPage | int32_t | El número de la página original donde se creará el rectángulo vinculado con el enlace local. |

## Ver también

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreateLocalLink(System::Drawing::Rectangle, int32_t, int32_t, System::Drawing::Color) method


Crea un enlace local en el documento PDF.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateLocalLink(System::Drawing::Rectangle rect, int32_t desPage, int32_t originalPage, System::Drawing::Color clr)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | El rectángulo para clic activo. |
| desPage | int32_t | La página de destino. |
| originalPage | int32_t | El número de la página original donde se creará el rectángulo vinculado con el enlace local. |
| clr | System::Drawing::Color | El color del rectángulo para clic activo. |

## Ver también

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [Color](../../../system.drawing/color/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreateLocalLink(System::Drawing::Rectangle, int32_t, int32_t, System::Drawing::Color, const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\&) method


Crea un enlace local en el documento PDF.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateLocalLink(System::Drawing::Rectangle rect, int32_t desPage, int32_t originalPage, System::Drawing::Color clr, const System::ArrayPtr<System::SharedPtr<System::BoxedValueBase>> &actionName)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | El rectángulo para clic activo. |
| desPage | int32_t | La página de destino. |
| originalPage | int32_t | El número de la página original donde se creará el rectángulo vinculado con el enlace local. |
| clr | System::Drawing::Color | El color del rectángulo para clic activo. |
| actionName | const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\& | La matriz de acciones (miembros del enum PredefinedAction) correspondiente a la ejecución de elementos del menú en el visor Acrobat. |

## Ver también

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [Color](../../../system.drawing/color/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [BoxedValueBase](../../../system/boxedvaluebase/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
