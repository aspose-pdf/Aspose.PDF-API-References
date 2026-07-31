---
title: "Classe TextEditOptions"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Text.TextEditOptions. Descrive le opzioni delle operazioni di modifica del testo."
type: docs
weight: 11000
url: /it/net/aspose.pdf.text/texteditoptions/
---
## TextEditOptions class

Descrive le opzioni delle operazioni di modifica del testo.

```csharp
public sealed class TextEditOptions : TextOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextEditOptions](texteditoptions/#constructor)(bool) | Inizializza una nuova istanza dell'oggetto `TextEditOptions` per l'autorizzazione specificata alla trasformazione della lingua. |
| [TextEditOptions](texteditoptions/#constructor_1)(FontReplace) | Inizializza una nuova istanza dell'oggetto `TextEditOptions` per la modalità di comportamento di sostituzione dei caratteri specificata. |
| [TextEditOptions](texteditoptions/#constructor_2)(LanguageTransformation) | Inizializza una nuova istanza dell'oggetto `TextEditOptions` per la modalità di comportamento della trasformazione linguistica specificata. |
| [TextEditOptions](texteditoptions/#constructor_3)(NoCharacterAction) | Inizializza una nuova istanza dell'oggetto `TextEditOptions` per la modalità di comportamento senza caratteri specificata. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AllowLanguageTransformation](../../aspose.pdf.text/texteditoptions/allowlanguagetransformation/) { get; set; } | Ottiene o imposta il valore che consente l'uso della trasformazione linguistica durante l'aggiunta o la modifica del testo. true - la trasformazione linguistica verrà applicata se necessario (valore predefinito). false - la trasformazione linguistica NON verrà applicata. |
| [ClippingPathsProcessing](../../aspose.pdf.text/texteditoptions/clippingpathsprocessing/) { get; set; } | Ottiene la modalità per l'elaborazione del percorso di ritaglio del testo modificato. |
| [FontReplaceBehavior](../../aspose.pdf.text/texteditoptions/fontreplacebehavior/) { get; set; } | Ottiene la modalità che definisce il comportamento per gli scenari di sostituzione dei caratteri. |
| [LanguageTransformationBehavior](../../aspose.pdf.text/texteditoptions/languagetransformationbehavior/) { get; set; } | Ottiene la modalità che definisce il comportamento per gli scenari di trasformazione linguistica. |
| [NoCharacterBehavior](../../aspose.pdf.text/texteditoptions/nocharacterbehavior/) { get; set; } | Ottiene o imposta la modalità che definisce il comportamento nel caso in cui i font non contengano i caratteri richiesti. |
| [ReplacementFont](../../aspose.pdf.text/texteditoptions/replacementfont/) { get; set; } | Ottiene o imposta il font utilizzato per la sostituzione se il font dell'utente non contiene il carattere richiesto. |
| [ToAttemptGetUnderlineFromSource](../../aspose.pdf.text/texteditoptions/toattemptgetunderlinefromsource/) { get; set; } | Ottiene o imposta il valore che consente la ricerca di sottolineature di testo nella pagina del documento di origine. (Obsoleto) Si prega di utilizzare TextSearchOptions.SearchForTextRelatedGraphics al suo posto. |

### Vedi anche

* class [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


