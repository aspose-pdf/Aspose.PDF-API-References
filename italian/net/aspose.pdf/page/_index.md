---
title: "Classe Page"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Page. Classe che rappresenta una pagina di documento PDF"
type: docs
weight: 8190
url: /it/net/aspose.pdf/page/
---
## Page class

Classe che rappresenta una pagina di documento PDF.

```csharp
public sealed class Page : IDisposable
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Actions](../../aspose.pdf/page/actions/) { get; } | Ottiene la raccolta delle proprietà della pagina. |
| [Annotations](../../aspose.pdf/page/annotations/) { get; } | Ottiene la raccolta delle annotazioni della pagina. [`Annotations`](./annotations/) |
| [ArtBox](../../aspose.pdf/page/artbox/) { get; set; } | Ottiene o imposta l'art box della pagina. |
| [Artifacts](../../aspose.pdf/page/artifacts/) { get; } | Ottiene la raccolta degli artefatti nella pagina. |
| [Background](../../aspose.pdf/page/background/) { get; set; } | Ottiene o imposta il colore di sfondo della pagina. |
| [BackgroundImage](../../aspose.pdf/page/backgroundimage/) { get; set; } | Ottiene o imposta l'immagine di sfondo per la pagina (solo per il generatore, non viene popolata durante la lettura del documento). |
| [BleedBox](../../aspose.pdf/page/bleedbox/) { get; set; } | Ottiene o imposta il bleed box della pagina. |
| [ColorType](../../aspose.pdf/page/colortype/) { get; } | Imposta il tipo di colore delle pagine basandosi sulle informazioni ottenute dagli operatori SetColor, dalle immagini e dai moduli. |
| [Contents](../../aspose.pdf/page/contents/) { get; } | Ottiene la raccolta degli operatori nel flusso di contenuto della pagina. [`OperatorCollection`](../operatorcollection/) |
| [CropBox](../../aspose.pdf/page/cropbox/) { get; set; } | Ottiene o imposta il crop box della pagina. |
| [Duration](../../aspose.pdf/page/duration/) { get; set; } | Ottiene o imposta la durata di visualizzazione della pagina. Questo è il tempo in secondi per cui la pagina deve essere mostrata durante la presentazione. Restituisce -1 se la durata non è definita. |
| [FieldsInTabOrder](../../aspose.pdf/page/fieldsintaborder/) { get; } | Ottiene l'elenco degli oggetti Field in ordine Tab su questa pagina. |
| [Footer](../../aspose.pdf/page/footer/) { get; set; } | Ottiene o imposta il piè di pagina. |
| [Group](../../aspose.pdf/page/group/) { get; set; } | Ottiene o imposta una classe di attributi di gruppo che specifica gli attributi del gruppo di pagine per l'uso nel modello di imaging trasparente. |
| [Header](../../aspose.pdf/page/header/) { get; set; } | Ottiene o imposta l'intestazione della pagina. |
| [IsAddParagraphsAfterLast](../../aspose.pdf/page/isaddparagraphsafterlast/) { get; set; } | Ottiene o imposta l'aggiunta di paragrafi dopo l'ultimo paragrafo della pagina |
| [Layers](../../aspose.pdf/page/layers/) { get; set; } | Ottiene o imposta la raccolta dei layer. |
| [MediaBox](../../aspose.pdf/page/mediabox/) { get; set; } | Ottiene o imposta il media box della pagina. |
| [NoteLineStyle](../../aspose.pdf/page/notelinestyle/) { get; set; } | Ottiene o imposta lo stile di linea per le note (solo per il generatore, non compilato durante la lettura del documento). |
| [Number](../../aspose.pdf/page/number/) { get; } | Ottieni il numero della pagina. |
| [PageInfo](../../aspose.pdf/page/pageinfo/) { get; set; } | Ottiene o imposta le informazioni della pagina (solo per il generatore, non compilato durante la lettura del documento). |
| [Paragraphs](../../aspose.pdf/page/paragraphs/) { get; set; } | Ottiene i paragrafi. |
| [Rect](../../aspose.pdf/page/rect/) { get; set; } | Ottiene o imposta il rettangolo della pagina. Per l'ottenimento: viene restituito il crop box della pagina se specificato, altrimenti viene restituito il media box della pagina. Per l'impostazione: il media box della pagina è sempre impostato. Si noti che questa proprietà non considera la rotazione della pagina. Per ottenere il rettangolo della pagina considerando la rotazione, utilizzare ActualRect. |
| [Resources](../../aspose.pdf/page/resources/) { get; } | Ottiene le risorse della pagina. L'oggetto Resources contiene raccolte di immagini, moduli e font. [`Resources`](./resources/) |
| [Rotate](../../aspose.pdf/page/rotate/) { get; set; } | Ottiene o imposta la rotazione della pagina. |
| [RotationMatrix](../../aspose.pdf/page/rotationmatrix/) { get; } | Ottiene la matrice di trasformazione per la pagina. |
| [TabOrder](../../aspose.pdf/page/taborder/) { get; set; } | Ottiene o imposta l'ordine di tabulazione della pagina. Valori possibili: Row, Column. Predefinito, Manual |
| [TocInfo](../../aspose.pdf/page/tocinfo/) { get; set; } | Ottiene o imposta le informazioni dell'indice. |
| [TrimBox](../../aspose.pdf/page/trimbox/) { get; set; } | Ottiene o imposta il trim box della pagina. |
| [UserUnit](../../aspose.pdf/page/userunit/) { get; set; } | Ottiene o imposta il valore UserUnit. Un numero positivo che indica la dimensione delle unità di spazio utente predefinite, in multipli di 1/72 di pollice. Il valore predefinito è 1. Impostare zero o un valore negativo per cancellare questa voce nella pagina. |
| [Watermark](../../aspose.pdf/page/watermark/) { get; set; } | Ottiene o imposta il watermark della pagina. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Accept](../../aspose.pdf/page/accept/#accept)(AnnotationSelector) | Accetta l'oggetto visitor [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) che fornisce funzionalità per lavorare con le annotazioni. |
| [Accept](../../aspose.pdf/page/accept/#accept_1)(ImagePlacementAbsorber) | Accetta l'oggetto visitor [`ImagePlacementAbsorber`](../imageplacementabsorber/) che fornisce funzionalità per lavorare con gli oggetti di posizionamento immagine. |
| [Accept](../../aspose.pdf/page/accept/#accept_2)(TextAbsorber) | Accetta l'oggetto visitor [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) che fornisce funzionalità per lavorare con gli oggetti di testo. |
| [Accept](../../aspose.pdf/page/accept/#accept_3)(TextFragmentAbsorber) | Accetta l'oggetto visitor [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) che fornisce funzionalità per lavorare con gli oggetti di testo. |
| [AddGraphics](../../aspose.pdf/page/addgraphics/)(GraphicElementCollection, Rectangle) | Aggiunge grafica alla pagina. Funziona più velocemente rispetto all'aggiunta di elementi uno per uno con il metodo [`AddOnPage`](../../aspose.pdf.vector/graphicelement/addonpage/). |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_2)(string, Rectangle) | Aggiunge un'immagine alla pagina e la posiziona al centro del rettangolo specificato mantenendo le proporzioni dell'immagine. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage)(Stream, Rectangle, Rectangle, bool) | Aggiunge un'immagine alla pagina e la posiziona al centro del rettangolo specificato mantenendo le proporzioni dell'immagine. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_3)(string, Stream, Rectangle, Rectangle) | Aggiunge un'immagine ricercabile alla pagina e la posiziona al centro del rettangolo specificato mantenendo le proporzioni dell'immagine. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_1)(Stream, Rectangle, int, int, bool, Rectangle) | Aggiunge un'immagine alla pagina e la posiziona in base alla posizione del rettangolo dell'immagine. |
| [AddStamp](../../aspose.pdf/page/addstamp/)(Stamp) | Inserisce un timbro nella pagina. Il timbro può essere il numero di pagina, un'immagine o un semplice testo, ad es. un logo. |
| [AsByteArray](../../aspose.pdf/page/asbytearray/)(Resolution) | Converte la pagina corrente in bitmap e quindi restituisce un array di byte. |
| [AsXml](../../aspose.pdf/page/asxml/)() | Converte la pagina corrente in XML con codifica UTF-8. |
| [CalculateContentBBox](../../aspose.pdf/page/calculatecontentbbox/)() | Calcola il valore bbox - rettangolo che contiene i contenuti senza margini visibili. |
| [ConvertToPNGMemoryStream](../../aspose.pdf/page/converttopngmemorystream/)() | Converti la pagina in PNG per lo stream di immagini DSR, OMR, OCR. |
| [DeleteGraphics](../../aspose.pdf/page/deletegraphics/)(GraphicElementCollection) | Elimina la grafica dalla pagina. Funziona più velocemente rispetto all'eliminazione di elementi uno per uno con il metodo [`Remove`](../../aspose.pdf.vector/graphicelement/remove/). |
| [Dispose](../../aspose.pdf/page/dispose/)() | Libera la memoria |
| [Flatten](../../aspose.pdf/page/flatten/)() | Rimuove tutti i campi presenti nella pagina e ne colloca i valori al loro posto. |
| [FreeMemory](../../aspose.pdf/page/freememory/)() | Cancella i dati memorizzati nella cache |
| [GetNotifications](../../aspose.pdf/page/getnotifications/)() | Restituisce notifiche sulle operazioni interne con il contenuto della pagina. (Attualmente sono supportate solo le notifiche sugli eventi dei paragrafi negli scenari di aggiunta di testo.) |
| [GetPageRect](../../aspose.pdf/page/getpagerect/)(bool) | Restituisce il rettangolo della pagina in base al suo CropBox (o MediaBox se CropBox è nullo). |
| [GetResources](../../aspose.pdf/page/getresources/)() | Recupera le risorse associate alla pagina. |
| [HasVectorGraphics](../../aspose.pdf/page/hasvectorgraphics/)() | Rileva la presenza di grafica vettoriale, se è presente nella pagina. |
| [IsBlank](../../aspose.pdf/page/isblank/)(double) | Ottiene l'indicatore se la pagina è vuota o meno. |
| [MakeGrayscale](../../aspose.pdf/page/makegrayscale/)() | Converte la pagina in scala di grigi. |
| [MergeLayers](../../aspose.pdf/page/mergelayers/#mergelayers)(string) | Unisce tutti i livelli della pagina in un unico livello con il nome del nuovo livello specificato. |
| [MergeLayers](../../aspose.pdf/page/mergelayers/#mergelayers_1)(string, string) | Unisce tutti i livelli della pagina in un unico livello con il nome del nuovo livello specificato e l'ID opzionale del gruppo di contenuti. |
| [Resize](../../aspose.pdf/page/resize/)(PageSize) | Ridimensiona la pagina. |
| [SendTo](../../aspose.pdf/page/sendto/#sendto)(PageDevice, Stream) | Invia la pagina da elaborare con il dispositivo di pagina fornito. |
| [SendTo](../../aspose.pdf/page/sendto/#sendto_1)(PageDevice, string) | Invia la pagina da elaborare con il dispositivo di pagina fornito. |
| [SetPageSize](../../aspose.pdf/page/setpagesize/)(double, double) | Imposta la dimensione della pagina per la pagina. |
| [TrySaveVectorGraphics](../../aspose.pdf/page/trysavevectorgraphics/)(string) | Cerca di salvare la grafica vettoriale se è presente nella pagina. Il formato di salvataggio è SVG. |
| static [IntToRotation](../../aspose.pdf/page/inttorotation/)(int) | Traduce il valore intero nel membro corrispondente dell'enumerazione di rotazione. |
| static [RotationToInt](../../aspose.pdf/page/rotationtoint/)(Rotation) | Traduce il membro dell'enumerazione di rotazione in valore intero. |

## Eventi

| Nome | Descrizione |
| --- | --- |
| event [OnBeforePageGenerate](../../aspose.pdf/page/onbeforepagegenerate/) | Evento per personalizzare intestazione e piè di pagina. |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| delegate [BeforePageGenerate](../../aspose.pdf/page.beforepagegenerate) | Procedura per personalizzare intestazione e piè di pagina. |

### Vedi anche

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


