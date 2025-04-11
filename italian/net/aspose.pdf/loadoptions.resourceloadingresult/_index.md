---
title: Class LoadOptions.ResourceLoadingResult
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LoadOptionsResourceLoadingResult class. Result of custom loading of resource
type: docs
weight: 6150
url: /it/net/aspose.pdf/loadoptions.resourceloadingresult/
---
## LoadOptions.ResourceLoadingResult class

Risultato del caricamento personalizzato della risorsa

```csharp
public class ResourceLoadingResult
```

## Constructors

| Name | Description |
| --- | --- |
| [ResourceLoadingResult](../../aspose.pdf/loadoptions.resourceloadingresult/.ctor)(byte[]) | Crea un'istanza del risultato di caricamento |

## Properties

| Name | Description |
| --- | --- |
| [Data](../../aspose.pdf/loadoptions.resourceloadingresult/data) { get; } | Dati binari caricati con il caricatore personalizzato - devono essere impostati dopo il caricamento |

## Fields

| Name | Description |
| --- | --- |
| [EncodingIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/encodingifknown) | A volte la codifica della risorsa è nota dopo o durante il caricamento. In tal caso, il codice personalizzato può fornire un convertitore con tale conoscenza tramite questo parametro. Puoi lasciare null in questo parametro se la codifica è sconosciuta o non importa. |
| [ExceptionOfLoadingIfAny](../../aspose.pdf/loadoptions.resourceloadingresult/exceptionofloadingifany) | A volte è impossibile caricare la risorsa richiesta per qualche motivo. L'indisponibilità della risorsa spesso non porta a un crash della conversione e il documento risultante può essere creato comunque (ma forse in una qualità leggermente peggiore, senza immagini, ecc.). Se si è verificata un'eccezione durante il caricamento, basta catturarla e metterla in questo parametro - a volte queste informazioni sono utili per il convertitore per il rendering del risultato. |
| [LoadingCancelled](../../aspose.pdf/loadoptions.resourceloadingresult/loadingcancelled) | A volte, per qualche motivo, il caricamento non dovrebbe avvenire nel codice personalizzato. In tal caso, si prega di impostare questo flag su True. In tal caso, il convertitore cercherà di utilizzare il caricatore di risorse predefinito interno per ottenere quel risultato (come si comporta in situazioni in cui non è fornita una strategia personalizzata). |
| [MIMETypeIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/mimetypeifknown) | A volte la conoscenza del tipo MIME della risorsa caricata è utile per il convertitore. Puoi fornire il tipo MIME (se noto dopo il caricamento) in questo parametro. Si prega di lasciare il parametro uguale a null quando il tipo MIME è sconosciuto o non è necessario fornirlo. |

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)