---
title: LoadOptions.DisableFontLicenseVerifications
second_title: Aspose.PDF for .NET API Reference
description: Proprietà LoadOptions. Ottiene o imposta un flag per disabilitare eventuali restrizioni di licenza per tutti i font durante il caricamento del file. Quando è vero, consente di eseguire operazioni con font che sono vietate da una licenza di questo font, ad esempio consente di incorporare un font in un documento PDF anche se le regole di licenza disabilitano l'incorporamento per questo font. Per impostazione predefinita falso
type: docs
weight: 10
url: /it/net/aspose.pdf/loadoptions/disablefontlicenseverifications/
---
## Proprietà LoadOptions.DisableFontLicenseVerifications

Ottiene o imposta un flag per disabilitare eventuali restrizioni di licenza per tutti i font durante il caricamento del file. Quando `true`, consente di eseguire operazioni con font che sono vietate da una licenza di questo font, ad esempio consente di incorporare un font in un documento PDF anche se le regole di licenza disabilitano l'incorporamento per questo font. Per impostazione predefinita `false`.

```csharp
public bool DisableFontLicenseVerifications { get; set; }
```

## Osservazioni

Fai attenzione quando usi questo flag. Quando è impostato, significa che la persona che imposta questo flag si assume tutta la responsabilità di eventuali violazioni di licenza/legge. Quindi se lo assume a proprio rischio. È fortemente consigliato utilizzare questo flag solo quando si è completamente certi di non violare la legge sul copyright.

### Vedi Anche

* classe [LoadOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)