---
title: "Aspose::Pdf::HtmlLoadOptions class"
linktitle: "HtmlLoadOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::HtmlLoadOptions class. Representerar alternativ för att ladda/importera html‑fil till pdf‑dokument i C++."
type: docs
weight: 7200
url: /sv/cpp/aspose.pdf/htmlloadoptions/
---
## HtmlLoadOptions class


Representerar alternativ för att läsa in/ importera HTML‑fil till PDF‑dokument.

```cpp
class HtmlLoadOptions : public Aspose::Pdf::LoadOptions
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_BasePath](./get_basepath/)() const | Bas‑sökvägen/URL för HTML‑filen. |
| [get_CreateLogicalStructure](./get_createlogicalstructure/)() const | Hämtar ett värde som indikerar om man ska skapa en logisk struktur i det resulterande PDF‑dokumentet. |
| [get_HtmlMediaType](./get_htmlmediatype/)() const | Hämtar möjliga mediatyper som används under rendering. |
| [get_InputEncoding](./get_inputencoding/)() const | Hämtar attributet som specificerar den kodning som används för detta dokument vid parsning. Om detta attribut är null kommer kodningen att bestämmas från dokumentets teckenuppsättningsattribut. |
| [get_IsEmbedFonts](./get_isembedfonts/)() const | Hämtar inbäddning av teckensnitt i resultatsdokumentet. |
| [get_IsPriorityCssPageRule](./get_isprioritycsspagerule/)() const |  |
| [get_IsRenderToSinglePage](./get_isrendertosinglepage/)() const | Hämtar rendering av hela dokumentet till en enda sida. |
| [get_PageInfo](./get_pageinfo/)() const | Hämtar dokumentets sidinformation. |
| [get_PageLayoutOption](./get_pagelayoutoption/)() const | Hämtar layoutalternativ. |
| [HtmlLoadOptions](./htmlloadoptions/)() | Skapar laddningsalternativ för konvertering av html till pdf‑dokument med tom basväg. |
| [HtmlLoadOptions](./htmlloadoptions/)(const System::String\&) | Skapar laddningsalternativ för konvertering av html till pdf‑dokument med definierad basväg. |
| [set_CreateLogicalStructure](./set_createlogicalstructure/)(bool) | Ställer in ett värde som indikerar om en logisk struktur ska skapas i det resulterande PDF‑dokumentet. |
| [set_HtmlMediaType](./set_htmlmediatype/)(Aspose::Pdf::HtmlMediaType) | Ställer in möjliga mediatyper som används under rendering. |
| [set_InputEncoding](./set_inputencoding/)(const System::String\&) | Ställer in attributet som specificerar den kodning som används för detta dokument vid parsning. Om detta attribut är null kommer kodningen att bestämmas från dokumentets teckenuppsättningsattribut. |
| [set_IsEmbedFonts](./set_isembedfonts/)(bool) | Ställer in inbäddning av teckensnitt i resultatsdokumentet. |
| [set_IsPriorityCssPageRule](./set_isprioritycsspagerule/)(bool) |  |
| [set_IsRenderToSinglePage](./set_isrendertosinglepage/)(bool) | Ställer in rendering av hela dokumentet till en enda sida. |
| [set_PageInfo](./set_pageinfo/)(const System::SharedPtr\<Aspose::Pdf::PageInfo\>\&) | Ställer in dokumentets sidinformation. |
| [set_PageLayoutOption](./set_pagelayoutoption/)(HtmlPageLayoutOption) | Ställer in layoutalternativ. |
## Se även

* Class [LoadOptions](../loadoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
