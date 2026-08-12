---
title: "Aspose::Pdf::BaseParagraph class"
linktitle: "BaseParagraph"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::BaseParagraph class. Representerar ett abstrakt basobjekt som kan läggas till på sidan (doc.Paragraphs.Add()) i C++."
type: docs
weight: 1000
url: /sv/cpp/aspose.pdf/baseparagraph/
---
## BaseParagraph class


Representerar ett abstrakt basobjekt som kan läggas till på sidan (doc.Paragraphs.Add()).

```cpp
class BaseParagraph : public System::ICloneable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [BaseParagraph](./baseparagraph/)() |  |
| [Clone](./clone/)() override | Klonar denna instans. Virtuell metod. Returnerar alltid null. |
| virtual [get_HorizontalAlignment](./get_horizontalalignment/)() | Hämtar en horisontell justering av stycket. |
| virtual [get_Hyperlink](./get_hyperlink/)() | Hämtar fragmentets hyperlänk (för pdf‑generator). |
| [get_IsFirstParagraphInColumn](./get_isfirstparagraphincolumn/)() const | Hämtar ett booleskt värde som indikerar om detta stycke kommer att vara i nästa kolumn. Standard är false. (för pdf‑generering) |
| [get_IsInLineParagraph](./get_isinlineparagraph/)() const | Hämtar om ett stycke är inline. Standard är false. (för pdf‑generering) |
| [get_IsInNewPage](./get_isinnewpage/)() const | Hämtar ett booleskt värde som tvingar detta stycke att genereras på en ny sida. Standard är false. (för pdf‑generering) |
| [get_IsKeptWithNext](./get_iskeptwithnext/)() const | Hämtar ett booleskt värde som indikerar om det aktuella stycket förblir på samma sida tillsammans med nästa stycke. Standard är false. (för pdf‑generering) |
| [get_Margin](./get_margin/)() | Hämtar en yttre marginal för stycket (för pdf‑generering) |
| virtual [get_VerticalAlignment](./get_verticalalignment/)() | Hämtar en vertikal justering av stycket. |
| [get_ZIndex](./get_zindex/)() const | Hämtar ett heltalsvärde som indikerar Z‑ordningen för grafen. En graf med högre ZIndex placeras ovanför en graf med lägre ZIndex. ZIndex kan vara negativt. En graf med negativ ZIndex placeras bakom texten på sidan. |
| virtual [set_HorizontalAlignment](./set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) | Ställer in en horisontell justering av stycket. |
| virtual [set_Hyperlink](./set_hyperlink/)(System::SharedPtr\<Aspose::Pdf::Hyperlink\>) | Ställer in fragmentets hyperlänk (för pdf‑generator). |
| [set_IsFirstParagraphInColumn](./set_isfirstparagraphincolumn/)(bool) | Ställer in ett booleskt värde som indikerar om detta stycke kommer att vara i nästa kolumn. Standard är false. (för pdf‑generering) |
| [set_IsInLineParagraph](./set_isinlineparagraph/)(bool) | Ställer in om ett stycke är inline. Standard är false. (för pdf‑generering) |
| [set_IsInNewPage](./set_isinnewpage/)(bool) | Ställer in ett booleskt värde som tvingar detta stycke att genereras på en ny sida. Standard är false. (för pdf‑generering) |
| [set_IsKeptWithNext](./set_iskeptwithnext/)(bool) | Ställer in ett booleskt värde som indikerar om det aktuella stycket förblir på samma sida tillsammans med nästa stycke. Standard är false. (för pdf‑generering) |
| [set_Margin](./set_margin/)(const System::SharedPtr\<MarginInfo\>\&) | Ställer in en yttre marginal för stycket (för pdf‑generering) |
| virtual [set_VerticalAlignment](./set_verticalalignment/)(Aspose::Pdf::VerticalAlignment) | Ställer in en vertikal justering av stycket. |
| [set_ZIndex](./set_zindex/)(int32_t) | Ställer in ett heltalsvärde som indikerar Z‑ordningen för grafen. En graf med högre ZIndex placeras ovanför en graf med lägre ZIndex. ZIndex kan vara negativt. En graf med negativ ZIndex placeras bakom texten på sidan. |
## Se även

* Class [ICloneable](../../system/icloneable/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
