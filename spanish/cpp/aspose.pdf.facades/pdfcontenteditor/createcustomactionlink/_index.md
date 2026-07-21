---
title: "Método Aspose::Pdf::Facades::PdfContentEditor::CreateCustomActionLink"
linktitle: "CreateCustomActionLink"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método Aspose::Pdf::Facades::PdfContentEditor::CreateCustomActionLink. Crea un enlace a acciones personalizadas en un documento PDF en C++."
type: docs
weight: 1000
url: /es/cpp/aspose.pdf.facades/pdfcontenteditor/createcustomactionlink/
---
## PdfContentEditor::CreateCustomActionLink method


Crea un enlace a acciones personalizadas en el documento PDF.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateCustomActionLink(System::Drawing::Rectangle rect, int32_t originalPage, System::Drawing::Color color, const System::ArrayPtr<System::SharedPtr<System::BoxedValueBase>> &actionName)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | El rectángulo para clic activo. |
| originalPage | int32_t | El número de la página original donde se creará el rectángulo vinculado con el enlace. |
| color | System::Drawing::Color | El color del rectángulo para clic activo. |
| actionName | const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\& | La matriz de acciones (miembros del enum PredefinedAction) correspondiente a la ejecución de elementos del menú en el visor Acrobat. |
## Observaciones



///
## Ver también

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [Color](../../../system.drawing/color/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [BoxedValueBase](../../../system/boxedvaluebase/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
