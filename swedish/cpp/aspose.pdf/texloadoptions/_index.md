---
title: "Aspose::Pdf::TeXLoadOptions-klass"
linktitle: "TeXLoadOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::TeXLoadOptions-klass. Representerar alternativ för att ladda/importera TeX-fil till PDF-dokument i C++."
type: docs
weight: 18100
url: /sv/cpp/aspose.pdf/texloadoptions/
---
## TeXLoadOptions class


Representerar alternativ för inläsning/import av TeX-fil till PDF-dokument.

```cpp
class TeXLoadOptions : public Aspose::Pdf::LoadOptions
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_DateTime](./get_datetime/)() | Hämtar/sätter ett visst värde för datum/tids‑primitiver som år, månad, dag och tid. |
| [get_InputDirectory](./get_inputdirectory/)() | Hämtar/sätter TeX‑indata‑katalog. |
| [get_JobName](./get_jobname/)() const | Hämtar/sätter namnet på jobbet. |
| [get_NoLigatures](./get_noligatures/)() | Hämtar/sätter en flagga som avbryter ligaturer i alla typsnitt. |
| [get_OutputDirectory](./get_outputdirectory/)() | Hämtar/inställer TeX-utdatakatalog. |
| [get_RasterizeFormulas](./get_rasterizeformulas/)() | Hämtar/inställer en flagga som tillåter att rasterisera matematiska formler. |
| [get_Repeat](./get_repeat/)() | Hämtar/inställer flaggan som indikerar om det är nödvändigt att köra TeX-jobbet två gånger om exempelvis det finns referenser i indata‑TeX‑fil(er). I allmänhet är detta beteende användbart när motorn samlar in data under typografiprocessen och lagrar den i en hjälpfil, allt under den första körningen. Och vid den andra körningen använder motorn på något sätt den datan. |
| [get_RequiredInputDirectory](./get_requiredinputdirectory/)() | Hämtar/inställer TeX kräver indata‑katalog. Krävd indata är de filer som på något sätt inkluderas i huvud‑.tex‑filen, t.ex. paket för vilka det inte finns inbyggt stöd. |
| [get_ShowTerminalOutput](./get_showterminaloutput/)() const | Hämtar/inställer flaggan som indikerar om terminalutdata ska visas i konsolen. |
| [get_SubsetFonts](./get_subsetfonts/)() | Hämtar/inställer flaggan som indikerar om teckensnitt ska delmängdas i utdatafilen eller inte. |
| [GetLoadResult](./getloadresult/)() | Hämtar resultat för TeX‑laddning och kompilering – gick allt smidigt eller fanns det några kommentarer/fel. |
| [set_DateTime](./set_datetime/)(System::DateTime) | Hämtar/sätter ett visst värde för datum/tids‑primitiver som år, månad, dag och tid. |
| [set_InputDirectory](./set_inputdirectory/)(const System::SharedPtr\<ITeXInputDirectory\>\&) | Hämtar/sätter TeX‑indata‑katalog. |
| [set_JobName](./set_jobname/)(const System::String\&) | Hämtar/sätter namnet på jobbet. |
| [set_NoLigatures](./set_noligatures/)(bool) | Hämtar/sätter en flagga som avbryter ligaturer i alla typsnitt. |
| [set_OutputDirectory](./set_outputdirectory/)(const System::SharedPtr\<ITeXOutputDirectory\>\&) | Hämtar/inställer TeX-utdatakatalog. |
| [set_RasterizeFormulas](./set_rasterizeformulas/)(bool) | Hämtar/inställer en flagga som tillåter att rasterisera matematiska formler. |
| [set_Repeat](./set_repeat/)(bool) | Hämtar/inställer flaggan som indikerar om det är nödvändigt att köra TeX-jobbet två gånger om exempelvis det finns referenser i indata‑TeX‑fil(er). I allmänhet är detta beteende användbart när motorn samlar in data under typografiprocessen och lagrar den i en hjälpfil, allt under den första körningen. Och vid den andra körningen använder motorn på något sätt den datan. |
| [set_RequiredInputDirectory](./set_requiredinputdirectory/)(const System::SharedPtr\<ITeXInputDirectory\>\&) | Hämtar/inställer TeX kräver indata‑katalog. Krävd indata är de filer som på något sätt inkluderas i huvud‑.tex‑filen, t.ex. paket för vilka det inte finns inbyggt stöd. |
| [set_ShowTerminalOutput](./set_showterminaloutput/)(bool) | Hämtar/inställer flaggan som indikerar om terminalutdata ska visas i konsolen. |
| [set_SubsetFonts](./set_subsetfonts/)(bool) | Hämtar/inställer flaggan som indikerar om teckensnitt ska delmängdas i utdatafilen eller inte. |
| [TeXLoadOptions](./texloadoptions/)() | Skapar standardladdningsalternativ för konvertering av TeX‑fil till PDF‑dokument. |
## Se även

* Class [LoadOptions](../loadoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
