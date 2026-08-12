---
title: "Aspose::Pdf::Facades::PdfContentEditor::CreatePdfDocumentLink método"
linktitle: "CreatePdfDocumentLink"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfContentEditor::CreatePdfDocumentLink método. Crea un enlace a otra página de documento PDF en C++."
type: docs
weight: 1800
url: /es/cpp/aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/
---
## PdfContentEditor::CreatePdfDocumentLink(System::Drawing::Rectangle, const System::String\&, int32_t, int32_t) method


Crea un enlace a otra página de documento PDF.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreatePdfDocumentLink(System::Drawing::Rectangle rect, const System::String &remotePdf, int32_t originalPage, int32_t destinationPage)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | El rectángulo para clic activo. |
| remotePdf | const System::String\& | El documento PDF cuya página se abrirá. |
| originalPage | int32_t | El número de la página original donde se creará el rectángulo vinculado con el enlace. |
| destinationPage | int32_t | La página de destino. |

## Ver también

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreatePdfDocumentLink(System::Drawing::Rectangle, const System::String\&, int32_t, int32_t, System::Drawing::Color) method


Crea un enlace a otra página de documento PDF.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreatePdfDocumentLink(System::Drawing::Rectangle rect, const System::String &remotePdf, int32_t originalPage, int32_t destinationPage, System::Drawing::Color clr)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | El rectángulo para clic activo. |
| remotePdf | const System::String\& | El documento PDF cuya página se abrirá. |
| originalPage | int32_t | El número de la página original donde se creará el rectángulo vinculado con el enlace. |
| destinationPage | int32_t | La página de destino. |
| clr | System::Drawing::Color | El color del rectángulo para clic activo. |

## Ver también

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreatePdfDocumentLink(System::Drawing::Rectangle, const System::String\&, int32_t, int32_t, System::Drawing::Color, const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\&) method


Crea un enlace a otra página de documento PDF.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreatePdfDocumentLink(System::Drawing::Rectangle rect, const System::String &remotePdf, int32_t originalPage, int32_t destinationPage, System::Drawing::Color clr, const System::ArrayPtr<System::SharedPtr<System::BoxedValueBase>> &actionName)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | El rectángulo para clic activo. |
| remotePdf | const System::String\& | El documento PDF cuya página se abrirá. |
| originalPage | int32_t | El número de la página original donde se creará el rectángulo vinculado con el enlace. |
| destinationPage | int32_t | La página de destino. |
| clr | System::Drawing::Color | El color del rectángulo para clic activo. |
| actionName | const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\& | La matriz de acciones (miembros del enum PredefinedAction) correspondiente a la ejecución de elementos del menú en el visor Acrobat. |

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
