---
title: "Aspose::Pdf::Facades::PdfContentEditor::CreateRubberStamp método"
linktitle: "CreateRubberStamp"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfContentEditor::CreateRubberStamp método. Crea una anotación de sello de goma en C++."
type: docs
weight: 2200
url: /es/cpp/aspose.pdf.facades/pdfcontenteditor/createrubberstamp/
---
## PdfContentEditor::CreateRubberStamp(int32_t, System::Drawing::Rectangle, const System::String\&, System::Drawing::Color, const System::SharedPtr\<System::IO::Stream\>\&) method


Crea una anotación de sello de goma.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateRubberStamp(int32_t page, System::Drawing::Rectangle annotRect, const System::String &annotContents, System::Drawing::Color color, const System::SharedPtr<System::IO::Stream> &appearanceStream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| página | int32_t | El número de la página original donde se creará la anotación. |
| annotRect | System::Drawing::Rectangle | El rectángulo de anotación que define la ubicación de la anotación en la página. |
| annotContents | const System::String\& | El contenido de la anotación. |
| color | System::Drawing::Color | El color de la anotación. |
| appearanceStream | const System::SharedPtr\<System::IO::Stream\>\& | El flujo del archivo de apariencia. |

## Ver también

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreateRubberStamp(int32_t, System::Drawing::Rectangle, const System::String\&, System::Drawing::Color, const System::String\&) method


Crea una anotación de sello de goma.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateRubberStamp(int32_t page, System::Drawing::Rectangle annotRect, const System::String &annotContents, System::Drawing::Color color, const System::String &appearanceFile)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| página | int32_t | El número de la página original donde se creará la anotación. |
| annotRect | System::Drawing::Rectangle | El rectángulo de anotación que define la ubicación de la anotación en la página. |
| annotContents | const System::String\& | El contenido de la anotación. |
| color | System::Drawing::Color | El color de la anotación. |
| appearanceFile | const System::String\& | La ruta del archivo de apariencia. |

## Ver también

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreateRubberStamp(int32_t, System::Drawing::Rectangle, const System::String\&, const System::String\&, System::Drawing::Color) method


Crea una anotación de sello de goma.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateRubberStamp(int32_t page, System::Drawing::Rectangle annotRect, const System::String &icon, const System::String &annotContents, System::Drawing::Color color)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| página | int32_t | El número de la página original donde se creará la anotación. |
| annotRect | System::Drawing::Rectangle | El rectángulo de anotación que define la ubicación de la anotación en la página. |
| icon | const System::String\& | Se usará un icono para mostrar la anotación. Valor predeterminado: 'Draft'. |
| annotContents | const System::String\& | El contenido de la anotación. |
| color | System::Drawing::Color | El color de la anotación. |

## Ver también

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
