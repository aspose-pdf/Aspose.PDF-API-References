---
title: Class TextSearchOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextSearchOptions classe. Rappresenta le opzioni di ricerca del testo.
type: docs
weight: 11040
url: /it/net/aspose.pdf.text/textsearchoptions/
---
## TextSearchOptions class

Rappresenta le opzioni di ricerca del testo

```csharp
public sealed class TextSearchOptions : TextOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [TextSearchOptions](textsearchoptions/#constructor_2)(bool) | Inizializza una nuova istanza dell'oggetto `TextSearchOptions`. Specifica la modalità di utilizzo delle espressioni regolari. |
| [TextSearchOptions](textsearchoptions/#constructor)(Rectangle) | Inizializza una nuova istanza dell'oggetto `TextSearchOptions`. Specifica il rettangolo che delimita il testo cercato. |
| [TextSearchOptions](textsearchoptions/#constructor_1)(Rectangle, bool) | Inizializza una nuova istanza dell'oggetto `TextSearchOptions`. Specifica il rettangolo che delimita il testo cercato e la modalità di utilizzo delle espressioni regolari. |

## Properties

| Name | Description |
| --- | --- |
| [IgnoreResourceFontErrors](../../aspose.pdf.text/textsearchoptions/ignoreresourcefonterrors/) { get; set; } | Ottiene o imposta l'indicazione che gli errori relativi all'assenza di font saranno ignorati dall'assorbitore di testo (frammento). true - significa che gli errori di assenza di font saranno ignorati. I segmenti di testo che si riferiscono a risorse errate saranno saltati durante l'elaborazione. false (predefinito) - l'errore di assenza di font terminerà l'elaborazione generando un'eccezione. |
| [IgnoreShadowText](../../aspose.pdf.text/textsearchoptions/ignoreshadowtext/) { get; set; } | Ottiene o imposta l'indicazione che i frammenti di testo che rappresentano l'ombra del testo normale saranno ignorati durante la ricerca. true - significa che il testo ombra non sarà trovato (prova questo se la ricerca del testo restituisce frammenti duplicati in posizioni vicine) false - significa che il testo ombra sarà trovato così come il testo normale (valore predefinito) |
| [IsRegularExpressionUsed](../../aspose.pdf.text/textsearchoptions/isregularexpressionused/) { get; set; } | Ottiene o imposta l'indicazione che l'espressione regolare è utilizzata. |
| [LimitToPageBounds](../../aspose.pdf.text/textsearchoptions/limittopagebounds/) { get; set; } | Ottiene o imposta l'indicazione che il testo è cercato all'interno dei limiti della pagina. |
| [LogTextExtractionErrors](../../aspose.pdf.text/textsearchoptions/logtextextractionerrors/) { get; set; } | Ottiene o imposta l'indicazione che gli errori di estrazione del testo (decodifica) saranno registrati nell'assorbitore di testo (frammento). true - significa che gli errori di estrazione del testo (decodifica) saranno registrati. Potrebbe ridurre le prestazioni. false (predefinito) - nessuna registrazione degli errori. |
| [Rectangle](../../aspose.pdf.text/textsearchoptions/rectangle/) { get; set; } | Ottiene o imposta il rettangolo che delimita il testo cercato. |
| [SearchForTextRelatedGraphics](../../aspose.pdf.text/textsearchoptions/searchfortextrelatedgraphics/) { get; set; } | Ottiene o imposta il valore che consente di cercare grafica relativa al testo (sottolineatura, sfondo, ecc.) durante la ricerca del testo. true - la ricerca di grafica relativa al testo sarà eseguita (valore predefinito). false - gli elementi grafici che potrebbero essere presenti nel documento sorgente saranno ignorati. Imposta questo in caso di problemi di prestazioni o se non è necessario gestire sottolineature, sfondi o ritagli. |
| [SearchInAnnotations](../../aspose.pdf.text/textsearchoptions/searchinannotations/) { get; set; } | Ottiene o imposta il valore che consente di cercare testo nelle Annotazioni. true - il testo sarà cercato nelle Annotazioni. false - il testo nelle Annotazioni non sarà analizzato dall'Assorbitore di Frammenti di Testo. |
| [StoredGraphicElementsMaxCount](../../aspose.pdf.text/textsearchoptions/storedgraphicelementsmaxcount/) { get; set; } | Ottiene o imposta il valore che limita la ricerca di grafica relativa al testo (sottolineatura, sfondo, ecc.) su una pagina per il numero specificato di elementi. Il predefinito è 250. Imposta un valore inferiore in caso di problemi di prestazioni, prova un valore maggiore nel caso in cui alcuni elementi grafici non siano stati trovati. |
| [UseFontEngineEncoding](../../aspose.pdf.text/textsearchoptions/usefontengineencoding/) { get; set; } | Ottiene o imposta l'indicazione che il testo sarà cercato utilizzando la codifica del motore del font. true - significa che sarà utilizzata la codifica del motore del font (prova questo se la ricerca del testo fallisce a causa di una codifica imperfetta nel documento) false - significa che sarà utilizzata la codifica del font del documento (valore predefinito) |

### See Also

* class [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)