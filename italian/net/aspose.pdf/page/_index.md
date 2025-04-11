---
title: Class Page
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Page. Classe che rappresenta una pagina di un documento PDF
type: docs
weight: 8050
url: /it/net/aspose.pdf/page/
---
## Classe Pagina

Classe che rappresenta una pagina di un documento PDF.

```csharp
public sealed class Page : IDisposable
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Actions](../../aspose.pdf/page/actions/) { get; } | Ottiene la collezione delle proprietà della pagina. |
| [Annotations](../../aspose.pdf/page/annotations/) { get; } | Ottiene la collezione delle annotazioni della pagina. [`Annotations`](./annotations/) |
| [ArtBox](../../aspose.pdf/page/artbox/) { get; set; } | Ottiene o imposta la scatola artistica della pagina. |
| [Artifacts](../../aspose.pdf/page/artifacts/) { get; } | Ottiene la collezione degli artefatti sulla pagina. |
| [Background](../../aspose.pdf/page/background/) { get; set; } | Ottiene o imposta il colore di sfondo della pagina. |
| [BackgroundImage](../../aspose.pdf/page/backgroundimage/) { get; set; } | Ottiene o imposta l'immagine di sfondo per la pagina (solo per il generatore, non compilata durante la lettura del documento). |
| [BleedBox](../../aspose.pdf/page/bleedbox/) { get; set; } | Ottiene o imposta la scatola di bleed della pagina. |
| [ColorType](../../aspose.pdf/page/colortype/) { get; } | Imposta il tipo di colore delle pagine in base alle informazioni ottenute dagli operatori SetColor, immagini e moduli. |
| [Contents](../../aspose.pdf/page/contents/) { get; } | Ottiene la collezione degli operatori nel flusso di contenuti della pagina. [`OperatorCollection`](../operatorcollection/) |
| [CropBox](../../aspose.pdf/page/cropbox/) { get; set; } | Ottiene o imposta la scatola di ritaglio della pagina. |
| [Duration](../../aspose.pdf/page/duration/) { get; set; } | Ottiene o imposta la durata di visualizzazione della pagina. Questo è il tempo in secondi che la pagina deve essere visualizzata durante la presentazione. Restituisce -1 se la durata non è definita. |
| [FieldsInTabOrder](../../aspose.pdf/page/fieldsintaborder/) { get; } | Ottiene l'elenco degli oggetti Field nell'ordine Tab su questa pagina. |
| [Footer](../../aspose.pdf/page/footer/) { get; set; } | Ottiene o imposta il piè di pagina della pagina. |
| [Group](../../aspose.pdf/page/group/) { get; set; } | Ottiene o imposta una classe di attributi di gruppo che specifica gli attributi del gruppo di pagine della pagina per l'uso nel modello di imaging trasparente. |
| [Header](../../aspose.pdf/page/header/) { get; set; } | Ottiene o imposta l'intestazione della pagina. |
| [IsAddParagraphsAfterLast](../../aspose.pdf/page/isaddparagraphsafterlast/) { get; set; } | Ottiene o imposta l'aggiunta di paragrafi dopo l'ultimo paragrafo della pagina |
| [Layers](../../aspose.pdf/page/layers/) { get; set; } | Ottiene o imposta la collezione di livelli. |
| [MediaBox](../../aspose.pdf/page/mediabox/) { get; set; } | Ottiene o imposta la scatola media della pagina. |
| [NoteLineStyle](../../aspose.pdf/page/notelinestyle/) { get; set; } | Ottiene o imposta lo stile della linea per le note. (solo per il generatore, non compilato durante la lettura del documento) |
| [Number](../../aspose.pdf/page/number/) { get; } | Ottiene il numero della pagina. |
| [PageInfo](../../aspose.pdf/page/pageinfo/) { get; set; } | Ottiene o imposta le informazioni sulla pagina (solo per il generatore, non compilato durante la lettura del documento). |
| [Paragraphs](../../aspose.pdf/page/paragraphs/) { get; set; } | Ottiene i paragrafi. |
| [Rect](../../aspose.pdf/page/rect/) { get; set; } | Ottiene o imposta il rettangolo della pagina. Per ottenere: viene restituita la scatola di ritaglio della pagina se specificata, altrimenti viene restituita la scatola media della pagina. Per impostare: la scatola media della pagina è sempre impostata. Si prega di notare che questa proprietà non considera la rotazione della pagina. Per ottenere il rettangolo della pagina considerando la rotazione, si prega di utilizzare ActualRect. |
| [Resources](../../aspose.pdf/page/resources/) { get; } | Ottiene le risorse della pagina. L'oggetto risorse contiene collezioni di immagini, moduli e caratteri. [`Resources`](./resources/) |
| [Rotate](../../aspose.pdf/page/rotate/) { get; set; } | Ottiene o imposta la rotazione della pagina. |
| [RotationMatrix](../../aspose.pdf/page/rotationmatrix/) { get; } | Ottiene la matrice di trasformazione per la pagina. |
| [TabOrder](../../aspose.pdf/page/taborder/) { get; set; } | Ottiene o imposta l'ordine delle schede della pagina. Valori possibili: Riga, Colonna. Predefinito, Manuale |
| [TocInfo](../../aspose.pdf/page/tocinfo/) { get; set; } | Ottiene o imposta le informazioni della tabella dei contenuti. |
| [TrimBox](../../aspose.pdf/page/trimbox/) { get; set; } | Ottiene o imposta la scatola di rifilatura della pagina. |
| [UserUnit](../../aspose.pdf/page/userunit/) { get; set; } | Ottiene o imposta il valore UserUnit. Un numero positivo che indica la dimensione delle unità di spazio utente predefinite, in multipli di 1 / 72 pollice. Il valore predefinito è 1. Si prega di impostare un valore zero o negativo per cancellare questa voce nella pagina. |
| [Watermark](../../aspose.pdf/page/watermark/) { get; set; } | Ottiene o imposta la filigrana della pagina. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Accept](../../aspose.pdf/page/accept/#accept)(AnnotationSelector) | Accetta l'oggetto visitatore [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) che fornisce funzionalità per lavorare con le annotazioni. |
| [Accept](../../aspose.pdf/page/accept/#accept_1)(ImagePlacementAbsorber) | Accetta l'oggetto visitatore [`ImagePlacementAbsorber`](../imageplacementabsorber/) che fornisce funzionalità per lavorare con gli oggetti di posizionamento delle immagini. |
| [Accept](../../aspose.pdf/page/accept/#accept_2)(TextAbsorber) | Accetta l'oggetto visitatore [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) che fornisce funzionalità per lavorare con gli oggetti di testo. |
| [Accept](../../aspose.pdf/page/accept/#accept_3)(TextFragmentAbsorber) | Accetta l'oggetto visitatore [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) che fornisce funzionalità per lavorare con gli oggetti di testo. |
| [AddGraphics](../../aspose.pdf/page/addgraphics/)(GraphicElementCollection, Rectangle) | Aggiunge grafica alla pagina. Funziona più velocemente rispetto all'aggiunta di elementi uno per uno con il metodo [`AddOnPage`](../../aspose.pdf.vector/graphicelement/addonpage/). |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_2)(string, Rectangle) | Aggiunge un'immagine sulla pagina e la posiziona al centro del rettangolo specificato mantenendo la proporzione dell'immagine. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage)(Stream, Rectangle, Rectangle, bool) | Aggiunge un'immagine sulla pagina e la posiziona al centro del rettangolo specificato mantenendo la proporzione dell'immagine. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_3)(string, Stream, Rectangle, Rectangle) | Aggiunge un'immagine ricercabile sulla pagina e la posiziona al centro del rettangolo specificato mantenendo la proporzione dell'immagine. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_1)(Stream, Rectangle, int, int, bool, Rectangle) | Aggiunge un'immagine sulla pagina e la posiziona in base alla posizione del rettangolo dell'immagine. |
| [AddStamp](../../aspose.pdf/page/addstamp/)(Stamp) | Inserisce un timbro nella pagina. Il timbro può essere un numero di pagina, un'immagine o un semplice testo, ad esempio un logo. |
| [AsByteArray](../../aspose.pdf/page/asbytearray/)(Resolution) | Converte la pagina corrente in bitmap e restituisce quindi un array di byte. |
| [AsXml](../../aspose.pdf/page/asxml/)() | Converte la pagina corrente in xml in codifica utf8. |
| [CalculateContentBBox](../../aspose.pdf/page/calculatecontentbbox/)() | Calcola il valore bbox - rettangolo contenente i contenuti senza margini visibili. |
| [ConvertToPNGMemoryStream](../../aspose.pdf/page/converttopngmemorystream/)() | Converte la pagina in PNG per il flusso di immagini DSR, OMR, OCR. |
| [DeleteGraphics](../../aspose.pdf/page/deletegraphics/)(GraphicElementCollection) | Elimina la grafica dalla pagina. Funziona più velocemente rispetto all'eliminazione di elementi uno per uno con il metodo [`Remove`](../../aspose.pdf.vector/graphicelement/remove/). |
| [Dispose](../../aspose.pdf/page/dispose/)() | Libera la memoria |
| [Flatten](../../aspose.pdf/page/flatten/)() | Rimuove tutti i campi presenti sulla pagina e inserisce i loro valori al posto. |
| [FreeMemory](../../aspose.pdf/page/freememory/)() | Pulisce i dati memorizzati nella cache |
| [GetNotifications](../../aspose.pdf/page/getnotifications/)() | Restituisce notifiche sulle operazioni interne con il contenuto della pagina. (Attualmente sono supportate solo le notifiche sugli eventi dei paragrafi negli scenari di aggiunta di testo.) |
| [GetPageRect](../../aspose.pdf/page/getpagerect/)(bool) | Restituisce il rettangolo della pagina in base alla sua CropBox (o MediaBox se CropBox è nullo). |
| [GetResources](../../aspose.pdf/page/getresources/)() | Recupera le risorse associate alla pagina. |
| [HasVectorGraphics](../../aspose.pdf/page/hasvectorgraphics/)() | Rileva la presenza di grafica vettoriale, se presente sulla pagina. |
| [IsBlank](../../aspose.pdf/page/isblank/)(double) | Ottiene il flag se la pagina è vuota o meno. |
| [MakeGrayscale](../../aspose.pdf/page/makegrayscale/)() | Converte la pagina in scala di grigi. |
| [MergeLayers](../../aspose.pdf/page/mergelayers/#mergelayers)(string) | Unisce tutti i livelli sulla pagina in un unico livello con il nome del nuovo livello specificato. |
| [MergeLayers](../../aspose.pdf/page/mergelayers/#mergelayers_1)(string, string) | Unisce tutti i livelli sulla pagina in un unico livello con il nome del nuovo livello specificato e un Id di gruppo di contenuti opzionale. |
| [Resize](../../aspose.pdf/page/resize/)(PageSize) | Ridimensiona la pagina. |
| [SendTo](../../aspose.pdf/page/sendto/#sendto)(PageDevice, Stream) | Invia la pagina per l'elaborazione con il dispositivo pagina fornito. |
| [SendTo](../../aspose.pdf/page/sendto/#sendto_1)(PageDevice, string) | Invia la pagina per l'elaborazione con il dispositivo pagina fornito. |
| [SetPageSize](../../aspose.pdf/page/setpagesize/)(double, double) | Imposta la dimensione della pagina per la pagina. |
| [TrySaveVectorGraphics](../../aspose.pdf/page/trysavevectorgraphics/)(string) | Tenta di salvare la grafica vettoriale se presente sulla pagina. Il formato di salvataggio è SVG. |
| static [IntToRotation](../../aspose.pdf/page/inttorotation/)(int) | Traduci il valore intero nel corrispondente membro di enumerazione di rotazione. |
| static [RotationToInt](../../aspose.pdf/page/rotationtoint/)(Rotation) | Traduci il membro di enumerazione di rotazione in valore intero. |

## Eventi

| Nome | Descrizione |
| --- | --- |
| event [OnBeforePageGenerate](../../aspose.pdf/page/onbeforepagegenerate/) | Evento per personalizzare intestazione e piè di pagina. |

## Altri Membri

| Nome | Descrizione |
| --- | --- |
| delegate [BeforePageGenerate](../../aspose.pdf/page.beforepagegenerate) | Procedura per personalizzare intestazione e piè di pagina. |

### Vedi Anche

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)