---
title: Class LoadOptions.ResourceLoadingResult
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LoadOptionsResourceLoadingResult class. Result of custom loading of resource
type: docs
weight: 6150
url: /sv/net/aspose.pdf/loadoptions.resourceloadingresult/
---
## LoadOptions.ResourceLoadingResult klass

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
| [Data](../../aspose.pdf/loadoptions.resourceloadingresult/data) { get; } | Bynära data som laddades med anpassad inläsare - det måste sättas efter inläsning |

## Fält

| Namn | Beskrivning |
| --- | --- |
| [EncodingIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/encodingifknown) | Ibland är kodningen av resursen känd efter eller under inläsning. I sådana fall kan anpassad kod tillhandahålla konverteraren med den kunskapen via denna parameter. Du kan lämna null i denna parameter om kodningen är okänd eller inte spelar någon roll. |
| [ExceptionOfLoadingIfAny](../../aspose.pdf/loadoptions.resourceloadingresult/exceptionofloadingifany) | Ibland är det omöjligt att ladda den begärda resursen av någon anledning. Otillgänglighet av resursen leder ofta inte till krasch av konverteringen och resultatdokumentet kan skapas ändå (men kanske i något sämre kvalitet, utan bilder etc.). Om ett undantag inträffade under inläsning, fånga det bara och lägg i denna parameter - ibland är den informationen användbar för konverteraren för rendering av resultatet. |
| [LoadingCancelled](../../aspose.pdf/loadoptions.resourceloadingresult/loadingcancelled) | Ibland bör inläsning av olika skäl inte ske av anpassad kod. I sådana fall vänligen sätt denna flagga till True. I sådana fall kommer konverteraren att försöka använda den interna standardresursläsaren för att få det resultatet (som den beter sig i situationer när ingen anpassad strategi tillhandahålls). |
| [MIMETypeIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/mimetypeifknown) | Ibland är kunskap om MIME-typen för den inlästa resursen användbar för konverteraren. Du kan tillhandahålla MIME-typ (om den är känd efter inläsning) i denna parameter. Vänligen lämna parametern lika med null när MIME-typen är okänd eller det inte är nödvändigt att tillhandahålla den. |

### Se Även

* klass [LoadOptions](../loadoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)