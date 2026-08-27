---
title: "Classe LoadOptions.ResourceLoadingResult"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.LoadOptionsResourceLoadingResult. Risultato del caricamento personalizzato della risorsa"
type: docs
weight: 6290
url: /it/net/aspose.pdf/loadoptions.resourceloadingresult/
---
## LoadOptions.ResourceLoadingResult class

Risultato del caricamento personalizzato della risorsa

```csharp
public class ResourceLoadingResult
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ResourceLoadingResult](../../aspose.pdf/loadoptions.resourceloadingresult/.ctor)(byte[]) | Crea un'istanza del risultato del caricamento |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Data](../../aspose.pdf/loadoptions.resourceloadingresult/data) { get; } | Dati binari caricati con il loader personalizzato - devono essere impostati dopo il caricamento |

## Campi

| Nome | Descrizione |
| --- | --- |
| [EncodingIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/encodingifknown) | A volte la codifica della risorsa è nota dopo o durante il caricamento. In tal caso il codice personalizzato può fornire al convertitore tale conoscenza tramite questo parametro. È possibile lasciare null in questo parametro se la codifica è sconosciuta o non è rilevante. |
| [ExceptionOfLoadingIfAny](../../aspose.pdf/loadoptions.resourceloadingresult/exceptionofloadingifany) | A volte è impossibile caricare la risorsa richiesta per qualche motivo. L'indisponibilità della risorsa spesso non porta al crash del converter e il Document risultato può essere creato comunque (ma forse con una qualità leggermente inferiore, senza immagini ecc.). Se si verifica un'eccezione durante il caricamento, basta catturarla e inserirla in questo parametro - a volte queste informazioni sono utili al converter per il rendering del risultato. |
| [LoadingCancelled](../../aspose.pdf/loadoptions.resourceloadingresult/loadingcancelled) | A volte per alcune ragioni il caricamento non dovrebbe avvenire tramite codice personalizzato. In tal caso impostare questo flag a True. In tal caso il converter proverà a utilizzare il loader di risorse interno predefinito per ottenere quel risultato (come si comporta nella situazione in cui non è fornita una strategia personalizzata). |
| [MIMETypeIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/mimetypeifknown) | A volte la conoscenza del tipo MIME della risorsa caricata è utile al converter. È possibile fornire il tipo MIME (se conosciuto dopo il caricamento) in questo parametro. Si prega di lasciare il parametro uguale a null quando il tipo MIME è sconosciuto o non è necessario fornirlo. |

### Vedi anche

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


