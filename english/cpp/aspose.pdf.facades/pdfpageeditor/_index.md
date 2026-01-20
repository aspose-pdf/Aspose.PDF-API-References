---
title: Aspose::Pdf::Facades::PdfPageEditor class
linktitle: PdfPageEditor
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfPageEditor class. Represents a class to edit the PDF file''s page, including rotating page, zooming page, moving position and changing page size in C++.'
type: docs
weight: 2800
url: /cpp/aspose.pdf.facades/pdfpageeditor/
---
## PdfPageEditor class


Represents a class to edit the PDF file's page, including rotating page, zooming page, moving position and changing page size.

```cpp
class PdfPageEditor : public Aspose::Pdf::Facades::SaveableFacade
```

## Methods

| Method | Description |
| --- | --- |
| [ApplyChanges](./applychanges/)() | Apply changes made to the document pages. |
| [get_DisplayDuration](./get_displayduration/)() | Gets display duration for pages. |
| [get_HorizontalAlignment](./get_horizontalalignment/)() | Gets the horizontal alignment of the original PDF content on the result page, default is AlignmentType.Left. |
| [get_PageRotations](./get_pagerotations/)() | A hashtable contains the page number and rotation degree, the key represents the page number, the value of key represents the rotation in degrees. |
| [get_PageSize](./get_pagesize/)() | Gets the output file's page size. |
| [get_ProcessPages](./get_processpages/)() | Gets the page numbers to be edited. By default, each page would be edited. |
| [get_Rotation](./get_rotation/)() | Gets the rotation of the pages, the rotation must be 0, 90, 180 or 270. Default value is 0. |
| [get_TransitionDuration](./get_transitionduration/)() | Gets duration of the transition effect. |
| [get_TransitionType](./get_transitiontype/)() | Gets transition style to use when moving to this page from another during a presentation. |
| [get_VerticalAlignmentType](./get_verticalalignmenttype/)() | Gets or Sets the vertical alignment of the original PDF content on the result page, default is VerticalAlignmentType.Bottom. |
| [get_Zoom](./get_zoom/)() | Get or sets zoom coefficient. Value 1.0 corresponds to 100%. Default value is 1.0. |
| [GetPageBoxSize](./getpageboxsize/)(int32_t, System::String) | Returns size of specified box in document. |
| [GetPageRotation](./getpagerotation/)(int32_t) | Returns the rotation of specified page. |
| [GetPages](./getpages/)() | Returns total number of pages. |
| [GetPageSize](./getpagesize/)(int32_t) | Returns the page size of the specified page. |
| [MovePosition](./moveposition/)(float, float) | Moves the origin from (0, 0) to the point that appointted. The origin is left-bottom and the unit is point(1 inch = 72 points). |
| [PdfPageEditor](./pdfpageeditor/)() | Constructor for [PdfPageEditor](./) class. |
| [PdfPageEditor](./pdfpageeditor/)(System::SharedPtr\<Aspose::Pdf::Document\>) | Constructor for [PdfPageEditor](./) class. |
| [Save](./save/)(System::String) override | Saves changed document into file. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>) override | Saves changed document into stream. |
| [set_DisplayDuration](./set_displayduration/)(int32_t) | Sets display duration for pages. |
| [set_HorizontalAlignment](./set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) | Sets the horizontal alignment of the original PDF content on the result page, default is AlignmentType.Left. |
| [set_PageRotations](./set_pagerotations/)(System::SharedPtr\<System::Collections::Generic::Dictionary\<int32_t, int32_t\>\>) | A hashtable contains the page number and rotation degree, the key represents the page number, the value of key represents the rotation in degrees. |
| [set_PageSize](./set_pagesize/)(System::SharedPtr\<Aspose::Pdf::PageSize\>) | Sets the output file's page size. |
| [set_ProcessPages](./set_processpages/)(System::ArrayPtr\<int32_t\>) | Sets the page numbers to be edited. By default, each page would be edited. |
| [set_Rotation](./set_rotation/)(int32_t) | Sets the rotation of the pages, the rotation must be 0, 90, 180 or 270. Default value is 0. |
| [set_TransitionDuration](./set_transitionduration/)(int32_t) | Sets duration of the transition effect. |
| [set_TransitionType](./set_transitiontype/)(int32_t) | Sets transition style to use when moving to this page from another during a presentation. |
| [set_VerticalAlignmentType](./set_verticalalignmenttype/)(Aspose::Pdf::VerticalAlignment) | Gets or Sets the vertical alignment of the original PDF content on the result page, default is VerticalAlignmentType.Bottom. |
| [set_Zoom](./set_zoom/)(float) | Get or sets zoom coefficient. Value 1.0 corresponds to 100%. Default value is 1.0. |
## Fields

| Field | Description |
| --- | --- |
| static constexpr [BLINDH](./blindh/) | Vertical Blinds. |
| static constexpr [BLINDV](./blindv/) | Vertical Blinds. |
| static constexpr [BTWIPE](./btwipe/) | Bottom-Top Wipe. |
| static constexpr [DGLITTER](./dglitter/) | Diagonal Glitter. |
| static constexpr [DISSOLVE](./dissolve/) | The old page dissolves. |
| static constexpr [INBOX](./inbox/) | Inward Box. |
| static constexpr [LRGLITTER](./lrglitter/) | Left-Right Glitter. |
| static constexpr [LRWIPE](./lrwipe/) | Left-Right Wipe. |
| static constexpr [OUTBOX](./outbox/) | Outward Box. |
| static constexpr [RLWIPE](./rlwipe/) | Right-Left Wipe. |
| static constexpr [SPLITHIN](./splithin/) | IN Horizontal Split. |
| static constexpr [SPLITHOUT](./splithout/) | Out Horizontal Split. |
| static constexpr [SPLITVIN](./splitvin/) | In Vertical Split. |
| static constexpr [SPLITVOUT](./splitvout/) | Out Vertical Split. |
| static constexpr [TBGLITTER](./tbglitter/) | Top-Bottom Glitter. |
| static constexpr [TBWIPE](./tbwipe/) | Top-Bottom Wipe. |
## See Also

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
