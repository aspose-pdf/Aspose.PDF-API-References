---
title: CosPdfDictionary.Item
second_title: Aspose.PDF for .NET API Reference
description: Proprietà CosPdfDictionary. Ottiene o imposta l'elemento con la chiave specificata
type: docs
weight: 60
url: /it/net/aspose.pdf.dataeditor/cospdfdictionary/item/
---
## Indicizzatore CosPdfDictionary

Ottiene o imposta l'elemento con la chiave specificata.

```csharp
public ICosPdfPrimitive this[string key] { get; set; }
```

| Parametro | Descrizione |
| --- | --- |
| key | La chiave dell'elemento da ottenere o impostare. |

### Valore di Ritorno

L'elemento con la chiave specificata.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | La chiave è nulla. |
| KeyNotFoundException | La proprietà viene recuperata e la chiave non viene trovata. |
| ArgumentException | Solleva un'eccezione se la chiave non può essere modificata/impostata. |

### Vedi Anche

* interfaccia [ICosPdfPrimitive](../../icospdfprimitive/)
* classe [CosPdfDictionary](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)