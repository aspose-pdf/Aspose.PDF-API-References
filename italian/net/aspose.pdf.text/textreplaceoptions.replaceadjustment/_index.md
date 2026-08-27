---
title: "Enum TextReplaceOptions.ReplaceAdjustment"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Enum Aspose.Pdf.Text.TextReplaceOptionsReplaceAdjustment. Determina l'azione da eseguire dopo la sostituzione di un frammento di testo con uno più corto. None - nessuna azione, il testo sostituito può sovrapporsi al resto della riga; AdjustSpaceWidth - tenta di regolare gli spazi tra le parole per mantenere la lunghezza della riga; WholeWordsHyphenation - tenta di distribuire le parole tra le righe del paragrafo per mantenere il campo destro del paragrafo; ShiftRestOfLine - sposta il resto della riga in base alla variazione della lunghezza del testo, la lunghezza della riga può cambiare; Il valore predefinito è ShiftRestOfLine."
type: docs
weight: 11210
url: /it/net/aspose.pdf.text/textreplaceoptions.replaceadjustment/
---
## TextReplaceOptions.ReplaceAdjustment enumeration

Determina l'azione da eseguire dopo la sostituzione di un frammento di testo con uno più corto. None - nessuna azione, il testo sostituito può sovrapporsi al resto della riga; AdjustSpaceWidth - tenta di regolare gli spazi tra le parole per mantenere la lunghezza della riga; WholeWordsHyphenation - tenta di distribuire le parole tra le righe del paragrafo per mantenere il campo destro del paragrafo; ShiftRestOfLine - sposta il resto della riga in base alla variazione della lunghezza del testo, la lunghezza della riga può cambiare; Il valore predefinito è ShiftRestOfLine.

```csharp
[Flags]
public enum ReplaceAdjustment
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | `0` | Nessuna azione, il testo sostituito può sovrapporsi al resto della riga |
| AdjustSpaceWidth | `1` | Cerca di regolare gli spazi tra le parole per mantenere la lunghezza della riga |
| WholeWordsHyphenation | `2` | Cerca di distribuire le parole tra le righe del paragrafo per mantenere il margine destro del paragrafo |
| IsFormFillingMode | `4` | Cerca di distribuire le parole nello spazio bianco disponibile usando la larghezza del paragrafo. Se il testo supera i limiti, verrà nascosto. |
| ShiftRestOfLine | `8` | (Predefinito) Sposta il resto della riga in base alla variazione della lunghezza del testo, la lunghezza della riga può essere modificata |

### Vedi anche

* class [TextReplaceOptions](../textreplaceoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


