---
title: "Klass LoadOptions.ResourceLoadingResult"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.LoadOptionsResourceLoadingResult‑klass. Resultat av anpassad inläsning av resurs"
type: docs
weight: 6290
url: /sv/net/aspose.pdf/loadoptions.resourceloadingresult/
---
## LoadOptions.ResourceLoadingResult class

Resultat av anpassad inläsning av resurs

```csharp
public class ResourceLoadingResult
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ResourceLoadingResult](../../aspose.pdf/loadoptions.resourceloadingresult/.ctor)(byte[]) | Skapar en instans av inläsningsresultatet |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Data](../../aspose.pdf/loadoptions.resourceloadingresult/data) { get; } | Binär data som laddats med anpassad laddare – den måste sättas efter inläsning |

## Fält

| Namn | Beskrivning |
| --- | --- |
| [EncodingIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/encodingifknown) | Ibland är kodningen för resursen känd efter eller under inläsning. I så fall kan anpassad kod förse konverteraren med den kunskapen via denna parameter. Du kan lämna null i denna parameter om kodningen är okänd eller inte spelar någon roll. |
| [ExceptionOfLoadingIfAny](../../aspose.pdf/loadoptions.resourceloadingresult/exceptionofloadingifany) | Ibland är det omöjligt att ladda den begärda resursen av någon anledning. Brist på resurs leder ofta inte till att konverteringen kraschar och resultatdokumentet kan ändå skapas (men kanske i något sämre kvalitet, utan bilder osv.). Om ett undantag inträffade under inläsning, fånga det bara och placera det i denna parameter – ibland är den informationen användbar för konverteraren vid rendering av resultatet. |
| [LoadingCancelled](../../aspose.pdf/loadoptions.resourceloadingresult/loadingcancelled) | Ibland bör inläsning inte ske av anpassad kod av vissa skäl. I så fall sätt denna flagga till True. Då kommer konverteraren att försöka använda den interna standardresursladdaren för att få det resultatet (så som den beter sig i en situation när ingen anpassad strategi har angivits). |
| [MIMETypeIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/mimetypeifknown) | Ibland är kunskap om MIME‑typen för den inlästa resursen användbar för konverteraren. Du kan ange MIME‑typen (om den är känd efter inläsning) i denna parameter. Lämna parametern som null när MIME‑typen är okänd eller inte behöver anges. |

### Se även

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


