---
title: DictionaryEditor.TryGetValue
second_title: Aspose.PDF for .NET API Reference
description: Metodo DictionaryEditor. Per l'accesso a tipi di dati semplici come stringa, nome, bool, numero. Restituisce null per altri tipi
type: docs
weight: 150
url: /it/net/aspose.pdf.dataeditor/dictionaryeditor/trygetvalue/
---
## Metodo DictionaryEditor.TryGetValue

Per l'accesso a tipi di dati semplici come stringa, nome, bool, numero. Restituisce null per altri tipi.

```csharp
public bool TryGetValue(string key, out ICosPdfPrimitive value)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | String | Valore della chiave |
| value | ICosPdfPrimitive& | restituisce [`ICosPdfPrimitive`](../../icospdfprimitive/) per la chiave o null. |

### Valore di ritorno

Restituisce true se [`ICosPdfPrimitive`](../../icospdfprimitive/) è come stringa, nome, bool, numero. Restituisce false per tutti gli altri tipi.

### Vedi anche

* interfaccia [ICosPdfPrimitive](../../icospdfprimitive/)
* classe [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)