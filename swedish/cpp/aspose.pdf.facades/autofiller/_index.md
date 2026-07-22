---
title: "Aspose::Pdf::Facades::AutoFiller class"
linktitle: "AutoFiller"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::AutoFiller class. Representerar en klass som tar emot data från en databas eller annan datakälla, fyller dem i de designade fälten i mall‑pdf‑filen och slutligen genererar en ny pdf‑fil eller ström. Den har två indata‑lägen för mallfilen: inmatning som en ström eller en pdf‑fil. Den har fyra typer av utdata‑lägen: en sammanslagen ström, en sammanslagen fil, många små strömmar, många små filer. Den kan ta emot litterala data som finns i ett System.Data.DataTable i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.facades/autofiller/
---
## AutoFiller class


Representerar en klass som tar emot data från en databas eller annan datakälla, fyller dem i de designade fälten i mall‑pdf‑filen och slutligen genererar en ny pdf‑fil eller ström. Den har två indata‑lägen för mallfilen: inmatning som en ström eller en pdf‑fil. Den har fyra typer av utdata‑lägen: en sammanslagen ström, en sammanslagen fil, många små strömmar, många små filer. Den kan ta emot litterala data som finns i ett [System.Data.DataTable](../../system.data/datatable/).

```cpp
class AutoFiller : public Aspose::Pdf::Facades::ISaveableFacade
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AutoFiller](./autofiller/)() |  |
| [BindPdf](./bindpdf/)(System::String) override | Binder en [Pdf](../../aspose.pdf/) fil. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<System::IO::Stream\>) override | Binder en [Pdf](../../aspose.pdf/) fil. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<Document\>) override | Binder ett [Pdf](../../aspose.pdf/) dokument. |
| [Close](./close/)() override | Stänger objektet och utdata‑strömmarna. |
| [Dispose](./dispose/)() override | Stänger objektet och utdata‑strömmarna. |
| [get_BasicFileName](./get_basicfilename/)() const | Hämtar det grundläggande filnamnet om många små filer ska genereras. Den genererade filen kommer att vara som "BasicFileName0","BasicFileName1",... Den fungerar tillsammans med egenskapen [GeneratingPath](../)GeneratingPath. |
| [get_GeneratingPath](./get_generatingpath/)() const | Hämtar den genererande sökvägen för de små pdf‑filerna om många små pdf‑filer ska genereras. Den fungerar tillsammans med egenskapen [BasicFileName](../)BasicFileName. Ett av de fyra utdata‑lägena. |
| [get_InputFileName](./get_inputfilename/)() const | Hämtar inmatningsmallfilen. Ett av två indata‑lägen. |
| [get_InputStream](./get_inputstream/)() const | Hämtar inmatningsmallströmmen. Ett av två indata‑lägen. |
| [get_OutputFileName](./get_outputfilename/)() const | Hämtar den enda stora sammanslagna utdatafilen. Ett av de fyra utdata‑lägena. |
| [get_OutputStream](./get_outputstream/)() const | Hämtar OutputStream. Ett av fyra utdata‑lägen. Dess klassiska användningsfall är Response.OutputStream. Se den online‑demonstrationen. |
| [get_OutputStreams](./get_outputstreams/)() const | Hämtar de många Output‑strömmarna. Ett av fyra utdata‑lägen. |
| [Save](./save/)() | Sparar alla pdf‑filerna. |
| [Save](./save/)(System::String) override | Sparar alla pdf‑filerna. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>) override | Sparar alla pdf‑filerna. |
| [set_BasicFileName](./set_basicfilename/)(const System::String\&) | Ställer in det grundläggande filnamnet om många små filer ska genereras. Den genererade filen kommer att vara som "BasicFileName0","BasicFileName1",... Det fungerar med en annan egenskap [GeneratingPath](../)GeneratingPath. |
| [set_GeneratingPath](./set_generatingpath/)(const System::String\&) | Ställer in den genererande sökvägen för de små pdf-filerna om många små pdf-filer ska genereras. Det fungerar med en annan egenskap [BasicFileName](../)BasicFileName. Ett av de fyra utmatningslägena. |
| [set_InputFileName](./set_inputfilename/)(const System::String\&) | Ställer in inmatningsmallfilen. Ett av två inmatningslägen. |
| [set_InputStream](./set_inputstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Ställer in inmatningsmallströmmen. Ett av två inmatningslägen. |
| [set_OutputFileName](./set_outputfilename/)(const System::String\&) | Ställer in den enda stora sammanslagna utdatafilen. Ett av de fyra utmatningslägena. |
| [set_OutputStream](./set_outputstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Ställer in OutputStream. Ett av fyra utmatningslägen. Dess klassiska användningsfall är Response.OutputStream. Se den online‑demonstrationen. |
| [set_OutputStreams](./set_outputstreams/)(const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\&) | Ställer in de många Output Streams. Ett av fyra utmatningslägen. |
| [set_UnFlattenFields](./set_unflattenfields/)(const System::ArrayPtr\<System::String\>\&) | Ställer in fälten som inte ska plattas ut. Om denna egenskap inte är inställd, kommer alla fält att plattas ut. |
## Se även

* Class [ISaveableFacade](../isaveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
