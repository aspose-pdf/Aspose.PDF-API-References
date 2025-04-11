---
title: DictionaryEditor.Remove
second_title: Aspose.PDF for .NET API Reference
description: Metodo DictionaryEditor. Rimuove l'elemento con la chiave specificata dal DictionaryEditor
type: docs
weight: 140
url: /it/net/aspose.pdf.dataeditor/dictionaryeditor/remove/
---
## Remove(string) {#remove_1}

Rimuove l'elemento con la chiave specificata dal [`DictionaryEditor`](../).

```csharp
public bool Remove(string key)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | String | La chiave dell'elemento da rimuovere. |

### Valore di ritorno

True se l'elemento è stato rimosso con successo; altrimenti, false. Questo metodo restituisce anche false se la chiave non è stata trovata nel dizionario originale o se la chiave non è modificabile.

### Vedi anche

* classe [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) {#remove}

Rimuove la prima occorrenza di un oggetto specifico dal [`DictionaryEditor`](../).

```csharp
public bool Remove(KeyValuePair<string, ICosPdfPrimitive> item)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | KeyValuePair`2 | L'oggetto da rimuovere dal [`DictionaryEditor`](../). |

### Valore di ritorno

true se l'item è stato rimosso con successo dal [`DictionaryEditor`](../); altrimenti, false. Questo metodo restituisce anche false se l'item non è trovato nel [`DictionaryEditor`](../) originale.

### Vedi anche

* interfaccia [ICosPdfPrimitive](../../icospdfprimitive/)
* classe [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)