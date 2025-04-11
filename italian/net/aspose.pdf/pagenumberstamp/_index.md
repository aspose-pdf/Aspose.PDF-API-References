---
title: Class PageNumberStamp
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.PageNumberStamp. Rappresenta il timbro del numero di pagina e viene utilizzato per numerare le pagine
type: docs
weight: 8230
url: /it/net/aspose.pdf/pagenumberstamp/
---
## Classe PageNumberStamp

Rappresenta il timbro del numero di pagina e viene utilizzato per numerare le pagine.

```csharp
public sealed class PageNumberStamp : TextStamp
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PageNumberStamp](pagenumberstamp/#constructor)() | Inizializza una nuova istanza della classe `PageNumberStamp`. Il formato è impostato su "#". |
| [PageNumberStamp](pagenumberstamp/#constructor_1)(FormattedText) | Crea PageNumberStamp tramite testo formattato. |
| [PageNumberStamp](pagenumberstamp/#constructor_2)(string) | Inizializza una nuova istanza della classe `PageNumberStamp`. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AutoAdjustFontSizePrecision](../../aspose.pdf/textstamp/autoadjustfontsizeprecision/) { get; set; } | Regola automaticamente la precisione della dimensione del carattere. Valore predefinito: 0.1; |
| [AutoAdjustFontSizeToFitStampRectangle](../../aspose.pdf/textstamp/autoadjustfontsizetofitstamprectangle/) { get; set; } | Se abilitato, la dimensione del carattere verrà regolata automaticamente per adattarsi al rettangolo del timbro di dimensione: [`Width`](../textstamp/width/) e [`Height`](../textstamp/height/). La larghezza e l'altezza predefinite sono derivate dal rettangolo della pagina. |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Imposta o ottiene un valore booleano che indica se il contenuto è timbrato come sfondo. Se il valore è vero, il contenuto del timbro è posizionato in fondo. Per impostazione predefinita, il valore è falso, il contenuto del timbro è posizionato in cima. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Ottiene o imposta il margine inferiore del timbro. |
| [Draw](../../aspose.pdf/textstamp/draw/) { get; set; } | Questa proprietà determina come il timbro viene disegnato sulla pagina. Se Draw = true, il timbro viene disegnato come operatori grafici e se draw = false, il timbro viene disegnato come testo. |
| [FontSize](../../aspose.pdf/textstamp/fontsize/) { get; } | Dimensione effettiva del carattere dopo che il timbro è stato posizionato. (Può differire dalla dimensione iniziale del carattere fornita tramite il costruttore se l'opzione 'AutoAdjustFontSizeToFitStampRectangle' è abilitata.) |
| [Format](../../aspose.pdf/pagenumberstamp/format/) { get; set; } | Valore stringa per timbrare i numeri di pagina. Il valore deve includere il carattere '#' che viene sostituito con il numero di pagina nel processo di timbratura. |
| override [Height](../../aspose.pdf/textstamp/height/) { get; set; } | Altezza desiderata del timbro sulla pagina. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Ottiene o imposta l'allineamento orizzontale del timbro sulla pagina. |
| [Justify](../../aspose.pdf/textstamp/justify/) { get; set; } | Definisce la giustificazione del testo. Se questa proprietà è impostata su true, entrambi i bordi sinistro e destro del testo sono allineati. Valore predefinito: false. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Ottiene o imposta il margine sinistro del timbro. |
| [MaxRowWidth](../../aspose.pdf/textstamp/maxrowwidth/) { get; set; } | Altezza massima della riga per l'opzione WordWrap. |
| [NoCharacterBehavior](../../aspose.pdf/textstamp/nocharacterbehavior/) { get; set; } | Ottiene o imposta la modalità che definisce il comportamento nel caso in cui i caratteri richiesti non siano contenuti nei caratteri. |
| [NumberingStyle](../../aspose.pdf/pagenumberstamp/numberingstyle/) { get; set; } | Stile di numerazione utilizzato da questo timbro. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Ottiene o imposta un valore per indicare l'opacità del timbro. Il valore va da 0.0 a 1.0. Per impostazione predefinita, il valore è 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Ottiene o imposta un valore per indicare l'opacità del contorno del timbro. Il valore va da 0.0 a 1.0. Per impostazione predefinita, il valore è 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Ottiene o imposta un valore della larghezza del contorno del timbro. Per impostazione predefinita, il valore è 1.0. |
| [ReplacementFont](../../aspose.pdf/textstamp/replacementfont/) { get; set; } | Ottiene o imposta il carattere utilizzato per la sostituzione se il carattere dell'utente non contiene il carattere richiesto. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Ottiene o imposta il margine destro del timbro. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Imposta o ottiene la rotazione del contenuto del timbro secondo i valori di [`Rotation`](../rotation/). Nota. Questa proprietà è per impostare angoli che sono multipli di 90 gradi (0, 90, 180, 270 gradi). Per impostare un angolo arbitrario, utilizzare la proprietà RotateAngle. Se l'angolo impostato da ArbitraryAngle non è un multiplo di 90, la proprietà Rotate restituisce Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Ottiene o imposta l'angolo di rotazione del timbro in gradi. Questa proprietà consente di impostare un angolo di rotazione arbitrario. |
| [Scale](../../aspose.pdf/textstamp/scale/) { get; set; } | Definisce la scala del testo. Se questa proprietà è impostata su true e il valore di Width è specificato, il testo verrà scalato per adattarsi alla larghezza specificata. |
| [StartingNumber](../../aspose.pdf/pagenumberstamp/startingnumber/) { get; set; } | Ottiene o imposta il valore del numero della pagina iniziale. Altre pagine saranno numerate a partire da questo valore. |
| [TextAlignment](../../aspose.pdf/textstamp/textalignment/) { get; set; } | Allineamento del testo all'interno del timbro. |
| [TextState](../../aspose.pdf/textstamp/textstate/) { get; } | Ottiene le proprietà del testo del timbro. Vedi [`TextState`](../textstamp/textstate/) per dettagli. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Ottiene o imposta il margine superiore del timbro. |
| [TreatYIndentAsBaseLine](../../aspose.pdf/textstamp/treatyindentasbaseline/) { get; set; } | Definisce l'origine delle coordinate per posizionare il testo. Se TreatYIndentAsBaseLine = true (predefinito quando Draw = true), il valore YIndent sarà trattato come la linea di base del testo. Se TreatYIndentAsBaseLine = false (predefinito quando Draw = false), il valore YIndent sarà trattato come il fondo (linea di discesa) del testo. |
| [Value](../../aspose.pdf/textstamp/value/) { get; set; } | Ottiene o imposta il valore stringa utilizzato come timbro sulla pagina. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Ottiene o imposta l'allineamento verticale del timbro sulla pagina. |
| override [Width](../../aspose.pdf/textstamp/width/) { get; set; } | Larghezza desiderata del timbro sulla pagina. |
| [WordWrapMode](../../aspose.pdf/textstamp/wordwrapmode/) { get; set; } | Ottiene o imposta la modalità di interruzione delle parole per il rendering del testo. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | Coordinata orizzontale del timbro, partendo da sinistra. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | Coordinata verticale del timbro, partendo dal basso. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Fattore di zoom del timbro. Consente di scalare il timbro. Si prega di notare che la coppia di proprietà ZoomX e ZoomY consente di impostare il fattore di zoom per ogni asse separatamente. L'impostazione di questa proprietà modifica sia le proprietà ZoomX che ZoomY. Se ZoomX e ZoomY sono diversi, la proprietà Zoom restituisce il valore di ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Fattore di zoom orizzontale del timbro. Consente di scalare il timbro orizzontalmente. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Fattore di zoom verticale del timbro. Consente di scalare il timbro verticalmente. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Restituisce l'ID del timbro. |
| override [Put](../../aspose.pdf/pagenumberstamp/put/)(Page) | Aggiunge il numero di pagina. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Imposta l'ID del timbro. |

### Vedi Anche

* classe [TextStamp](../textstamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)