---
title: "Aspose::Pdf::Facades::PdfFileEditor::AddMarginsPct-metod"
linktitle: "AddMarginsPct"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileEditor::AddMarginsPct-metod. Ändrar storlek på sidinnehållet och lägger till angivna marginaler. Marginalerna anges i procent av den ursprungliga sidstorleken i C++."
type: docs
weight: 300
url: /sv/cpp/aspose.pdf.facades/pdffileeditor/addmarginspct/
---
## PdfFileEditor::AddMarginsPct(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, double, double, double, double) method


Ändrar storlek på sidinnehållet och lägger till specificerade marginaler. Marginalerna anges i procent av den ursprungliga sidstorleken.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::AddMarginsPct(const System::SharedPtr<System::IO::Stream> &source, const System::SharedPtr<System::IO::Stream> &destination, const System::ArrayPtr<int32_t> &pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | const System::SharedPtr\<System::IO::Stream\>\& | Ström som innehåller källdokumentet. |
| destination | const System::SharedPtr\<System::IO::Stream\>\& | Ström där det resulterande dokumentet kommer att sparas. |
| sidor | const System::ArrayPtr\<int32_t\>\& | Array av sidindex. Om null bearbetas alla dokumentets sidor. |
| leftMargin | double | [Left](../../../aspose.pdf/left/) marginal i procent av ursprunglig sidstorlek. |
| rightMargin | double | [Right](../../../aspose.pdf/right/) marginal i procent av ursprunglig sidstorlek. |
| topMargin | double | Övre marginal i procent av ursprunglig sidstorlek. |
| bottomMargin | double | Nedre marginal i procent av ursprunglig sidstorlek. |

### ReturnValue

true om åtgärden utfördes framgångsrikt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::AddMarginsPct(const System::String\&, const System::String\&, const System::ArrayPtr\<int32_t\>\&, double, double, double, double) method


Ändrar storlek på sidinnehållet och lägger till specificerade marginaler. Marginalerna anges i procent av den ursprungliga sidstorleken.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::AddMarginsPct(const System::String &source, const System::String &destination, const System::ArrayPtr<int32_t> &pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | const System::String\& | Sökväg till källdokumentet. |
| destination | const System::String\& | Sökväg där det resulterande dokumentet kommer att sparas. |
| sidor | const System::ArrayPtr\<int32_t\>\& | Array av sidindex. Om null bearbetas alla dokumentets sidor. |
| leftMargin | double | [Left](../../../aspose.pdf/left/) marginal i procent av ursprunglig sidstorlek. |
| rightMargin | double | [Right](../../../aspose.pdf/right/) marginal i procent av ursprunglig sidstorlek. |
| topMargin | double | Övre marginal i procent av ursprunglig sidstorlek. |
| bottomMargin | double | Nedre marginal i procent av ursprunglig sidstorlek. |

### ReturnValue

true om storleksändring lyckades

## Se även

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
