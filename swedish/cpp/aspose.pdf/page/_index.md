---
title: "Aspose::Pdf::Page klass"
linktitle: "Page"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Page klass. Klassen representerar en sida i PDF-dokument i C++."
type: docs
weight: 13000
url: /sv/cpp/aspose.pdf/page/
---
## Page class


Klass som representerar en sida i PDF-dokumentet.

```cpp
class Page : public System::IDisposable,
             public Aspose::Pdf::ISupportsMemoryCleanup,
             public Aspose::Pdf::IOperatorContainer
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Accept](./accept/)(const System::SharedPtr\<Aspose::Pdf::Annotations::AnnotationSelector\>\&) | Accepterar [AnnotationSelector](../) besökarobjekt som tillhandahåller funktionalitet för att arbeta med annotationer. |
| [Accept](./accept/)(const System::SharedPtr\<Aspose::Pdf::Text::TextFragmentAbsorber\>\&) | Accepterar **TextFragmentAbsorber** besökarobjekt som tillhandahåller funktionalitet för att arbeta med textobjekt. |
| [Accept](./accept/)(const System::SharedPtr\<Aspose::Pdf::ImagePlacementAbsorber\>\&) | Accepterar [ImagePlacementAbsorber](../imageplacementabsorber/) besökarobjekt som tillhandahåller funktionalitet för att arbeta med bildplaceringsobjekt. |
| [Accept](./accept/)(const System::SharedPtr\<Aspose::Pdf::Text::TextAbsorber\>\&) | Accepterar **TextAbsorber** besökarobjekt som tillhandahåller funktionalitet för att arbeta med textobjekt. |
| [AddGraphics](./addgraphics/)(const System::SharedPtr\<Aspose::Pdf::Vector::GraphicElementCollection\>\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Lägger till grafik på sidan. Fungerar snabbare än att lägga till element ett i taget med metoden [GraphicElement::AddOnPage(Page)](../). |
| [AddImage](./addimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&, bool) | Lägger till en bild på sidan och placerar den i mitten av den angivna rektangeln samtidigt som bildens proportion bevaras. |
| [AddImage](./addimage/)(const System::String\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Lägger till en sökbar bild på sidan och placerar den i mitten av den angivna rektangeln samtidigt som bildens proportion bevaras. |
| [AddImage](./addimage/)(const System::SharedPtr\<System::IO::Stream\>\&, System::SharedPtr\<Aspose::Pdf::Rectangle\>, int32_t, int32_t, bool, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Lägger till en bild på sidan och placerar den beroende på bildens rektangelposition. |
| [AddImage](./addimage/)(const System::String\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Lägger till en bild på sidan och placerar den i mitten av den angivna rektangeln samtidigt som bildens proportion bevaras. |
| [AddStamp](./addstamp/)(const System::SharedPtr\<Aspose::Pdf::Stamp\>\&) | Placera stämpel på sidan. [Stamp](../stamp/) kan vara sidnummer, bild eller enkel text, t.ex. en logotyp. |
| [AsByteArray](./asbytearray/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Konverterar aktuell sida till bitmap och returnerar sedan en bytearray. |
| [AsXml](./asxml/)() | Konverterar aktuell sida till XML med UTF‑8‑kodning. |
| [CalculateContentBBox](./calculatecontentbbox/)() | Beräknar bbox‑värde – rektangel som innehåller innehållet utan synliga marginaler. |
| [ConvertToPNGMemoryStream](./converttopngmemorystream/)() | Konvertera sidan till PNG för DSR-, OMR- och OCR-bildström. |
| [DeleteGraphics](./deletegraphics/)(const System::SharedPtr\<Aspose::Pdf::Vector::GraphicElementCollection\>\&) | Tar bort grafik från sidan. Fungerar snabbare än att ta bort element ett i taget med metoden [GraphicElement::Remove](../). |
| [Dispose](./dispose/)() override | Frigör minne. |
| [Flatten](./flatten/)() | Tar bort alla fält på sidan och placerar deras värden istället. |
| [FreeMemory](./freememory/)() override | Rensar cachelagrad data. |
| [get_Actions](./get_actions/)() | Hämtar samling av sidegenskaper. |
| [get_Annotations](./get_annotations/)() | Hämtar samling av sidanteckningar. [Annotations](../../aspose.pdf.annotations/) |
| [get_ArtBox](./get_artbox/)() | Hämtar art‑boxen för sidan. |
| [get_Artifacts](./get_artifacts/)() | Hämtar samling av artefakter på sidan. |
| [get_Background](./get_background/)() | Hämtar sidans bakgrundsfärg. |
| [get_BackgroundImage](./get_backgroundimage/)() const | Hämtar bakgrundsbild för sidan (endast för generator, fylls inte i vid läsning av dokumentet). |
| [get_BleedBox](./get_bleedbox/)() | Hämtar bleed‑boxen för sidan. |
| [get_ColorType](./get_colortype/)() | Ställer in färgtyp för sidorna baserat på information från operatorerna SetColor, bilder och formulär. |
| [get_Contents](./get_contents/)() override | Hämtar samling av operatorer i sidans innehållsström. [OperatorCollection](../operatorcollection/) |
| [get_CropBox](./get_cropbox/)() | Hämtar crop‑boxen för sidan. |
| [get_Duration](./get_duration/)() | Hämtar eller anger sidans visningstid. Detta är tiden i sekunder som sidan ska visas under en presentation. Returnerar -1 om varaktigheten inte är definierad. |
| [get_FieldsInTabOrder](./get_fieldsintaborder/)() | Hämtar lista över Field‑objekt i tab‑ordning på den här sidan. |
| [get_Footer](./get_footer/)() const | Hämtar sidfot. |
| [get_Group](./get_group/)() | Hämtar en gruppattributklass som specificerar attributen för sidans sidgrupp för användning i den transparenta bildmodellen. |
| [get_Header](./get_header/)() const | Hämtar sidhuvud. |
| [get_IsAddParagraphsAfterLast](./get_isaddparagraphsafterlast/)() const | Hämtar tillägget av stycken efter det sista stycket på sidan. |
| [get_Layers](./get_layers/)() | Hämtar lager‑samling. |
| [get_MediaBox](./get_mediabox/)() | Hämtar media‑boxen för sidan. |
| [get_NoteLineStyle](./get_notelinestyle/)() | Hämtar linjestilen för anteckningar (endast för generator, fylls inte i vid läsning av dokument). |
| [get_Number](./get_number/)() | Hämta sidnumret. |
| [get_PageInfo](./get_pageinfo/)() | Hämtar sidinformationen (endast för generator, fylls inte i när dokument läses). |
| [get_Paragraphs](./get_paragraphs/)() | Hämtar styckena. |
| [get_Rect](./get_rect/)() | Hämtar rektangeln för sidan. Vid hämtning: sidans beskärningsruta returneras om den är angiven, annars returneras sidans mediabox. Vid inställning: sidans mediabox sätts alltid. Observera att denna egenskap inte tar hänsyn till sidrotation. För att hämta sidrektangeln med hänsyn till rotation, använd ActualRect. |
| [get_Resources](./get_resources/)() override | Hämtar sidresurser. Objektet [Resources](../resources/) innehåller samlingar av bilder, formulär och teckensnitt. [Resources](../resources/) |
| [get_Rotate](./get_rotate/)() | Hämtar sidans rotation. |
| [get_RotationMatrix](./get_rotationmatrix/)() | Hämtar transformationsmatrisen för sidan. |
| [get_TabOrder](./get_taborder/)() | Hämtar flikordningen för sidan. Möjliga värden: [Row](../row/), Column. Standard, Manual. |
| [get_TocInfo](./get_tocinfo/)() const | Hämtar information om innehållsförteckning. |
| [get_TrimBox](./get_trimbox/)() | Hämtar trimrutan för sidan. |
| [get_UserUnit](./get_userunit/)() | Hämtar UserUnit‑värdet. Ett positivt tal som anger storleken på standardenhet i användarutrymmet, i multiplar av 1 / 72 tum. Standardvärdet är 1. Ange noll eller ett negativt värde för att rensa detta fält på sidan. |
| [get_Watermark](./get_watermark/)() | Hämtar sidans vattenstämpel. |
| [GetNotifications](./getnotifications/)() | Returnerar aviseringar om interna operationer med sidans innehåll. (Endast aviseringar om stycke‑händelser i scenarier för texttillägg stöds för närvarande.) |
| [GetPageRect](./getpagerect/)(bool) | Returnerar sidans rektangel enligt dess CropBox (eller MediaBox om CropBox är null). |
| [GetResources](./getresources/)() override | Hämtar resurserna som är associerade med sidan. |
| [HasVectorGraphics](./hasvectorgraphics/)() | Detekterar förekomsten av vektorgrafik, om den finns på sidan. |
| static [IntToRotation](./inttorotation/)(int32_t) | Översätter heltalsvärdet till motsvarande rotationsenum‑medlem. |
| [IsBlank](./isblank/)(double) | Hämtar flaggan som anger om sidan är tom eller inte. |
| [MakeGrayscale](./makegrayscale/)() | Konverterar sidan till gråskala. |
| [MergeLayers](./mergelayers/)(const System::String\&) | Slår samman alla lager på sidan till ett enda lager med det angivna nya lagernamnet. |
| [MergeLayers](./mergelayers/)(const System::String\&, const System::String\&) | Slår samman alla lager på sidan till ett enda lager med det angivna nya lagernamnet och valfri innehållsgrupp [Id](../id/). |
| [Resize](./resize/)(System::SharedPtr\<Aspose::Pdf::PageSize\>) | Ändrar storlek på sidan. |
| static [RotationToInt](./rotationtoint/)(Aspose::Pdf::Rotation) | Översätter rotationsenum‑medlem till heltalsvärde. |
| [SendTo](./sendto/)(const System::SharedPtr\<Aspose::Pdf::Devices::PageDevice\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Skickar sidan för bearbetning med given sid-enhet. |
| [SendTo](./sendto/)(const System::SharedPtr\<Aspose::Pdf::Devices::PageDevice\>\&, const System::String\&) | Skickar sidan för bearbetning med given sid-enhet. |
| [set_ArtBox](./set_artbox/)(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Ställer in art‑boxen för sidan. |
| [set_Background](./set_background/)(const System::SharedPtr\<Aspose::Pdf::Color\>\&) | Ställer in bakgrundsfärgen för sidan. |
| [set_BackgroundImage](./set_backgroundimage/)(const System::SharedPtr\<Aspose::Pdf::Image\>\&) | Ställer in bakgrundsbild för sidan (endast för generator, fylls inte i vid läsning av dokumentet). |
| [set_BleedBox](./set_bleedbox/)(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Ställer in bleed-boxen för sidan. |
| [set_CropBox](./set_cropbox/)(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Ställer in beskärningsrutan för sidan. |
| [set_Duration](./set_duration/)(double) | Hämtar eller anger sidans visningstid. Detta är tiden i sekunder som sidan ska visas under en presentation. Returnerar -1 om varaktigheten inte är definierad. |
| [set_Footer](./set_footer/)(const System::SharedPtr\<Aspose::Pdf::HeaderFooter\>\&) | Ställer in sidfot. |
| [set_Group](./set_group/)(const System::SharedPtr\<Aspose::Pdf::Group\>\&) | Ställer in en gruppattributklass som specificerar attributen för sidans sidgrupp för användning i den transparenta bildmodellen. |
| [set_Header](./set_header/)(const System::SharedPtr\<Aspose::Pdf::HeaderFooter\>\&) | Ställer in sidhuvud. |
| [set_IsAddParagraphsAfterLast](./set_isaddparagraphsafterlast/)(bool) | Ställer in tillägget av stycken efter det sista stycket på sidan. |
| [set_Layers](./set_layers/)(const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<Aspose::Pdf::Layer\>\>\>\&) | Ställer in lagerkollektionen. |
| [set_MediaBox](./set_mediabox/)(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Ställer in mediaboxen för sidan. |
| [set_NoteLineStyle](./set_notelinestyle/)(const System::SharedPtr\<Aspose::Pdf::GraphInfo\>\&) | Ställer in linjestilen för anteckningar.(endast för generator, inte fylls i när dokumentet läses) |
| [set_PageInfo](./set_pageinfo/)(const System::SharedPtr\<Aspose::Pdf::PageInfo\>\&) | Ställer in sidinformationen (endast för generator, inte fylls i när dokumentet läses). |
| [set_Paragraphs](./set_paragraphs/)(const System::SharedPtr\<Aspose::Pdf::Paragraphs\>\&) | Hämtar styckena. |
| [set_Rect](./set_rect/)(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Ställer in rektangeln för sidan. Vid hämtning: returneras sidans beskärningsruta om den är specificerad, annars returneras sidans mediabox. Vid inställning: sidans mediabox sätts alltid. Observera att denna egenskap inte tar hänsyn till sidrotation. För att få sidrektangeln med hänsyn till rotation, använd ActualRect. |
| [set_Rotate](./set_rotate/)(Aspose::Pdf::Rotation) | Ställer in rotationen för sidan. |
| [set_TabOrder](./set_taborder/)(Aspose::Pdf::TabOrder) | Ställer in tabb-ordningen för sidan. Möjliga värden: [Row](../row/), Column. Standard, Manuell. |
| [set_TocInfo](./set_tocinfo/)(const System::SharedPtr\<Aspose::Pdf::TocInfo\>\&) | Ställer in information för innehållsförteckning. |
| [set_TrimBox](./set_trimbox/)(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Ställer in trim-boxen för sidan. |
| [set_UserUnit](./set_userunit/)(double) | Ställer in UserUnit-värdet. Ett positivt tal som anger storleken på standardenheterna i användarutrymmet, i multiplar av 1 / 72 tum. Standardvärdet är 1. Ange noll eller ett negativt värde för att rensa detta fält på sidan. |
| [set_Watermark](./set_watermark/)(const System::SharedPtr\<Aspose::Pdf::Watermark\>\&) | Ställer in vattenstämpeln för sidan. |
| [SetPageSize](./setpagesize/)(double, double) | Ställer in sidstorlek för sidan. |
| [TrySaveVectorGraphics](./trysavevectorgraphics/)(const System::String\&) | Försöker spara vektorgrafik om den finns på sidan. Sparaformatet är SVG. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [BeforePageGenerate](./beforepagegenerate/) | Procedur för att anpassa sidhuvud och sidfot. |
## Se även

* Class [IDisposable](../../system/idisposable/)
* Class [ISupportsMemoryCleanup](../isupportsmemorycleanup/)
* Class [IOperatorContainer](../ioperatorcontainer/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
