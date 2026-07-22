---
title: "Aspose::Pdf::Facades::PdfContentEditor klass"
linktitle: "PdfContentEditor"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfContentEditor klass. Representerar en klass för att redigera innehållet i en PDF‑fil i C++."
type: docs
weight: 1700
url: /sv/cpp/aspose.pdf.facades/pdfcontenteditor/
---
## PdfContentEditor class


Representerar en klass för att redigera PDF-filens innehåll.

```cpp
class PdfContentEditor : public Aspose::Pdf::Facades::SaveableFacade
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AddDocumentAdditionalAction](./adddocumentadditionalaction/)(const System::String\&, const System::String\&) | Lägger till en ytterligare åtgärd för dokumenthändelse. |
| [AddDocumentAttachment](./adddocumentattachment/)(const System::String\&, const System::String\&) | Lägger till dokumentbilaga utan någon annotation. |
| [AddDocumentAttachment](./adddocumentattachment/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, const System::String\&) | Lägger till dokumentbilaga utan någon annotation. |
| [BindPdf](./bindpdf/)(System::String) override | Kopplar en PDF‑fil för redigering. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<System::IO::Stream\>) override | Kopplar en PDF‑ström för redigering. |
| [ChangeViewerPreference](./changeviewerpreference/)(int32_t) | Ändrar visningspreferensen. |
| [Close](./close/)() override | Stänger öppet dokument. |
| [CreateApplicationLink](./createapplicationlink/)(System::Drawing::Rectangle, const System::String\&, int32_t, System::Drawing::Color, const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\&) | Skapar en länk för att starta ett program i PDF‑dokumentet. |
| [CreateApplicationLink](./createapplicationlink/)(System::Drawing::Rectangle, const System::String\&, int32_t, System::Drawing::Color) | Skapar en länk för att starta ett program i PDF‑dokumentet. |
| [CreateApplicationLink](./createapplicationlink/)(System::Drawing::Rectangle, const System::String\&, int32_t) | Skapar en länk för att starta ett program i PDF‑dokumentet. |
| [CreateBookmarksAction](./createbookmarksaction/)(const System::String\&, System::Drawing::Color, bool, bool, const System::String\&, const System::String\&, const System::String\&) | Skapar ett bokmärke med den angivna åtgärden. |
| [CreateCaret](./createcaret/)(int32_t, System::Drawing::Rectangle, System::Drawing::Rectangle, const System::String\&, const System::String\&, System::Drawing::Color) | Skapar marköranteckning. |
| [CreateCustomActionLink](./createcustomactionlink/)(System::Drawing::Rectangle, int32_t, System::Drawing::Color, const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\&) | Skapar en länk till anpassade åtgärder i PDF-dokumentet. |
| [CreateFileAttachment](./createfileattachment/)(System::Drawing::Rectangle, const System::String\&, const System::String\&, int32_t, const System::String\&) | Skapar filbilagsanteckning. |
| [CreateFileAttachment](./createfileattachment/)(System::Drawing::Rectangle, const System::String\&, const System::String\&, int32_t, const System::String\&, double) | Skapar filbilagsanteckning. |
| [CreateFileAttachment](./createfileattachment/)(System::Drawing::Rectangle, const System::String\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, int32_t, const System::String\&) | Skapar filbilagsanteckning. |
| [CreateFileAttachment](./createfileattachment/)(System::Drawing::Rectangle, const System::String\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, int32_t, const System::String\&, double) | Skapar filbilagsanteckning. |
| [CreateFreeText](./createfreetext/)(System::Drawing::Rectangle, const System::String\&, int32_t) | Skapar fri textanteckning i PDF-dokumentet. |
| [CreateJavaScriptLink](./createjavascriptlink/)(const System::String\&, System::Drawing::Rectangle, int32_t, System::Drawing::Color) | Skapar en länk till JavaScript i PDF-dokumentet. |
| [CreateLine](./createline/)(System::Drawing::Rectangle, const System::String\&, float, float, float, float, int32_t, int32_t, System::Drawing::Color, const System::String\&, const System::ArrayPtr\<int32_t\>\&, const System::ArrayPtr\<System::String\>\&) | Skapar linjeanteckning. |
| [CreateLocalLink](./createlocallink/)(System::Drawing::Rectangle, int32_t, int32_t, System::Drawing::Color, const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\&) | Skapar en lokal länk i PDF-dokumentet. |
| [CreateLocalLink](./createlocallink/)(System::Drawing::Rectangle, int32_t, int32_t, System::Drawing::Color) | Skapar en lokal länk i PDF-dokumentet. |
| [CreateLocalLink](./createlocallink/)(System::Drawing::Rectangle, int32_t, int32_t) | Skapar en lokal länk i PDF-dokumentet. |
| [CreateMarkup](./createmarkup/)(System::Drawing::Rectangle, const System::String\&, int32_t, int32_t, System::Drawing::Color) | Skapar markup-anteckning i PDF-dokumentet. |
| [CreateMovie](./createmovie/)(System::Drawing::Rectangle, const System::String\&, int32_t) | Skapar film [Annotations](../../aspose.pdf.annotations/). |
| [CreatePdfDocumentLink](./createpdfdocumentlink/)(System::Drawing::Rectangle, const System::String\&, int32_t, int32_t, System::Drawing::Color, const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\&) | Skapar en länk till en annan PDF-dokumentsida. |
| [CreatePdfDocumentLink](./createpdfdocumentlink/)(System::Drawing::Rectangle, const System::String\&, int32_t, int32_t, System::Drawing::Color) | Skapar en länk till en annan PDF-dokumentsida. |
| [CreatePdfDocumentLink](./createpdfdocumentlink/)(System::Drawing::Rectangle, const System::String\&, int32_t, int32_t) | Skapar en länk till en annan PDF-dokumentsida. |
| [CreatePolygon](./createpolygon/)(const System::SharedPtr\<LineInfo\>\&, int32_t, System::Drawing::Rectangle, const System::String\&) | Skapar polygonanteckning. |
| [CreatePolyLine](./createpolyline/)(const System::SharedPtr\<LineInfo\>\&, int32_t, System::Drawing::Rectangle, const System::String\&) | Skapar polylinjeanteckning. |
| [CreatePopup](./createpopup/)(System::Drawing::Rectangle, const System::String\&, bool, int32_t) | Skapar popup-anteckning i PDF-dokumentet. |
| [CreateRubberStamp](./createrubberstamp/)(int32_t, System::Drawing::Rectangle, const System::String\&, const System::String\&, System::Drawing::Color) | Skapar en gummistämpelanteckning. |
| [CreateRubberStamp](./createrubberstamp/)(int32_t, System::Drawing::Rectangle, const System::String\&, System::Drawing::Color, const System::String\&) | Skapar en gummistämpelanteckning. |
| [CreateRubberStamp](./createrubberstamp/)(int32_t, System::Drawing::Rectangle, const System::String\&, System::Drawing::Color, const System::SharedPtr\<System::IO::Stream\>\&) | Skapar en gummistämpelanteckning. |
| [CreateSound](./createsound/)(System::Drawing::Rectangle, const System::String\&, const System::String\&, int32_t, const System::String\&) | Skapar ljud [Annotations](../../aspose.pdf.annotations/). |
| [CreateSquareCircle](./createsquarecircle/)(System::Drawing::Rectangle, const System::String\&, System::Drawing::Color, bool, int32_t, int32_t) | Skapar kvadrat-cirkel-anteckning. |
| [CreateText](./createtext/)(System::Drawing::Rectangle, const System::String\&, const System::String\&, bool, const System::String\&, int32_t) | Skapar textanteckning i PDF-dokumentet. |
| [CreateWebLink](./createweblink/)(System::Drawing::Rectangle, const System::String\&, int32_t, System::Drawing::Color, const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\&) | Skapar en webb-länk i PDF-dokumentet. |
| [CreateWebLink](./createweblink/)(System::Drawing::Rectangle, const System::String\&, int32_t, System::Drawing::Color) | Skapar en webb-länk i PDF-dokumentet. |
| [CreateWebLink](./createweblink/)(System::Drawing::Rectangle, const System::String\&, int32_t) | Skapar en webb-länk i PDF-dokumentet. |
| [DeleteAttachments](./deleteattachments/)() | Tar bort alla bilagor i PDF-dokumentet. |
| [DeleteImage](./deleteimage/)(int32_t, const System::ArrayPtr\<int32_t\>\&) | Tar bort de angivna bilderna på den angivna sidan. |
| [DeleteImage](./deleteimage/)() | Tar bort alla bilder från PDF-dokumentet. |
| [DeleteStamp](./deletestamp/)(int32_t, const System::ArrayPtr\<int32_t\>\&) | Tar bort flera stämplar på den angivna sidan efter stämpelindex. |
| [DeleteStampById](./deletestampbyid/)(int32_t, int32_t) | Tar bort stämpel på den angivna sidan efter stämpel-ID. |
| [DeleteStampById](./deletestampbyid/)(int32_t) | Ta bort stämpel efter ID från alla sidor i dokumentet. |
| [DeleteStampByIds](./deletestampbyids/)(const System::ArrayPtr\<int32_t\>\&) | Tar bort stämplar med angivna ID:n från alla sidor i dokumentet. |
| [DeleteStampByIds](./deletestampbyids/)(int32_t, const System::ArrayPtr\<int32_t\>\&) | Raderar stämplar på den angivna sidan med flera stämpel‑ID:n. |
| [DrawCurve](./drawcurve/)(const System::SharedPtr\<LineInfo\>\&, int32_t, System::Drawing::Rectangle, const System::String\&) | Skapar kurvannotering. |
| [ExtractLink](./extractlink/)() | Extraherar samlingen av Link‑instanser som finns i PDF‑dokumentet. |
| [get_ReplaceTextStrategy](./get_replacetextstrategy/)() const | En uppsättning parametrar för ersättningsoperation av text. |
| [get_TextEditOptions](./get_texteditoptions/)() const | Hämtar alternativ för textredigering. |
| [get_TextReplaceOptions](./get_textreplaceoptions/)() const | Hämtar alternativ för textersättning. |
| [get_TextSearchOptions](./get_textsearchoptions/)() const | Hämtar alternativ för textsökning. |
| [GetStamps](./getstamps/)(int32_t) | Returnerar en array av stämplar på sidan. |
| [GetViewerPreference](./getviewerpreference/)() | Returnerar visningspreferensen. |
| [HideStampById](./hidestampbyid/)(int32_t, int32_t) | Döljer stämpeln. Efter döljs kan stämpelns synlighet återställas med metoden ShowStampById. |
| [MoveStamp](./movestamp/)(int32_t, int32_t, double, double) | Ändrar positionen för stämpeln på sidan. |
| [MoveStampById](./movestampbyid/)(int32_t, int32_t, double, double) | Ändrar positionen för stämpeln på sidan. |
| [PdfContentEditor](./pdfcontenteditor/)() | Konstruktorn för objektet [PdfContentEditor](./). |
| [PdfContentEditor](./pdfcontenteditor/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Initierar ett nytt [PdfContentEditor](./)-objekt baserat på *dokumentet*. |
| [RemoveDocumentOpenAction](./removedocumentopenaction/)() | Tar bort öppen åtgärd från dokumentet. Denna operation är användbar när man sammanfogar flera dokument som använder en explicit 'GoTo'-åtgärd vid start. |
| [ReplaceImage](./replaceimage/)(int32_t, int32_t, const System::String\&) | Ersätter den angivna bilden på den angivna sidan i PDF‑dokumentet med en annan bild. |
| [ReplaceText](./replacetext/)(const System::String\&, int32_t, const System::String\&, const System::SharedPtr\<Text::TextState\>\&) | Ersätter text i PDF‑filen på den angivna sidan. Objektet [TextState](../) (teckensnittsfamilj, färg) kan specificeras för den ersatta texten. |
| [ReplaceText](./replacetext/)(const System::String\&, const System::String\&) | Ersätter text i PDF‑filen. |
| [ReplaceText](./replacetext/)(const System::String\&, int32_t, const System::String\&) | Ersätter text i PDF‑filen på den angivna sidan. |
| [ReplaceText](./replacetext/)(const System::String\&, const System::String\&, const System::SharedPtr\<Text::TextState\>\&) | Ersätter text i PDF‑filen med hjälp av det specificerade objektet [TextState](../). |
| [ReplaceText](./replacetext/)(const System::String\&, const System::String\&, int32_t) | Ersätter text i PDF‑filen och anger teckenstorlek. |
| [set_ReplaceTextStrategy](./set_replacetextstrategy/)(const System::SharedPtr\<Aspose::Pdf::Facades::ReplaceTextStrategy\>\&) | En uppsättning parametrar för ersättningsoperation av text. |
| [set_TextEditOptions](./set_texteditoptions/)(const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\&) | Ställer in alternativ för textredigering. |
| [set_TextReplaceOptions](./set_textreplaceoptions/)(const System::SharedPtr\<Aspose::Pdf::Text::TextReplaceOptions\>\&) | Ställer in alternativ för textersättning. |
| [set_TextSearchOptions](./set_textsearchoptions/)(const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&) | Ställer in alternativ för textsökning. |
| [ShowStampById](./showstampbyid/)(int32_t, int32_t) | Visar stämpeln som dolts av HiddenStampById. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [DocumentClose](./documentclose/) | En dokumenthändelsetyp. Stänger ett dokument. |
| static [DocumentOpen](./documentopen/) | En dokumenthändelsetyp. Öppnar ett dokument. |
| static [DocumentPrinted](./documentprinted/) | En dokumenthändelsetyp. Utför en åtgärd efter utskrift. |
| static [DocumentSaved](./documentsaved/) | En dokumenthändelsetyp. Utför en åtgärd efter sparande. |
| static [DocumentWillPrint](./documentwillprint/) | En dokumenthändelsetyp. Utför en åtgärd före utskrift. |
| static [DocumentWillSave](./documentwillsave/) | En dokumenthändelsetyp. Utför en åtgärd före sparande. |
## Se även

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
