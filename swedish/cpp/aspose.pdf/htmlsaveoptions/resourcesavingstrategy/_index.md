---
title: "Aspose::Pdf::HtmlSaveOptions::ResourceSavingStrategy typedef"
linktitle: "ResourceSavingStrategy"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::HtmlSaveOptions::ResourceSavingStrategy typedef. Till den här egenskapen kan du tilldela en delegat skapad från en anpassad metod som implementerar bearbetning av en extern resurs (Font eller Image) som extraherades från PDF och måste sparas som extern resurs under konvertering av PDF till HTML. I sådant fall kan bearbetning (som att spara i ström eller på disk) göras i den anpassade koden och den anpassade koden måste returnera en sökväg (eller någon annan sträng utan citattecken) som därefter införlivas i den genererade HTML:n i stället för den ursprungliga antagna sökvägen till den bildresursen. I sådant fall måste alla nödvändiga åtgärder för sparande av bilden utföras i den levererade metodens kod, eftersom sparandet av resultatet i konverterarens kod inte kommer att användas. Om bearbetning för den här eller den där filen av någon anledning måste göras av konverterarens kod själv, inte i anpassad kod, vänligen sätt i den anpassade koden flaggan ''CustomProcessingCancelled'' på variabeln ''resourceSavingInfo''. Den signalerar till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste utföras i konverteraren själv som om ingen extern anpassad kod fanns i C++."
type: docs
weight: 5000
url: /sv/cpp/aspose.pdf/htmlsaveoptions/resourcesavingstrategy/
---
## ResourceSavingStrategy typedef


Till den här egenskapen kan du tilldela en delegat skapad från en anpassad metod som implementerar bearbetning av en extern resurs (teckensnitt eller bild) som extraherades från PDF och måste sparas som extern resurs under konvertering av PDF till HTML. I så fall kan bearbetning (t.ex. sparande till ström eller disk) göras i den anpassade koden och den anpassade koden måste returnera en sökväg (eller någon annan sträng utan citattecken) som därefter införlivas i den genererade HTML‑koden i stället för den ursprungliga antagna sökvägen till bildresursen. I så fall måste alla nödvändiga åtgärder för att spara bilden utföras i den levererade metodens kod, eftersom sparandet av resultatet i konverterarens kod inte kommer att användas. Om bearbetning för denna eller den filen av någon anledning måste göras av konverterarens kod själv, inte i anpassad kod, sätt i den anpassade koden flaggan 'CustomProcessingCancelled' för variabeln 'resourceSavingInfo'. Den signalerar till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste utföras i konverteraren själv som om ingen extern anpassad kod fanns.

```cpp
using Aspose::Pdf::HtmlSaveOptions::ResourceSavingStrategy =  System::MulticastDelegate<System::String(const System::SharedPtr<Aspose::Pdf::SaveOptions::ResourceSavingInfo>&)>
```


## Se även

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
