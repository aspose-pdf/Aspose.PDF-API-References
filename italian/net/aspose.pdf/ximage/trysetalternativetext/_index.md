---
title: "XImage.TrySetAlternativeText"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo XImage. Imposta il testo alternativo per un XImage nella pagina"
type: docs
weight: 180
url: /it/net/aspose.pdf/ximage/trysetalternativetext/
---
## XImage.TrySetAlternativeText method

Imposta il testo alternativo per un XImage nella pagina.

```csharp
public bool TrySetAlternativeText(string alternativeText, Page page)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| alternativeText | String | Il testo alternativo da specificare. |
| pagina | Page | Pagina in cui si trova XImage. |

### Valore di ritorno

True se alternativeText per XImage è impostato. False se alternativeText per XImage non è impostato.

## Osservazioni

Il metodo restituisce false nei seguenti casi: - XImage non è trovato nella pagina specificata. - XImage appare più volte nella pagina con diversi elementi strutturali, rendendo ambiguo quale istanza debba ricevere il testo alternativo.

### Vedi anche

* class [Page](../../page/)
* class [XImage](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


