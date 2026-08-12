---
title: "Aspose::Pdf::Facades::PdfContentEditor::CreateRubberStamp metod"
linktitle: "CreateRubberStamp"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfContentEditor::CreateRubberStamp metod. Skapar en gummistämpelannotation i C++."
type: docs
weight: 2200
url: /sv/cpp/aspose.pdf.facades/pdfcontenteditor/createrubberstamp/
---
## PdfContentEditor::CreateRubberStamp(int32_t, System::Drawing::Rectangle, const System::String\&, System::Drawing::Color, const System::SharedPtr\<System::IO::Stream\>\&) method


Skapar en gummistämpelanteckning.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateRubberStamp(int32_t page, System::Drawing::Rectangle annotRect, const System::String &annotContents, System::Drawing::Color color, const System::SharedPtr<System::IO::Stream> &appearanceStream)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | int32_t | Numret på den ursprungliga sidan där annotationen kommer att skapas. |
| annotRect | System::Drawing::Rectangle | Annotationsrektangeln som definierar placeringen av anmärkningen på sidan. |
| annotContents | const System::String\& | Innehållet i annotationen. |
| färg | System::Drawing::Color | Färgen på annotationen. |
| appearanceStream | const System::SharedPtr\<System::IO::Stream\>\& | Strömmen för utseendefilen. |

## Se även

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreateRubberStamp(int32_t, System::Drawing::Rectangle, const System::String\&, System::Drawing::Color, const System::String\&) method


Skapar en gummistämpelanteckning.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateRubberStamp(int32_t page, System::Drawing::Rectangle annotRect, const System::String &annotContents, System::Drawing::Color color, const System::String &appearanceFile)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | int32_t | Numret på den ursprungliga sidan där annotationen kommer att skapas. |
| annotRect | System::Drawing::Rectangle | Annotationsrektangeln som definierar placeringen av anmärkningen på sidan. |
| annotContents | const System::String\& | Innehållet i annotationen. |
| färg | System::Drawing::Color | Färgen på annotationen. |
| appearanceFile | const System::String\& | Sökvägen till utseendefilen. |

## Se även

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreateRubberStamp(int32_t, System::Drawing::Rectangle, const System::String\&, const System::String\&, System::Drawing::Color) method


Skapar en gummistämpelanteckning.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateRubberStamp(int32_t page, System::Drawing::Rectangle annotRect, const System::String &icon, const System::String &annotContents, System::Drawing::Color color)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | int32_t | Numret på den ursprungliga sidan där annotationen kommer att skapas. |
| annotRect | System::Drawing::Rectangle | Annotationsrektangeln som definierar placeringen av anmärkningen på sidan. |
| icon | const System::String\& | En ikon ska användas vid visning av annotationen. Standardvärde: 'Draft'. |
| annotContents | const System::String\& | Innehållet i annotationen. |
| färg | System::Drawing::Color | Färgen på annotationen. |

## Se även

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
