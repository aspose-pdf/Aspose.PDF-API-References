---
title: "Aspose::Pdf::Annotations::SubmitFormAction klass"
linktitle: "SubmitFormAction"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::SubmitFormAction klass. Klass som beskriver submit-form‑åtgärd i C++."
type: docs
weight: 11000
url: /sv/cpp/aspose.pdf.annotations/submitformaction/
---
## SubmitFormAction class


Klassen som beskriver submit-form‑åtgärd.

```cpp
class SubmitFormAction : public Aspose::Pdf::Annotations::PdfAction
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Flags](./get_flags/)() | Hämtar flaggor för submit‑åtgärden. |
| [get_Url](./get_url/)() | Destinations‑URL. |
| [set_Flags](./set_flags/)(int32_t) | Ställer in flaggor för submit‑åtgärden. |
| [set_Url](./set_url/)(const System::SharedPtr\<FileSpecification\>\&) | Destinations‑URL. |
| [SubmitFormAction](./submitformaction/)() | Initierar [SubmitFormAction](./)‑objekt. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static constexpr [CanonicalFormat](./canonicalformat/) | Om den är inställd ska alla inskickade fältvärden som representerar datum konverteras till standardformatet. |
| static constexpr [EmbedForm](./embedform/) | Om den är inställd ska F‑posten i den inskickade FDF vara en filspecificering som innehåller ett inbäddat filström som representerar PDF‑filen som FDF‑filen skickas från. |
| static constexpr [ExclFKey](./exclfkey/) | Om den är inställd ska den inskickade FDF exkludera F‑posten. |
| static constexpr [ExclNonUserAnnots](./exclnonuserannots/) | Om den är inställd ska den endast inkludera de markup‑annoteringar vars T‑post matchar namnet på den aktuella användaren. |
| static constexpr [Exclude](./exclude/) | Om den är rensad anger Fields‑arrayen vilka fält som ska inkluderas i inskickningen. |
| static constexpr [ExportFormat](./exportformat/) | Om den är inställd ska fältnamn och -värden skickas i HTML‑formulärformat. |
| static constexpr [GetMethod](./getmethod/) | Om den är inställd ska fältnamn och -värden skickas med en HTTP‑GET‑begäran. |
| static constexpr [IncludeAnnotations](./includeannotations/) | Om den är inställd ska den inskickade FDF‑filen inkludera alla markup‑annoteringar i det underliggande PDF‑dokumentet. |
| static constexpr [IncludeAppendSaves](./includeappendsaves/) | Om den är inställd ska den inskickade FDF‑filen inkludera innehållet i alla inkrementella uppdateringar. |
| static constexpr [IncludeNoValueFields](./includenovaluefields/) | Om den är inställd ska alla fält som anges av Fields‑arrayen och Include/Exclude‑flaggan skickas. |
| static constexpr [SubmitCoordinates](./submitcoordinates/) | Om den är angiven ska koordinaterna för musklicken som orsakade submit-form‑åtgärden överföras som en del av formulärdata. |
| static constexpr [SubmitPdf](./submitpdf/) | Om den är angiven ska dokumentet skickas in som PDF med MIME‑innehållstypen application/pdf. |
| static constexpr [Xfdf](./xfdf/) | Om den är angiven ska fältnamn och värden skickas in som XFDF. |
## Se även

* Class [PdfAction](../pdfaction/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
