---
title: Enum TextReplaceOptions.ReplaceAdjustment
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextReplaceOptionsReplaceAdjustment enum. Determina l'azione che verrà eseguita dopo la sostituzione di un frammento di testo con uno più corto. Nessuna - nessuna azione, il testo sostituito può sovrapporsi al resto della riga; RegolaSpazioLarghezza - cerca di regolare gli spazi tra le parole per mantenere la lunghezza della riga; DivisioneParoleIntere - cerca di distribuire le parole tra le righe del paragrafo per mantenere il campo destro del paragrafo; SpostaRestoDellaRiga - sposta il resto della riga in base alla variazione della lunghezza del testo, la lunghezza della riga può essere cambiata; Il valore predefinito è SpostaRestoDellaRiga.
type: docs
weight: 11020
url: /it/net/aspose.pdf.text/textreplaceoptions.replaceadjustment/
---
## Enumerazione TextReplaceOptions.ReplaceAdjustment

Determina l'azione che verrà eseguita dopo la sostituzione di un frammento di testo con uno più corto. Nessuna - nessuna azione, il testo sostituito può sovrapporsi al resto della riga; RegolaSpazioLarghezza - cerca di regolare gli spazi tra le parole per mantenere la lunghezza della riga; DivisioneParoleIntere - cerca di distribuire le parole tra le righe del paragrafo per mantenere il campo destro del paragrafo; SpostaRestoDellaRiga - sposta il resto della riga in base alla variazione della lunghezza del testo, la lunghezza della riga può essere cambiata; Il valore predefinito è SpostaRestoDellaRiga.

```csharp
[Flags]
public enum ReplaceAdjustment
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Nessuna | `0` | Nessuna azione, il testo sostituito può sovrapporsi al resto della riga |
| RegolaSpazioLarghezza | `1` | Cerca di regolare gli spazi tra le parole per mantenere la lunghezza della riga |
| DivisioneParoleIntere | `2` | Cerca di distribuire le parole tra le righe del paragrafo per mantenere il campo destro del paragrafo |
| IsFormFillingMode | `4` | Cerca di distribuire le parole nello spazio bianco disponibile utilizzando la larghezza del paragrafo. Se il testo trabocca, verrà nascosto. |
| SpostaRestoDellaRiga | `8` | (Predefinito) Sposta il resto della riga in base alla variazione della lunghezza del testo, la lunghezza della riga può essere cambiata |

### Vedi Anche

* classe [TextReplaceOptions](../textreplaceoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)