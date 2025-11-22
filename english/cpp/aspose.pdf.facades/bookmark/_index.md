---
title: Aspose::Pdf::Facades::Bookmark class
linktitle: Bookmark
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::Bookmark class. Represents a bookmark in C++.'
type: docs
weight: 300
url: /cpp/aspose.pdf.facades/bookmark/
---
## Bookmark class


Represents a bookmark.

```cpp
class Bookmark : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Bookmark](./bookmark/)() | Initializes a new instance of the [Bookmark](./) class. |
| [get_Action](./get_action/)() const | Gets the action bound with the bookmark. If [PageNumber](../../aspose.pdf/pagenumber/) is presented the action can not be specified. The action type includes: "GoTo", "GoToR", "Launch", "Named". |
| [get_BoldFlag](./get_boldflag/)() const | Gets the bold flag of bookmark's title. |
| [get_ChildItem](./get_childitem/)() | Gets bookmark's children. |
| [get_ChildItems](./get_childitems/)() const | Gets bookmark's children. |
| [get_Destination](./get_destination/)() const | Gets bookmark's destination page. Required if action is set as string.Empty. |
| [get_ItalicFlag](./get_italicflag/)() const | Gets the italic flag of bookmark's title. |
| [get_Level](./get_level/)() const | Gets bookmark's hierarchy level. |
| [get_Open](./get_open/)() const | Gets bookmark state (open, close). |
| [get_PageDisplay](./get_pagedisplay/)() const | Gets the type of display bookmark's destination page. |
| [get_PageDisplay_Bottom](./get_pagedisplay_bottom/)() const | Gets the bottom coordinate of page display. |
| [get_PageDisplay_Left](./get_pagedisplay_left/)() const | Gets the left coordinate of page display. |
| [get_PageDisplay_Right](./get_pagedisplay_right/)() const | Gets the right coordinate of page display. |
| [get_PageDisplay_Top](./get_pagedisplay_top/)() const | Gets the top coordinate of page display. |
| [get_PageDisplay_Zoom](./get_pagedisplay_zoom/)() const | Gets the zoom factor of page display. |
| [get_PageNumber](./get_pagenumber/)() const | Gets the number of bookmark's destination page. |
| [get_RemoteFile](./get_remotefile/)() const | Gets the file (path) which is required for "GoToR" action of bookmark. |
| [get_Title](./get_title/)() const | Gets bookmark's title. |
| [get_TitleColor](./get_titlecolor/)() const | Gets the color of bookmark's title. |
| [set_Action](./set_action/)(System::String) | Sets the action bound with the bookmark. If [PageNumber](../../aspose.pdf/pagenumber/) is presented the action can not be specified. The action type includes: "GoTo", "GoToR", "Launch", "Named". |
| [set_BoldFlag](./set_boldflag/)(bool) | Sets the bold flag of bookmark's title. |
| [set_ChildItem](./set_childitem/)(System::SharedPtr\<Bookmarks\>) | Sets bookmark's children. |
| [set_ChildItems](./set_childitems/)(System::SharedPtr\<Bookmarks\>) | Sets bookmark's children. |
| [set_Destination](./set_destination/)(System::String) | Sets bookmark's destination page. Required if action is set as string.Empty. |
| [set_ItalicFlag](./set_italicflag/)(bool) | Sets the italic flag of bookmark's title. |
| [set_Level](./set_level/)(int32_t) | Sets bookmark's hierarchy level. |
| [set_Open](./set_open/)(bool) | Sets bookmark state (open, close). |
| [set_PageDisplay](./set_pagedisplay/)(System::String) | Sets the type of display bookmark's destination page. |
| [set_PageDisplay_Bottom](./set_pagedisplay_bottom/)(int32_t) | Sets the bottom coordinate of page display. |
| [set_PageDisplay_Left](./set_pagedisplay_left/)(int32_t) | Sets the left coordinate of page display. |
| [set_PageDisplay_Right](./set_pagedisplay_right/)(int32_t) | Sets the right coordinate of page display. |
| [set_PageDisplay_Top](./set_pagedisplay_top/)(int32_t) | Sets the top coordinate of page display. |
| [set_PageDisplay_Zoom](./set_pagedisplay_zoom/)(int32_t) | Sets the zoom factor of page display. |
| [set_PageNumber](./set_pagenumber/)(int32_t) | Sets the number of bookmark's destination page. |
| [set_RemoteFile](./set_remotefile/)(System::String) | Sets the file (path) which is required for "GoToR" action of bookmark. |
| [set_Title](./set_title/)(System::String) | Sets bookmark's title. |
| [set_TitleColor](./set_titlecolor/)(System::Drawing::Color) | Sets the color of bookmark's title. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
