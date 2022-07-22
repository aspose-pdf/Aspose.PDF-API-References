---
title: PageNumberStamp
second_title: Aspose.PDF per .NET API Reference
description: Rappresenta il timbro del numero di pagina e utilizzato per numerare le pagine.
type: docs
weight: 5890
url: /it/net/aspose.pdf/pagenumberstamp/
---
## PageNumberStamp class

Rappresenta il timbro del numero di pagina e utilizzato per numerare le pagine.

```csharp
public sealed class PageNumberStamp : TextStamp
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PageNumberStamp](pagenumberstamp#constructor)() | Inizializza una nuova istanza di[`PageNumberStamp`](../pagenumberstamp) classe. Il formato è impostato su "#". |
| [PageNumberStamp](pagenumberstamp#constructor_1)(FormattedText) | Crea PageNumberStamp in base al testo formattato. |
| [PageNumberStamp](pagenumberstamp#constructor_2)(string) | Inizializza una nuova istanza di[`PageNumberStamp`](../pagenumberstamp) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background) { get; set; } | Imposta o ottiene un valore bool che indica che il contenuto è stampato come sfondo. Se il valore è true, il contenuto del timbro viene posizionato in basso. Per default, il valore è false, il contenuto del timbro viene posizionato in alto. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin) { get; set; } | Ottiene o imposta il margine inferiore del timbro. |
| [Draw](../../aspose.pdf/textstamp/draw) { get; set; } | Questa proprietà determina il modo in cui il timbro viene disegnato sulla pagina. Se Draw = true stamp viene disegnato come operatori grafici e se draw = false allora stamp viene disegnato come testo. |
| [Format](../../aspose.pdf/pagenumberstamp/format) { get; set; } | Valore stringa per la stampa dei numeri di pagina. Il valore deve includere il carattere '#' che viene sostituito con il numero di pagina nel processo di timbratura. |
| override [Height](../../aspose.pdf/textstamp/height) { get; set; } | Altezza desiderata del timbro sulla pagina. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment) { get; set; } | Ottiene o imposta l'allineamento orizzontale del timbro sulla pagina. |
| [Justify](../../aspose.pdf/textstamp/justify) { get; set; } | Definisce la giustificazione del testo. Se questa proprietà è impostata su true, entrambi i bordi sinistro e destro del testo vengono allineati. Valore predefinito: false. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin) { get; set; } | Ottiene o imposta il margine sinistro del timbro. |
| [MaxRowWidth](../../aspose.pdf/textstamp/maxrowwidth) { get; set; } | Altezza massima della riga per l'opzione WordWrap. |
| [NumberingStyle](../../aspose.pdf/pagenumberstamp/numberingstyle) { get; set; } | Stile di numerazione utilizzato da questo francobollo. |
| [Opacity](../../aspose.pdf/stamp/opacity) { get; set; } | Ottiene o imposta un valore per indicare l'opacità del timbro. Il valore è compreso tra 0.0 e 1.0. Per impostazione predefinita il valore è 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity) { get; set; } | Ottiene o imposta un valore per indicare l'opacità del contorno del timbro. Il valore è compreso tra 0.0 e 1.0. Per impostazione predefinita il valore è 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth) { get; set; } | Ottiene o imposta un valore della larghezza del contorno del timbro. Per impostazione predefinita, il valore è 1.0. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin) { get; set; } | Ottiene o imposta il margine destro del timbro. |
| [Rotate](../../aspose.pdf/stamp/rotate) { get; set; } | Imposta o ottiene la rotazione del contenuto del timbro in base[`Rotation`](../rotation) valori. Nota. Questa proprietà serve per impostare angoli che sono multipli di 90 gradi (0, 90, 180, 270 gradi). Per impostare angoli arbitrari, utilizzare la proprietà RotateAngle. Se l'angolo impostato da ArbitraryAngle non è multiplo di 90, la proprietà Ruota restituisce Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle) { get; set; } | Ottiene o imposta l'angolo di rotazione del timbro in gradi. Questa proprietà permette di impostare un angolo di rotazione arbitrario. |
| [Scale](../../aspose.pdf/textstamp/scale) { get; set; } | Definisce il ridimensionamento del testo. Se questa proprietà è impostata su true e viene specificato il valore Larghezza, il testo verrà ridimensionato per adattarsi alla larghezza specificata. |
| [StartingNumber](../../aspose.pdf/pagenumberstamp/startingnumber) { get; set; } | Ottiene o imposta il valore del numero di pagina iniziale. Le altre pagine verranno numerate a partire da questo valore. |
| [TextAlignment](../../aspose.pdf/textstamp/textalignment) { get; set; } | Allineamento del testo all'interno del timbro. |
| [TextState](../../aspose.pdf/textstamp/textstate) { get; } | Ottiene le proprietà di testo del timbro. Vedere[`TextState`](../textstamp/textstate) per i dettagli. |
| [TopMargin](../../aspose.pdf/stamp/topmargin) { get; set; } | Ottiene o imposta il margine superiore del timbro. |
| [TreatYIndentAsBaseLine](../../aspose.pdf/textstamp/treatyindentasbaseline) { get; set; } | Definisce l'origine delle coordinate per il posizionamento del testo. Se TreatYIndentAsBaseLine = true (predefinito quando Draw = true) il valore YIndent verrà trattato come linea di base del testo. Se TreatYIndentAsBaseLine = false (predefinito quando Draw = false) Il valore YIndent verrà considerato come bottom ( linea di discesa) di testo. |
| [Value](../../aspose.pdf/textstamp/value) { get; set; } | Ottiene o imposta il valore della stringa che viene utilizzato come timbro sulla pagina. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment) { get; set; } | Ottiene o imposta l'allineamento verticale del timbro sulla pagina. |
| override [Width](../../aspose.pdf/textstamp/width) { get; set; } | Larghezza desiderata del timbro sulla pagina. |
| [WordWrap](../../aspose.pdf/textstamp/wordwrap) { get; set; } | Definisce il ritorno a capo automatico. Se questa proprietà è impostata su true e viene specificato il valore Larghezza, il testo verrà interrotto nelle diverse righe per adattarsi alla larghezza specificata. Valore predefinito: false. |
| [XIndent](../../aspose.pdf/stamp/xindent) { get; set; } | Coordinata timbro orizzontale, partendo da sinistra. |
| [YIndent](../../aspose.pdf/stamp/yindent) { get; set; } | Coordinata timbro verticale, partendo dal basso. |
| [Zoom](../../aspose.pdf/stamp/zoom) { get; set; } | Fattore di zoom del timbro. Consente di scalare il timbro. Si noti che la coppia di proprietà ZoomX e ZoomY consente di impostare il fattore di zoom per ogni asse separatamente. L'impostazione di questa proprietà modifica le proprietà di ZoomX e ZoomY. Se ZoomX e ZoomY sono diversi, la proprietà Zoom restituisce il valore ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx) { get; set; } | Fattore di zoom orizzontale del timbro. Consente di ridimensionare il timbro orizzontalmente. |
| [ZoomY](../../aspose.pdf/stamp/zoomy) { get; set; } | Fattore di zoom verticale del timbro. Consente di scalare il timbro verticalmente. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid)() | Restituisce l'ID timbro. |
| override [Put](../../aspose.pdf/pagenumberstamp/put)(Page) | Aggiunge il numero di pagina. |
| [setStampId](../../aspose.pdf/stamp/setstampid)(int) | Imposta ID timbro |

### Guarda anche

* class [TextStamp](../textstamp)
* spazio dei nomi [Aspose.Pdf](../../aspose.pdf)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
