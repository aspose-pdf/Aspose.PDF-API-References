---
title: Class RenderingOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.RenderingOptions class. Represents rendering options
type: docs
weight: 9760
url: /it/net/aspose.pdf/renderingoptions/
---
## Classe RenderingOptions

Rappresenta le opzioni di rendering.

```csharp
public sealed class RenderingOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [RenderingOptions](renderingoptions/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AnalyzeFonts](../../aspose.pdf/renderingoptions/analyzefonts/) { get; set; } | Sostituisce i caratteri se necessario per garantire che tutti i caratteri nel testo possano essere visualizzati. L'algoritmo di sostituzione dei caratteri segue questi passaggi: 1. Se l'utente imposta esplicitamente la proprietà DefaultFontName, controlla se il carattere specificato può visualizzare i caratteri desiderati. 2. Se non è impostato alcun carattere definito dall'utente, cerca tra i caratteri aggiunti tramite il !:FontRepository.Sources. 3. Analizza il testo per identificare il suo alfabeto o script e suggerire i nomi dei caratteri di conseguenza. Tenta di localizzare e utilizzare questi caratteri dal sistema. 4. Come fallback, cerca nel sistema qualsiasi carattere in grado di visualizzare i caratteri richiesti. |
| [BarcodeOptimization](../../aspose.pdf/renderingoptions/barcodeoptimization/) { get; set; } | Ottiene o imposta la modalità di ottimizzazione del codice a barre. |
| [ConvertFontsToUnicodeTTF](../../aspose.pdf/renderingoptions/convertfontstounicodettf/) { get; set; } | Indica che tutti i caratteri saranno convertiti in versioni TTF unicode. Questo è utile per motivi di compatibilità e per ottimizzare l'uso dei caratteri, poiché ogni nuovo carattere TTF non avrà tutti i simboli del carattere sorgente, ma solo i simboli utilizzati nel testo. |
| [DefaultFontName](../../aspose.pdf/renderingoptions/defaultfontname/) { get; set; } | Ottiene/imposta il nome predefinito del carattere utilizzato per sostituire i caratteri mancanti. |
| [HeightExtraUnits](../../aspose.pdf/renderingoptions/heightextraunits/) { get; set; } | Ottiene o imposta un valore utilizzato per aumentare o diminuire la larghezza del rettangolo per l'operatore AppendRectangle. |
| [IgnoreResourceFontErrors](../../aspose.pdf/renderingoptions/ignoreresourcefonterrors/) { get; set; } | Ottiene o imposta l'indicazione che gli errori relativi all'assenza di caratteri saranno ignorati. true - significa che gli errori di assenza di caratteri saranno ignorati. I segmenti di testo che si riferiscono a risorse errate saranno saltati durante l'elaborazione. false per impostazione predefinita |
| [InterpolationHighQuality](../../aspose.pdf/renderingoptions/interpolationhighquality/) { get; set; } | Ottiene o imposta la modalità di alta qualità per l'interpolazione. |
| [MaxFontsCacheSize](../../aspose.pdf/renderingoptions/maxfontscachesize/) { get; set; } | Numero massimo di caratteri nella cache dei caratteri. Il valore predefinito è 10. |
| [MaxSymbolsCacheSize](../../aspose.pdf/renderingoptions/maxsymbolscachesize/) { get; set; } | Numero massimo di simboli nella cache dei simboli. Il valore predefinito è 100. |
| [OptimizeDimensions](../../aspose.pdf/renderingoptions/optimizedimensions/) { get; set; } | Ottiene o imposta la modalità di ottimizzazione delle dimensioni. |
| [SystemFontsNativeRendering](../../aspose.pdf/renderingoptions/systemfontsnativerendering/) { get; set; } | Ottiene o imposta una modalità in cui i caratteri di sistema vengono renderizzati in modo nativo. |
| [UseFontHinting](../../aspose.pdf/renderingoptions/usefonthinting/) { get; set; } | L'uso di questo flag attiva il meccanismo di hinting dei caratteri. Il hinting dei caratteri è l'uso di istruzioni matematiche per regolare la visualizzazione di un carattere outline. In alcuni casi, attivare questo flag può risolvere problemi di leggibilità del testo. Al momento attuale, l'uso di questo flag potrebbe avere effetto solo per i caratteri TTF, se questi caratteri sono utilizzati nel documento sorgente. |
| [WidthExtraUnits](../../aspose.pdf/renderingoptions/widthextraunits/) { get; set; } | Ottiene o imposta un valore utilizzato per aumentare o diminuire la larghezza del rettangolo per l'operatore AppendRectangle. |

### Vedi anche

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)