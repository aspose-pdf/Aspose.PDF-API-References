---
title: "Aspose::Pdf::SvgSaveOptions::EmbeddedImagesSavingStrategy typedef"
linktitle: "EmbeddedImagesSavingStrategy"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::SvgSaveOptions::EmbeddedImagesSavingStrategy typedef. Till egenskap av sådan typ kan du tilldela en delegat skapad från en anpassad metod som implementerar bearbetning av extern sparning av bild som extraherats från SVG skapad från PDF och måste sparas som extern resurs under konvertering av PDF till HTML. I sådant fall kan bearbetning (t.ex. egen sparning till ström eller på disk) göras i den anpassade koden och den anpassade koden måste returnera en sökväg (eller någon annan sträng utan citattecken) som därefter införlivas i den genererade SVG:n istället för den ursprungliga antagna sökvägen till bildresursen. I sådant fall måste alla nödvändiga åtgärder för sparning av bilden utföras i den levererade metodens kod, eftersom sparning av resultatet i konverterarens kod inte kommer att användas. Om bearbetning för denna eller den filen av någon anledning måste göras av konverterarens kod själv, inte i anpassad kod, vänligen sätt i den anpassade koden flaggan ''CustomProcessingCancelled'' på variabeln för ''imageSavingInfo''‑parametern. Den signalerar till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste göras i konverteraren själv som om ingen extern anpassad kod fanns i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.pdf/svgsaveoptions/embeddedimagessavingstrategy/
---
## EmbeddedImagesSavingStrategy typedef


Till en egenskap av sådan typ kan du tilldela en delegat skapad från en anpassad metod som implementerar bearbetning av extern sparning av en bild som extraherades från SVG skapad från PDF och måste sparas som extern resurs under konvertering av PDF till HTML. I sådant fall kan bearbetning (t.ex. egen sparning till ström eller på disk) göras i den anpassade koden och den anpassade koden måste returnera en sökväg (eller någon annan sträng utan citattecken) som därefter införlivas i den genererade SVG:n istället för den ursprungliga antagna sökvägen till bildresursen. I sådant fall måste alla nödvändiga åtgärder för att spara bilden utföras i den levererade metodens kod, eftersom sparning av resultatet i konverterarens kod inte kommer att användas. Om bearbetning för denna eller den filen av någon anledning måste göras av konverterarens kod själv, inte i anpassad kod, vänligen sätt i den anpassade koden flaggan 'CustomProcessingCancelled' på variabeln 'imageSavingInfo' för parametern. Den signalerar till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste utföras i konverteraren själv som om ingen extern anpassad kod fanns.

```cpp
using Aspose::Pdf::SvgSaveOptions::EmbeddedImagesSavingStrategy =  System::MulticastDelegate<System::String(const System::SharedPtr<Aspose::Pdf::SvgSaveOptions::SvgImageSavingInfo>&)>
```

## Se även

* Class [SvgSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
