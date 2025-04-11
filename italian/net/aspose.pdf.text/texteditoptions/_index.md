---
title: Class TextEditOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextEditOptions class. Descubes options of text edit operations
type: docs
weight: 10820
url: /it/net/aspose.pdf.text/texteditoptions/
---
## Classe TextEditOptions

Scopre le opzioni delle operazioni di modifica del testo.

```csharp
public sealed class TextEditOptions : TextOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextEditOptions](texteditoptions/#constructor)(bool) | Inizializza una nuova istanza dell'oggetto `TextEditOptions` per il permesso di trasformazione della lingua specificato. |
| [TextEditOptions](texteditoptions/#constructor_1)(FontReplace) | Inizializza una nuova istanza dell'oggetto `TextEditOptions` per la modalità di comportamento di sostituzione del font specificata. |
| [TextEditOptions](texteditoptions/#constructor_2)(LanguageTransformation) | Inizializza una nuova istanza dell'oggetto `TextEditOptions` per la modalità di comportamento di trasformazione della lingua specificata. |
| [TextEditOptions](texteditoptions/#constructor_3)(NoCharacterAction) | Inizializza una nuova istanza dell'oggetto `TextEditOptions` per la modalità di comportamento senza carattere specificata. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AllowLanguageTransformation](../../aspose.pdf.text/texteditoptions/allowlanguagetransformation/) { get; set; } | Ottiene o imposta il valore che consente l'uso della trasformazione della lingua durante l'aggiunta o la modifica del testo. true - la trasformazione della lingua sarà applicata se necessario (valore predefinito). false - la trasformazione della lingua NON sarà applicata. |
| [ClippingPathsProcessing](../../aspose.pdf.text/texteditoptions/clippingpathsprocessing/) { get; set; } | Ottiene la modalità per l'elaborazione del percorso di ritaglio del testo modificato. |
| [FontReplaceBehavior](../../aspose.pdf.text/texteditoptions/fontreplacebehavior/) { get; set; } | Ottiene la modalità che definisce il comportamento per gli scenari di sostituzione dei font. |
| [LanguageTransformationBehavior](../../aspose.pdf.text/texteditoptions/languagetransformationbehavior/) { get; set; } | Ottiene la modalità che definisce il comportamento per gli scenari di trasformazione della lingua. |
| [NoCharacterBehavior](../../aspose.pdf.text/texteditoptions/nocharacterbehavior/) { get; set; } | Ottiene o imposta la modalità che definisce il comportamento nel caso in cui i font non contengano i caratteri richiesti. |
| [ReplacementFont](../../aspose.pdf.text/texteditoptions/replacementfont/) { get; set; } | Ottiene o imposta il font utilizzato per la sostituzione se il font dell'utente non contiene il carattere richiesto. |
| [ToAttemptGetUnderlineFromSource](../../aspose.pdf.text/texteditoptions/toattemptgetunderlinefromsource/) { get; set; } | Ottiene o imposta il valore che consente di cercare la sottolineatura del testo nella pagina del documento sorgente. (Obsoleto) Si prega di utilizzare TextSearchOptions.SearchForTextRelatedGraphics invece di questo. |

### Vedi Anche

* classe [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)