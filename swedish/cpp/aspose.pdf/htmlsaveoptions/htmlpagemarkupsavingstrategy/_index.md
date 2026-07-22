---
title: "Aspose::Pdf::HtmlSaveOptions::HtmlPageMarkupSavingStrategy typedef"
linktitle: "HtmlPageMarkupSavingStrategy"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::HtmlSaveOptions::HtmlPageMarkupSavingStrategy typedef. Resultatet av konverteringen kan innehålla en eller flera HTML‑sidor (som också kan referera till externa filer som bilder eller teckensnitt). Du kan tilldela den här egenskapen en delegat skapad från en anpassad metod som implementerar bearbetning av den genererade HTML‑sidan (HTML‑innehållet) som skapades under konverteringen. I sådant fall kan bearbetning (t.ex. sparande till ström eller disk) göras i den anpassade koden. I sådant fall måste alla nödvändiga åtgärder för att spara HTML‑sidans markup utföras i den levererade metodens kod, eftersom sparandet av resultatet i konverterarens kod inte kommer att användas. Om bearbetning för detta eller annat fall av någon anledning måste utföras av konverterarens egen kod, inte i anpassad kod, sätt i den anpassade koden flaggan ''CustomProcessingCancelled'' på variabeln ''htmlSavingInfo''‑parameter: den signalerar till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste göras i konverteraren själv på samma sätt som om ingen extern anpassad sparkod fanns i C++."
type: docs
weight: 4900
url: /sv/cpp/aspose.pdf/htmlsaveoptions/htmlpagemarkupsavingstrategy/
---
## HtmlPageMarkupSavingStrategy typedef


Resultatet av konverteringen kan innehålla en eller flera HTML‑sidor (som också kan referera till externa filer som bilder eller teckensnitt). Du kan tilldela den här egenskapen en delegat skapad från en anpassad metod som implementerar bearbetning av den erhållna HTML‑sidan (HTML‑innehållet) som skapades under konverteringen. I så fall kan bearbetning (t.ex. sparande till ström eller disk) göras i den anpassade koden. I så fall måste alla nödvändiga åtgärder för att spara HTML‑sidans markup utföras i den levererade metodens kod, eftersom sparandet av resultatet i konverterarens kod inte kommer att användas. Om bearbetning för detta eller det fallet av någon anledning måste göras av konverterarens kod själv, inte i anpassad kod, sätt i den anpassade koden flaggan 'CustomProcessingCancelled' för variabeln 'htmlSavingInfo' : den signalerar till konverteraren att alla nödvändiga steg för bearbetning av den resursen måste utföras i konverteraren själv på samma sätt som om ingen extern anpassad sparkod fanns.

```cpp
using Aspose::Pdf::HtmlSaveOptions::HtmlPageMarkupSavingStrategy =  System::MulticastDelegate<void(const System::SharedPtr<Aspose::Pdf::HtmlSaveOptions::HtmlPageMarkupSavingInfo>&)>
```


## Se även

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
