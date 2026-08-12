---
title: "Aspose::Pdf::Facades::PdfFileEditor::AddMargins-metod"
linktitle: "AddMargins"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileEditor::AddMargins-metod. Ändrar storlek på sidinnehållet och lägger till angivna marginaler. Marginalerna anges i standardenhetsmått i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.pdf.facades/pdffileeditor/addmargins/
---
## PdfFileEditor::AddMargins(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, double, double, double, double) method


Ändrar storlek på sidinnehållet och lägger till angivna marginaler. Marginalerna anges i standardenhetsmått.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::AddMargins(const System::SharedPtr<System::IO::Stream> &source, const System::SharedPtr<System::IO::Stream> &destination, const System::ArrayPtr<int32_t> &pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | const System::SharedPtr\<System::IO::Stream\>\& | Ström som innehåller källdokumentet. |
| destination | const System::SharedPtr\<System::IO::Stream\>\& | Ström där det resulterande dokumentet kommer att sparas. |
| sidor | const System::ArrayPtr\<int32_t\>\& | Array av sidindex. Om null bearbetas alla dokumentets sidor. |
| leftMargin | double | [Vänster](../../../aspose.pdf/left/) marginal. |
| rightMargin | double | [Höger](../../../aspose.pdf/right/) marginal. |
| topMargin | double | Övre marginal. |
| bottomMargin | double | Nedre marginal. |

### ReturnValue

true om operationen lyckades.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::AddMargins(const System::String\&, const System::String\&, const System::ArrayPtr\<int32_t\>\&, double, double, double, double) method


Ändrar storlek på sidinnehållet och lägger till angivna marginaler. Marginalerna anges i standardenhetsmått.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::AddMargins(const System::String &source, const System::String &destination, const System::ArrayPtr<int32_t> &pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | const System::String\& | Sökväg till källdokumentet. |
| destination | const System::String\& | Sökväg där det resulterande dokumentet kommer att sparas. |
| sidor | const System::ArrayPtr\<int32_t\>\& | Array av sidindex. Om null bearbetas alla dokumentets sidor. |
| leftMargin | double | [Vänster](../../../aspose.pdf/left/) marginal. |
| rightMargin | double | [Höger](../../../aspose.pdf/right/) marginal. |
| topMargin | double | Övre marginal. |
| bottomMargin | double | Nedre marginal. |

### ReturnValue

true om storleksändringen lyckades.

## Se även

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
