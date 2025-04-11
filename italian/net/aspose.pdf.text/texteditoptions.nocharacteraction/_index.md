---
title: Enum TextEditOptions.NoCharacterAction
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextEditOptionsNoCharacterAction enum. Action to perform if font does not contain required character
type: docs
weight: 10860
url: /it/net/aspose.pdf.text/texteditoptions.nocharacteraction/
---
## Enumerazione TextEditOptions.NoCharacterAction

Azione da eseguire se il font non contiene il carattere richiesto

```csharp
public enum NoCharacterAction
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| ThrowException | `0` | Genera un'eccezione |
| UseStandardFont | `1` | Sostituisci il font con un font standard che contiene il carattere richiesto |
| ReplaceAnyway | `2` | Sostituisci il testo comunque senza sostituzione del font |
| ReplaceFonts | `3` | Sostituisce i font secondo necessità per garantire che tutti i caratteri nel testo possano essere visualizzati. L'algoritmo di sostituzione del font segue questi passaggi: 1. Se l'utente imposta esplicitamente la proprietà Font, controlla se il font specificato può visualizzare i caratteri desiderati. 2. Se non è impostato alcun font definito dall'utente, cerca tra i font aggiunti tramite i [`Sources`](../fontrepository/sources/). 3. Analizza il testo per identificare il suo alfabeto o script e suggerisci i nomi dei font di conseguenza. Tenta di localizzare e utilizzare questi font dal sistema. 4. Come fallback, cerca nel sistema qualsiasi font in grado di visualizzare i caratteri richiesti. |
| UseCustomReplacementFont | `4` | Sostituisci il font con il font di sostituzione definito |

### Vedi Anche

* classe [TextEditOptions](../texteditoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)