---
title: "Classe PageNumberStamp"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.PageNumberStamp. Rappresenta il timbro del numero di pagina ed è usata per numerare le pagine"
type: docs
weight: 8370
url: /it/net/aspose.pdf/pagenumberstamp/
---
## PageNumberStamp class

Rappresenta il timbro del numero di pagina ed è usato per numerare le pagine.

```csharp
public sealed class PageNumberStamp : TextStamp
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PageNumberStamp](pagenumberstamp/#constructor)() | Inizializza una nuova istanza della classe `PageNumberStamp`. Il formato è impostato su "#". |
| [PageNumberStamp](pagenumberstamp/#constructor_1)(FormattedText) | Crea PageNumberStamp mediante testo formattato. |
| [PageNumberStamp](pagenumberstamp/#constructor_2)(string) | Inizializza una nuova istanza della classe `PageNumberStamp`. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AutoAdjustFontSizePrecision](../../aspose.pdf/textstamp/autoadjustfontsizeprecision/) { get; set; } | Regola automaticamente la precisione della dimensione del carattere. Valore predefinito: 0.1; |
| [AutoAdjustFontSizeToFitStampRectangle](../../aspose.pdf/textstamp/autoadjustfontsizetofitstamprectangle/) { get; set; } | Se abilitato, la dimensione del carattere verrà regolata automaticamente per adattarsi al rettangolo del timbro di dimensioni: [`Width`](../textstamp/width/) e [`Height`](../textstamp/height/). Larghezza e altezza predefinite sono derivate dal rettangolo della pagina. |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Imposta o ottiene un valore booleano che indica se il contenuto è timbrato come sfondo. Se il valore è true, il contenuto del timbro è posizionato in fondo. Per impostazione predefinita, il valore è false, il contenuto del timbro è posizionato in alto. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Ottiene o imposta il margine inferiore del timbro. |
| [Draw](../../aspose.pdf/textstamp/draw/) { get; set; } | Questa proprietà determina come il timbro viene disegnato sulla pagina. Se Draw = true il timbro è disegnato come operatori grafici e se draw = false il timbro è disegnato come testo. |
| [FontSize](../../aspose.pdf/textstamp/fontsize/) { get; } | Dimensione effettiva del carattere dopo che il timbro è stato posizionato. (Può differire dalla dimensione iniziale del carattere fornita tramite il costruttore se l'opzione 'AutoAdjustFontSizeToFitStampRectangle' è abilitata.) |
| [Format](../../aspose.pdf/pagenumberstamp/format/) { get; set; } | Valore stringa per il timbro dei numeri di pagina. Il valore deve includere il carattere '#' che viene sostituito con il numero di pagina durante il timbratura. |
| override [Height](../../aspose.pdf/textstamp/height/) { get; set; } | Altezza desiderata del timbro sulla pagina. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Ottiene o imposta l'allineamento orizzontale del timbro sulla pagina. |
| [Justify](../../aspose.pdf/textstamp/justify/) { get; set; } | Definisce la giustificazione del testo. Se questa proprietà è impostata su true, entrambi i bordi sinistro e destro del testo sono allineati. Valore predefinito: false. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Ottiene o imposta il margine sinistro del timbro. |
| [MaxRowWidth](../../aspose.pdf/textstamp/maxrowwidth/) { get; set; } | Altezza massima della riga per l'opzione WordWrap. |
| [NoCharacterBehavior](../../aspose.pdf/textstamp/nocharacterbehavior/) { get; set; } | Ottiene o imposta la modalità che definisce il comportamento nel caso in cui i font non contengano i caratteri richiesti. |
| [NumberingStyle](../../aspose.pdf/pagenumberstamp/numberingstyle/) { get; set; } | Stile di numerazione usato da questo timbro. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Ottiene o imposta un valore che indica l'opacità del timbro. Il valore è da 0.0 a 1.0. Per impostazione predefinita il valore è 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Ottiene o imposta un valore che indica l'opacità del contorno del timbro. Il valore è da 0.0 a 1.0. Per impostazione predefinita il valore è 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Ottiene o imposta un valore per la larghezza del contorno del timbro. Per impostazione predefinita il valore è 1.0. |
| [ReplacementFont](../../aspose.pdf/textstamp/replacementfont/) { get; set; } | Restituisce o imposta il font usato per la sostituzione se il font dell'utente non contiene il carattere richiesto. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Ottiene o imposta il margine destro del timbro. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Imposta o ottiene la rotazione del contenuto del timbro secondo i valori di [`Rotation`](../rotation/). Nota. Questa proprietà serve per impostare angoli che sono multipli di 90 gradi (0, 90, 180, 270 gradi). Per impostare un angolo arbitrario utilizzare la proprietà RotateAngle. Se l'angolo impostato da ArbitraryAngle non è un multiplo di 90, la proprietà Rotate restituisce Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Ottiene o imposta l'angolo di rotazione del timbro in gradi. Questa proprietà consente di impostare un angolo di rotazione arbitrario. |
| [Scale](../../aspose.pdf/textstamp/scale/) { get; set; } | Definisce la scalatura del testo. Se questa proprietà è impostata su true e viene specificato il valore Width, il testo verrà scalato per adattarsi alla larghezza specificata. |
| [StartingNumber](../../aspose.pdf/pagenumberstamp/startingnumber/) { get; set; } | Ottiene o imposta il valore del numero della pagina iniziale. Le altre pagine saranno numerate a partire da questo valore. |
| [TextAlignment](../../aspose.pdf/textstamp/textalignment/) { get; set; } | Allineamento del testo all'interno del timbro. |
| [TextState](../../aspose.pdf/textstamp/textstate/) { get; } | Ottiene le proprietà del testo del timbro. Vedi [`TextState`](../textstamp/textstate/) per i dettagli. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Ottiene o imposta il margine superiore del timbro. |
| [TreatYIndentAsBaseLine](../../aspose.pdf/textstamp/treatyindentasbaseline/) { get; set; } | Definisce l'origine delle coordinate per posizionare il testo. Se TreatYIndentAsBaseLine = true (impostazione predefinita quando Draw = true) il valore YIndent verrà trattato come linea di base del testo. Se TreatYIndentAsBaseLine = false (impostazione predefinita quando Draw = false) il valore YIndent verrà trattato come parte inferiore (linea di discesa) del testo. |
| [Value](../../aspose.pdf/textstamp/value/) { get; set; } | Ottiene o imposta il valore stringa utilizzato come timbro nella pagina. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Ottiene o imposta l'allineamento verticale del timbro sulla pagina. |
| override [Width](../../aspose.pdf/textstamp/width/) { get; set; } | Larghezza desiderata del timbro sulla pagina. |
| [WordWrapMode](../../aspose.pdf/textstamp/wordwrapmode/) { get; set; } | Ottiene o imposta la modalità di a capo automatico per il rendering del testo. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | Coordinata orizzontale del timbro, a partire da sinistra. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | Coordinata verticale del timbro, a partire dal basso. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Fattore di zoom del timbro. Consente di ridimensionare il timbro. Si noti che la coppia di proprietà ZoomX e ZoomY consente di impostare il fattore di zoom per ogni asse separatamente. L'impostazione di questa proprietà modifica entrambe le proprietà ZoomX e ZoomY. Se ZoomX e ZoomY sono diversi, la proprietà Zoom restituisce il valore di ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Fattore di zoom orizzontale del timbro. Consente di ridimensionare il timbro orizzontalmente. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Fattore di zoom verticale del timbro. Consente di ridimensionare il timbro verticalmente. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Restituisce l'ID del timbro. |
| override [Put](../../aspose.pdf/pagenumberstamp/put/)(Page) | Aggiunge il numero di pagina. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Imposta l'ID del timbro. |

### Vedi anche

* class [TextStamp](../textstamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


