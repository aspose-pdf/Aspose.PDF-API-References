---
title: "Enum TextEditOptions.NoCharacterAction"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Enum Aspose.Pdf.Text.TextEditOptionsNoCharacterAction. Azione da eseguire se il carattere richiesto non è presente nel font"
type: docs
weight: 11040
url: /it/net/aspose.pdf.text/texteditoptions.nocharacteraction/
---
## TextEditOptions.NoCharacterAction enumeration

Azione da eseguire se il carattere richiesto non è presente nel font

```csharp
public enum NoCharacterAction
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| ThrowException | `0` | Genera eccezione |
| UseStandardFont | `1` | Sostituisci il font con un font standard che contiene il carattere richiesto |
| ReplaceAnyway | `2` | Sostituisci comunque il testo senza sostituzione del font |
| ReplaceFonts | `3` | Sostituisce i font secondo necessità per garantire che tutti i caratteri nel testo possano essere visualizzati. L'algoritmo di sostituzione dei font segue questi passaggi: 1. Se l'utente imposta esplicitamente la proprietà Font, verificare se il font specificato può visualizzare i caratteri desiderati. 2. Se non è impostato alcun font definito dall'utente, cercare tra i font aggiunti tramite i [`Sources`](../fontrepository/sources/). 3. Analizzare il testo per identificare il suo alfabeto o script e suggerire i nomi dei font di conseguenza. Tentare di individuare e utilizzare questi font dal sistema. 4. Come soluzione di ripiego, cercare nel sistema un qualsiasi font in grado di visualizzare i caratteri richiesti. |
| UseCustomReplacementFont | `4` | Sostituisci il font con il font di sostituzione definito |

### Vedi anche

* class [TextEditOptions](../texteditoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


