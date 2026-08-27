---
title: "Classe TextSearchOptions"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.Text.TextSearchOptions classe. Rappresenta le opzioni di ricerca del testo"
type: docs
weight: 11230
url: /it/net/aspose.pdf.text/textsearchoptions/
---
## TextSearchOptions class

Rappresenta le opzioni di ricerca del testo

```csharp
public sealed class TextSearchOptions : TextOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextSearchOptions](textsearchoptions/#constructor_2)(bool) | Inizializza una nuova istanza dell'oggetto `TextSearchOptions`. Specifica la modalità di utilizzo delle espressioni regolari. |
| [TextSearchOptions](textsearchoptions/#constructor)(Rectangle) | Inizializza una nuova istanza dell'oggetto `TextSearchOptions`. Specifica il rettangolo che delimita il testo cercato. |
| [TextSearchOptions](textsearchoptions/#constructor_1)(Rectangle, bool) | Inizializza una nuova istanza dell'oggetto `TextSearchOptions`. Specifica il rettangolo che delimita il testo cercato e la modalità di utilizzo delle espressioni regolari. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [IgnoreResourceFontErrors](../../aspose.pdf.text/textsearchoptions/ignoreresourcefonterrors/) { get; set; } | Ottiene o imposta l'indicazione che gli errori relativi all'assenza del carattere saranno ignorati dall'assorbitore di testo (frammento). true - indica che gli errori di assenza del carattere saranno ignorati. I segmenti di testo che fanno riferimento a risorse errate saranno saltati durante l'elaborazione. false (predefinito) - l'errore di assenza del carattere interromperà l'elaborazione generando un'eccezione. |
| [IgnoreShadowText](../../aspose.pdf.text/textsearchoptions/ignoreshadowtext/) { get; set; } | Ottiene o imposta l'indicazione che i frammenti di testo che rappresentano l'ombra del testo normale saranno ignorati durante la ricerca. true - indica che il testo in ombra non verrà trovato (prova questa opzione se la ricerca di testo restituisce frammenti duplicati in posizioni vicine). false - indica che il testo in ombra verrà trovato insieme al testo normale (valore predefinito). |
| [IsRegularExpressionUsed](../../aspose.pdf.text/textsearchoptions/isregularexpressionused/) { get; set; } | Ottiene o imposta l'indicazione che viene utilizzata un'espressione regolare. |
| [LimitToPageBounds](../../aspose.pdf.text/textsearchoptions/limittopagebounds/) { get; set; } | Ottiene o imposta l'indicazione che il testo viene cercato entro i limiti della pagina. |
| [LogTextExtractionErrors](../../aspose.pdf.text/textsearchoptions/logtextextractionerrors/) { get; set; } | Ottiene o imposta l'indicazione che gli errori di estrazione del testo (decodifica) saranno registrati nell'assorbitore di testo (frammento). true - indica che gli errori di estrazione del testo (decodifica) saranno registrati. Può ridurre le prestazioni. false (predefinito) - nessuna registrazione degli errori. |
| [Rectangle](../../aspose.pdf.text/textsearchoptions/rectangle/) { get; set; } | Ottiene o imposta il rettangolo che delimita il testo cercato. |
| [SearchForTextRelatedGraphics](../../aspose.pdf.text/textsearchoptions/searchfortextrelatedgraphics/) { get; set; } | Ottiene o imposta il valore che consente la ricerca di grafica correlata al testo (sottolineatura, sfondo ecc.) durante la ricerca del testo. true - la ricerca di grafica correlata al testo verrà eseguita (valore predefinito). false - gli elementi grafici presenti nel documento sorgente saranno ignorati. Impostare questa opzione in caso di problemi di prestazioni o se non è necessario gestire sottolineature, sfondi o ritagli. |
| [SearchInAnnotations](../../aspose.pdf.text/textsearchoptions/searchinannotations/) { get; set; } | Ottiene o imposta il valore che consente la ricerca di testo nelle Annotations. true - il testo sarà ricercato nelle Annotations. false - il testo nelle Annotations non sarà analizzato da TextFragmentAbsorber. |
| [StoredGraphicElementsMaxCount](../../aspose.pdf.text/textsearchoptions/storedgraphicelementsmaxcount/) { get; set; } | Ottiene o imposta il valore che limita la ricerca di grafica correlata al testo (sottolineatura, sfondo ecc.) su una pagina per il numero specificato di elementi. Il valore predefinito è 250. Impostare un valore inferiore in caso di problemi di prestazioni, provare un valore maggiore se alcuni elementi grafici non sono stati trovati. |
| [UseFontEngineEncoding](../../aspose.pdf.text/textsearchoptions/usefontengineencoding/) { get; set; } | Ottiene o imposta l'indicazione che il testo sarà cercato utilizzando la codifica del motore dei caratteri. true - indica che verrà utilizzata la codifica del motore dei caratteri (prova questa opzione se la ricerca di testo fallisce a causa di una codifica imperfetta nel documento). false - indica che verrà utilizzata la codifica dei caratteri del documento (valore predefinito). |

### Vedi anche

* class [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


