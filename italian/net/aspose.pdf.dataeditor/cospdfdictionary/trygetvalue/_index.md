---
title: "CosPdfDictionary.TryGetValue"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo CosPdfDictionary. Per l'accesso a tipi di dati semplici come string, name, bool, number. Restituisce null per altri tipi"
type: docs
weight: 170
url: /it/net/aspose.pdf.dataeditor/cospdfdictionary/trygetvalue/
---
## CosPdfDictionary.TryGetValue method

Per l'accesso a tipi di dati semplici come stringa, nome, bool, numero. Restituisce null per altri tipi.

```csharp
public bool TryGetValue(string key, out ICosPdfPrimitive value)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chiave | String | Valore della chiave |
| value | ICosPdfPrimitive& | restituisce [`ICosPdfPrimitive`](../../icospdfprimitive/) per la chiave o null. |

### Valore di ritorno

Restituisce true se [`ICosPdfPrimitive`](../../icospdfprimitive/) è simile a string, name, bool, number. Restituisce false per tutti gli altri tipi.

### Vedi anche

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* class [CosPdfDictionary](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)


