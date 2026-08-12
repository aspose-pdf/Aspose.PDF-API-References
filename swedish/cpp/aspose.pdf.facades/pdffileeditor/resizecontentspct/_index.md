---
title: "Aspose::Pdf::Facades::PdfFileEditor::ResizeContentsPct‑metod"
linktitle: "ResizeContentsPct"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileEditor::ResizeContentsPct‑metod. Ändrar storlek på innehållet i dokumentets sidor. Krymper sidans innehåll och lägger till marginaler. Ny storlek på innehållet anges i procent i C++."
type: docs
weight: 3600
url: /sv/cpp/aspose.pdf.facades/pdffileeditor/resizecontentspct/
---
## PdfFileEditor::ResizeContentsPct(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, double, double) method


Ändrar storlek på innehållet i dokumentets sidor. Krymper innehållet på sidan och lägger till marginaler. Ny storlek på innehållet anges i procent.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::ResizeContentsPct(const System::SharedPtr<System::IO::Stream> &source, const System::SharedPtr<System::IO::Stream> &destination, const System::ArrayPtr<int32_t> &pages, double newWidth, double newHeight)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | const System::SharedPtr\<System::IO::Stream\>\& | Ström som innehåller källdokumentet. |
| destination | const System::SharedPtr\<System::IO::Stream\>\& | Ström där det resulterande dokumentet kommer att sparas. |
| sidor | const System::ArrayPtr\<int32_t\>\& | Array av sidindex. Om null bearbetas alla dokumentets sidor. |
| newWidth | double | Ny bredd på sidinnehållet i procent. |
| newHeight | double | Ny höjd på sidinnehållet i procent. |

### ReturnValue

true om storleken ändrades framgångsrikt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::ResizeContentsPct(const System::String\&, const System::String\&, const System::ArrayPtr\<int32_t\>\&, double, double) method


Ändrar storlek på innehållet i dokumentets sidor. Krymper innehållet på sidan och lägger till marginaler. Ny storlek på innehållet anges i procent.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::ResizeContentsPct(const System::String &source, const System::String &destination, const System::ArrayPtr<int32_t> &pages, double newWidth, double newHeight)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | const System::String\& | Sökväg till källdokumentet. |
| destination | const System::String\& | Sökväg där det resulterande dokumentet kommer att sparas. |
| sidor | const System::ArrayPtr\<int32_t\>\& | Array av sidindex. Om null bearbetas alla dokumentets sidor. |
| newWidth | double | Ny bredd på sidinnehållet i procent. |
| newHeight | double | Ny höjd på sidinnehållet i procent. |

### ReturnValue

true om storleksändringen lyckades.

## Se även

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
