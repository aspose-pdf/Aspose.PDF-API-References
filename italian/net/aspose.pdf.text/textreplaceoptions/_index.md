---
title: Class TextReplaceOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.TextReplaceOptions. Rappresenta le opzioni di sostituzione del testo
type: docs
weight: 11010
url: /it/net/aspose.pdf.text/textreplaceoptions/
---
## Classe TextReplaceOptions

Rappresenta le opzioni di sostituzione del testo

```csharp
public sealed class TextReplaceOptions : TextOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextReplaceOptions](textreplaceoptions/#constructor)(ReplaceAdjustment) | Inizializza una nuova istanza dell'oggetto `TextReplaceOptions` per l'azione di sostituzione specificata. |
| [TextReplaceOptions](textreplaceoptions/#constructor_1)(Scope) | Inizializza una nuova istanza dell'oggetto `TextReplaceOptions` per l'ambito specificato. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AdjustmentNewLineSpacing](../../aspose.pdf.text/textreplaceoptions/adjustmentnewlinespacing/) { get; set; } | Ottiene o imposta il valore dell'interlinea utilizzato se l'aggiustamento della sostituzione è forzato a creare una nuova riga di testo. Il valore atteso è un moltiplicatore della dimensione del carattere del testo sostituito. Il valore predefinito è 1.2. |
| [IgnoreParagraphs](../../aspose.pdf.text/textreplaceoptions/ignoreparagraphs/) { get; set; } | Ottiene o imposta un valore che indica se ignorare i paragrafi distinti quando si aggiusta il testo sulla pagina dopo la sostituzione del testo. |
| [LeftAdjustment](../../aspose.pdf.text/textreplaceoptions/leftadjustment/) { get; set; } | Imposta o ottiene l'aggiustamento della posizione sinistra per il testo sostituito quando si utilizza TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode; |
| [ReplaceAdjustmentAction](../../aspose.pdf.text/textreplaceoptions/replaceadjustmentaction/) { get; set; } | Ottiene o imposta un'azione che verrà eseguita dopo la sostituzione del frammento di testo con uno più corto. |
| [ReplaceScope](../../aspose.pdf.text/textreplaceoptions/replacescope/) { get; set; } | Ottiene o imposta un ambito in cui viene applicata l'operazione di sostituzione del testo |
| [RightAdjustment](../../aspose.pdf.text/textreplaceoptions/rightadjustment/) { get; set; } | Imposta o ottiene l'aggiustamento della posizione destra per il testo sostituito quando si utilizza TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |

### Vedi Anche

* classe [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)