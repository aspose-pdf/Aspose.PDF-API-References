---
title: "Aspose::Pdf::Facades::PdfPageEditor class"
linktitle: "PdfPageEditor"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfPageEditor class. Representerar en klass för att redigera PDF-filens sida, inklusive rotera sida, zooma sida, flytta position och ändra sidstorlek i C++."
type: docs
weight: 2800
url: /sv/cpp/aspose.pdf.facades/pdfpageeditor/
---
## PdfPageEditor class


Representerar en klass för att redigera PDF-filens sida, inklusive rotera sida, zooma sida, flytta position och ändra sidstorlek.

```cpp
class PdfPageEditor : public Aspose::Pdf::Facades::SaveableFacade
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [ApplyChanges](./applychanges/)() | Tillämpa ändringar som gjorts på dokumentets sidor. |
| [get_DisplayDuration](./get_displayduration/)() | Hämtar visningstid för sidor. |
| [get_HorizontalAlignment](./get_horizontalalignment/)() | Hämtar den horisontella justeringen av det ursprungliga PDF-innehållet på resultatsidan, standard är AlignmentType.Left. |
| [get_PageRotations](./get_pagerotations/)() | En hashtabell innehåller sidnumret och rotationsgraden, nyckeln representerar sidnumret, värdet för nyckeln representerar rotationen i grader. |
| [get_PageSize](./get_pagesize/)() | Hämtar sidstorleken för utdatafilen. |
| [get_ProcessPages](./get_processpages/)() | Hämtar sidnumren som ska redigeras. Som standard kommer varje sida att redigeras. |
| [get_Rotation](./get_rotation/)() | Hämtar rotationen för sidorna, rotationen måste vara 0, 90, 180 eller 270. Standardvärdet är 0. |
| [get_TransitionDuration](./get_transitionduration/)() | Hämtar varaktigheten för övergångseffekten. |
| [get_TransitionType](./get_transitiontype/)() | Hämtar övergångsstilen som ska användas när man går till den här sidan från en annan under en presentation. |
| [get_VerticalAlignmentType](./get_verticalalignmenttype/)() | Hämtar eller anger den vertikala justeringen av det ursprungliga PDF-innehållet på resultatsidan, standard är VerticalAlignmentType.Bottom. |
| [get_Zoom](./get_zoom/)() | Hämtar eller anger zoomkoefficienten. Värdet 1.0 motsvarar 100 %. Standardvärdet är 1.0. |
| [GetPageBoxSize](./getpageboxsize/)(int32_t, const System::String\&) | Returnerar storleken på den angivna rutan i dokumentet. |
| [GetPageRotation](./getpagerotation/)(int32_t) | Returnerar rotationen för den angivna sidan. |
| [GetPages](./getpages/)() | Returnerar det totala antalet sidor. |
| [GetPageSize](./getpagesize/)(int32_t) | Returnerar sidstorleken för den angivna sidan. |
| [MovePosition](./moveposition/)(float, float) | Flyttar origo från (0, 0) till den angivna punkten. Origo är vänster-nederkant och enheten är punkt (1 tum = 72 punkter). |
| [PdfPageEditor](./pdfpageeditor/)() | Konstruktor för klassen [PdfPageEditor](./). |
| [PdfPageEditor](./pdfpageeditor/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Konstruktor för klassen [PdfPageEditor](./). |
| [Save](./save/)(System::String) override | Sparar ändrat dokument till fil. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>) override | Sparar ändrat dokument till ström. |
| [set_DisplayDuration](./set_displayduration/)(int32_t) | Anger visningsvaraktigheten för sidor. |
| [set_HorizontalAlignment](./set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) | Anger den horisontella justeringen av det ursprungliga PDF-innehållet på resultatsidan, standard är AlignmentType.Left. |
| [set_PageRotations](./set_pagerotations/)(const System::SharedPtr\<System::Collections::Generic::Dictionary\<int32_t, int32_t\>\>\&) | En hashtabell innehåller sidnumret och rotationsgraden, nyckeln representerar sidnumret, värdet för nyckeln representerar rotationen i grader. |
| [set_PageSize](./set_pagesize/)(const System::SharedPtr\<Aspose::Pdf::PageSize\>\&) | Anger sidstorleken för utdatafilen. |
| [set_ProcessPages](./set_processpages/)(const System::ArrayPtr\<int32_t\>\&) | Anger sidnumren som ska redigeras. Som standard redigeras varje sida. |
| [set_Rotation](./set_rotation/)(int32_t) | Anger rotationen för sidorna, rotationen måste vara 0, 90, 180 eller 270. Standardvärdet är 0. |
| [set_TransitionDuration](./set_transitionduration/)(int32_t) | Anger varaktigheten för övergångseffekten. |
| [set_TransitionType](./set_transitiontype/)(int32_t) | Anger övergångsstilen som ska användas när man går till den här sidan från en annan under en presentation. |
| [set_VerticalAlignmentType](./set_verticalalignmenttype/)(Aspose::Pdf::VerticalAlignment) | Hämtar eller anger den vertikala justeringen av det ursprungliga PDF-innehållet på resultatsidan, standard är VerticalAlignmentType.Bottom. |
| [set_Zoom](./set_zoom/)(float) | Hämtar eller anger zoomkoefficienten. Värdet 1.0 motsvarar 100 %. Standardvärdet är 1.0. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static constexpr [BLINDH](./blindh/) | Vertikala persienner. |
| static constexpr [BLINDV](./blindv/) | Vertikala persienner. |
| static constexpr [BTWIPE](./btwipe/) | Nedifrån-uppåt svep. |
| static constexpr [DGLITTER](./dglitter/) | Diagonal glitter. |
| static constexpr [DISSOLVE](./dissolve/) | Den gamla sidan löser upp sig. |
| static constexpr [INBOX](./inbox/) | Inåtriktad ruta. |
| static constexpr [LRGLITTER](./lrglitter/) | Vänster-höger glitter. |
| static constexpr [LRWIPE](./lrwipe/) | Vänster-höger svep. |
| static constexpr [OUTBOX](./outbox/) | Utåtriktad ruta. |
| static constexpr [RLWIPE](./rlwipe/) | Höger-vänster svep. |
| static constexpr [SPLITHIN](./splithin/) | IN horisontell delning. |
| static constexpr [SPLITHOUT](./splithout/) | Ut horisontell delning. |
| static constexpr [SPLITVIN](./splitvin/) | In vertikal delning. |
| static constexpr [SPLITVOUT](./splitvout/) | Ut vertikal delning. |
| static constexpr [TBGLITTER](./tbglitter/) | Topp-ned glitter. |
| static constexpr [TBWIPE](./tbwipe/) | Topp-ned svep. |
## Se även

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
