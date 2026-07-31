---
title: "Classe TextReplaceOptions"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Text.TextReplaceOptions. Rappresenta le opzioni di sostituzione del testo"
type: docs
weight: 11190
url: /it/net/aspose.pdf.text/textreplaceoptions/
---
## TextReplaceOptions class

Rappresenta le opzioni di sostituzione del testo

```csharp
public sealed class TextReplaceOptions : TextOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextReplaceOptions](textreplaceoptions/#constructor)(ReplaceAdjustment) | Inizializza una nuova istanza dell'oggetto `TextReplaceOptions` per l'azione specificata dopo la sostituzione. |
| [TextReplaceOptions](textreplaceoptions/#constructor_1)(Scope) | Inizializza una nuova istanza dell'oggetto `TextReplaceOptions` per l'ambito specificato. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AdjustmentNewLineSpacing](../../aspose.pdf.text/textreplaceoptions/adjustmentnewlinespacing/) { get; set; } | Ottiene o imposta il valore dell'interlinea utilizzata se la regolazione della sostituzione è forzata a creare una nuova riga di testo. Il valore previsto è un moltiplicatore della dimensione del carattere del testo sostituito. Il valore predefinito è 1,2. |
| [FontSizeAdjustmentAction](../../aspose.pdf.text/textreplaceoptions/fontsizeadjustmentaction/) { get; set; } | Ottiene o imposta la politica per regolare la dimensione del carattere in modo da adattarsi ai limiti definiti dal [`Rectangle`](./rectangle/). |
| [IgnoreParagraphs](../../aspose.pdf.text/textreplaceoptions/ignoreparagraphs/) { get; set; } | Ottiene o imposta un valore che indica se ignorare paragrafi distinti durante la regolazione del testo nella pagina dopo la sostituzione del testo. |
| [LeftAdjustment](../../aspose.pdf.text/textreplaceoptions/leftadjustment/) { get; set; } | Imposta o ottiene la regolazione della posizione sinistra per il testo sostituito quando si utilizza TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode; |
| [Rectangle](../../aspose.pdf.text/textreplaceoptions/rectangle/) { get; set; } | Ottiene o imposta il rettangolo per adattare il testo dopo la sostituzione. |
| [ReplaceAdjustmentAction](../../aspose.pdf.text/textreplaceoptions/replaceadjustmentaction/) { get; set; } | Ottiene o imposta un'azione che verrà eseguita dopo la sostituzione di un frammento di testo per renderlo più breve. |
| [ReplaceScope](../../aspose.pdf.text/textreplaceoptions/replacescope/) { get; set; } | Ottiene o imposta l'ambito in cui viene applicata l'operazione di sostituzione del testo |
| [RightAdjustment](../../aspose.pdf.text/textreplaceoptions/rightadjustment/) { get; set; } | Imposta o ottiene la regolazione della posizione destra per il testo sostituito quando si utilizza TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |

### Vedi anche

* class [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


