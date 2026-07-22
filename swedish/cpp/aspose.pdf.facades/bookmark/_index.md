---
title: "Aspose::Pdf::Facades::Bookmark klass."
linktitle: "Bokmärke"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::Bookmark klass. Representerar ett bokmärke i C++."
type: docs
weight: 300
url: /sv/cpp/aspose.pdf.facades/bookmark/
---
## Bookmark class


Representerar ett bokmärke.

```cpp
class Bookmark : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Bookmark](./bookmark/)() | Initierar en ny instans av klassen [Bookmark](./). |
| [get_Action](./get_action/)() const | Hämtar åtgärden som är bunden till bokmärket. Om [PageNumber](../../aspose.pdf/pagenumber/) är angivet kan åtgärden inte specificeras. Åtgärdstypen inkluderar: "GoTo", "GoToR", "Launch", "Named". |
| [get_BoldFlag](./get_boldflag/)() const | Hämtar fetstilflaggan för bokmärkets titel. |
| [get_ChildItem](./get_childitem/)() | Hämtar bokmärkets barn. |
| [get_ChildItems](./get_childitems/)() const | Hämtar bokmärkets barn. |
| [get_Destination](./get_destination/)() const | Hämtar bokmärkets destinationsida. Krävs om åtgärden är satt till string.Empty. |
| [get_ItalicFlag](./get_italicflag/)() const | Hämtar kursivflaggan för bokmärkets titel. |
| [get_Level](./get_level/)() const | Hämtar bokmärkets hierarkinivå. |
| [get_Open](./get_open/)() const | Hämtar bokmärkets tillstånd (öppen, stängd). |
| [get_PageDisplay](./get_pagedisplay/)() const | Hämtar typen av visning för bokmärkets destinationsida. |
| [get_PageDisplay_Bottom](./get_pagedisplay_bottom/)() const | Hämtar den nedre koordinaten för sidvisning. |
| [get_PageDisplay_Left](./get_pagedisplay_left/)() const | Hämtar den vänstra koordinaten för sidvisning. |
| [get_PageDisplay_Right](./get_pagedisplay_right/)() const | Hämtar den högra koordinaten för sidvisning. |
| [get_PageDisplay_Top](./get_pagedisplay_top/)() const | Hämtar den övre koordinaten för sidvisning. |
| [get_PageDisplay_Zoom](./get_pagedisplay_zoom/)() const | Hämtar zoomfaktorn för sidvisning. |
| [get_PageNumber](./get_pagenumber/)() const | Hämtar numret på bokmärkets destinationsida. |
| [get_RemoteFile](./get_remotefile/)() const | Hämtar filen (sökvägen) som krävs för "GoToR"-åtgärden för bokmärket. |
| [get_Title](./get_title/)() const | Hämtar bokmärkets titel. |
| [get_TitleColor](./get_titlecolor/)() const | Hämtar färgen på bokmärkets titel. |
| [set_Action](./set_action/)(const System::String\&) | Ställer in åtgärden som är bunden till bokmärket. Om [PageNumber](../../aspose.pdf/pagenumber/) är angivet kan åtgärden inte specificeras. Åtgärdstypen inkluderar: "GoTo", "GoToR", "Launch", "Named". |
| [set_BoldFlag](./set_boldflag/)(bool) | Ställer in fetstilflaggan för bokmärkets titel. |
| [set_ChildItem](./set_childitem/)(const System::SharedPtr\<Bookmarks\>\&) | Sätter bokmärkets barn. |
| [set_ChildItems](./set_childitems/)(const System::SharedPtr\<Bookmarks\>\&) | Sätter bokmärkets barn. |
| [set_Destination](./set_destination/)(const System::String\&) | Sätter bokmärkets destinationssida. Krävs om åtgärden är inställd som string.Empty. |
| [set_ItalicFlag](./set_italicflag/)(bool) | Sätter kursivflaggan för bokmärkets titel. |
| [set_Level](./set_level/)(int32_t) | Sätter bokmärkets hierarkinivå. |
| [set_Open](./set_open/)(bool) | Sätter bokmärkets tillstånd (öppen, stängd). |
| [set_PageDisplay](./set_pagedisplay/)(const System::String\&) | Sätter visningstypen för bokmärkets destinationssida. |
| [set_PageDisplay_Bottom](./set_pagedisplay_bottom/)(int32_t) | Sätter den nedre koordinaten för sidvisning. |
| [set_PageDisplay_Left](./set_pagedisplay_left/)(int32_t) | Sätter den vänstra koordinaten för sidvisning. |
| [set_PageDisplay_Right](./set_pagedisplay_right/)(int32_t) | Sätter den högra koordinaten för sidvisning. |
| [set_PageDisplay_Top](./set_pagedisplay_top/)(int32_t) | Sätter den övre koordinaten för sidvisning. |
| [set_PageDisplay_Zoom](./set_pagedisplay_zoom/)(int32_t) | Sätter zoomfaktorn för sidvisning. |
| [set_PageNumber](./set_pagenumber/)(int32_t) | Sätter numret på bokmärkets destinationssida. |
| [set_RemoteFile](./set_remotefile/)(const System::String\&) | Sätter filen (sökvägen) som krävs för "GoToR"-åtgärden för bokmärket. |
| [set_Title](./set_title/)(const System::String\&) | Sätter bokmärkets titel. |
| [set_TitleColor](./set_titlecolor/)(System::Drawing::Color) | Sätter färgen på bokmärkets titel. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
