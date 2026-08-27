---
title: "Classe RenderingOptions"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.RenderingOptions. Rappresenta le opzioni di rendering"
type: docs
weight: 9910
url: /it/net/aspose.pdf/renderingoptions/
---
## RenderingOptions class

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
| [AnalyzeFonts](../../aspose.pdf/renderingoptions/analyzefonts/) { get; set; } | Sostituisce i caratteri tipografici secondo necessità per garantire che tutti i caratteri nel testo possano essere visualizzati. L'algoritmo di sostituzione dei font segue questi passaggi: 1. Se l'utente imposta esplicitamente la proprietà DefaultFontName, verifica se il font specificato può visualizzare i caratteri desiderati. 2. Se non è impostato alcun font definito dall'utente, cerca tra i font aggiunti tramite !:FontRepository.Sources. 3. Analizza il testo per identificare il suo alfabeto o script e suggerisce i nomi dei font di conseguenza. Tenta di individuare e utilizzare questi font dal sistema. 4. Come soluzione di ripiego, cerca nel sistema un qualsiasi font in grado di visualizzare i caratteri richiesti. |
| [BarcodeOptimization](../../aspose.pdf/renderingoptions/barcodeoptimization/) { get; set; } | Ottiene o imposta la modalità di ottimizzazione del codice a barre. |
| [ConvertFontsToUnicodeTTF](../../aspose.pdf/renderingoptions/convertfontstounicodettf/) { get; set; } | Indica che tutti i font saranno convertiti in versioni TTF Unicode. Questo è utile per motivi di compatibilità e per ottimizzare l'uso dei font, poiché ogni nuovo font TTF conterrà solo i simboli utilizzati nel testo, non tutti i simboli del font di origine. |
| [DefaultFontName](../../aspose.pdf/renderingoptions/defaultfontname/) { get; set; } | Ottiene/imposta il nome predefinito del font utilizzato per sostituire i font mancanti. |
| [HeightExtraUnits](../../aspose.pdf/renderingoptions/heightextraunits/) { get; set; } | Ottiene o imposta un valore usato per aumentare o diminuire la larghezza del rettangolo per l'operatore AppendRectangle. |
| [IgnoreResourceFontErrors](../../aspose.pdf/renderingoptions/ignoreresourcefonterrors/) { get; set; } | Ottiene o imposta l'indicazione che gli errori relativi all'assenza del font saranno ignorati. true - indica che gli errori di assenza del font saranno ignorati. I segmenti di testo che si riferiscono a risorse errate verranno saltati durante l'elaborazione. false per impostazione predefinita |
| [InterpolationHighQuality](../../aspose.pdf/renderingoptions/interpolationhighquality/) { get; set; } | Ottiene o imposta la modalità ad alta qualità per l'interpolazione. |
| [MaxFontsCacheSize](../../aspose.pdf/renderingoptions/maxfontscachesize/) { get; set; } | Numero massimo di font nella cache dei font. Il valore predefinito è 10. |
| [MaxSymbolsCacheSize](../../aspose.pdf/renderingoptions/maxsymbolscachesize/) { get; set; } | Numero massimo di simboli nella cache dei simboli. Il valore predefinito è 100. |
| [OptimizeDimensions](../../aspose.pdf/renderingoptions/optimizedimensions/) { get; set; } | Ottiene o imposta la modalità di ottimizzazione delle dimensioni. |
| [SystemFontsNativeRendering](../../aspose.pdf/renderingoptions/systemfontsnativerendering/) { get; set; } | Ottiene o imposta una modalità in cui i font di sistema vengono renderizzati nativamente. |
| [UseFontHinting](../../aspose.pdf/renderingoptions/usefonthinting/) { get; set; } | L'uso di questo flag attiva il meccanismo di hinting dei font. Il hinting dei font è l'uso di istruzioni matematiche per regolare la visualizzazione di un font contornato. In alcuni casi, attivare questo flag può risolvere problemi di leggibilità del testo. Al momento, l'uso di questo flag può avere effetto solo sui font TTF, se questi font sono utilizzati nel documento di origine. |
| [WidthExtraUnits](../../aspose.pdf/renderingoptions/widthextraunits/) { get; set; } | Ottiene o imposta un valore usato per aumentare o diminuire la larghezza del rettangolo per l'operatore AppendRectangle. |

### Vedi anche

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


