---
title: "Aspose::Pdf::PsLoadOptions class"
linktitle: "PsLoadOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::PsLoadOptions class. Representerar alternativ för inläsning/import av .mht‑fil till pdf‑dokument i C++."
type: docs
weight: 16100
url: /sv/cpp/aspose.pdf/psloadoptions/
---
## PsLoadOptions class


Representerar alternativ för inläsning/import av .mht-fil till pdf-dokument.

```cpp
class PsLoadOptions : public Aspose::Pdf::LoadOptions
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_ConvertFontsToTTF](./get_convertfontstottf/)() const | Anger om icke‑TrueType‑typsnitt ska sparas som TTF. Det minskar avsevärt volymen på det resulterande dokumentet vid PS‑till‑PDF‑konvertering och ökar konverteringshastigheten för PS‑filer med en stor mängd text i icke‑TrueType‑typsnitt till vilket output‑format som helst. Däremot uppstår en liten vertikal förskjutning av texten när PostSctipt‑fil konverteras till bild. |
| [get_FontsFolders](./get_fontsfolders/)() const | Hämtar sökvägar till teckensnittsmappar. |
| [PsLoadOptions](./psloadoptions/)() | Skapar inläsningsalternativ för konvertering av PostScript till pdf‑dokument med tom bas‑sökväg. |
| [set_ConvertFontsToTTF](./set_convertfontstottf/)(bool) | Anger om icke‑TrueType‑typsnitt ska sparas som TTF. Det minskar avsevärt volymen på det resulterande dokumentet vid PS‑till‑PDF‑konvertering och ökar konverteringshastigheten för PS‑filer med en stor mängd text i icke‑TrueType‑typsnitt till vilket output‑format som helst. Däremot uppstår en liten vertikal förskjutning av texten när PostSctipt‑fil konverteras till bild. |
| [set_FontsFolders](./set_fontsfolders/)(const System::ArrayPtr\<System::String\>\&) | Ställer in sökvägar till teckensnittsmappar. |
## Se även

* Class [LoadOptions](../loadoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
