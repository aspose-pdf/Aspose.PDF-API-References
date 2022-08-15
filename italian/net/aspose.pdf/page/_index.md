---
title: Page
second_title: Aspose.PDF per .NET API Reference
description: Classe che rappresenta la pagina del documento PDF.
type: docs
weight: 5790
url: /it/net/aspose.pdf/page/
---
## Page class

Classe che rappresenta la pagina del documento PDF.

```csharp
public sealed class Page : IDisposable
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Actions](../../aspose.pdf/page/actions) { get; } | Ottiene la raccolta delle proprietà della pagina. |
| [Annotations](../../aspose.pdf/page/annotations) { get; } | Ottiene la raccolta di annotazioni di pagina. [`Annotations`](./annotations) |
| [ArtBox](../../aspose.pdf/page/artbox) { get; set; } | Ottiene o imposta il riquadro artistico della pagina. |
| [Artifacts](../../aspose.pdf/page/artifacts) { get; } | Ottiene la raccolta di artefatti nella pagina. |
| [Background](../../aspose.pdf/page/background) { get; set; } | Ottiene o imposta il colore di sfondo della pagina. |
| [BackgroundImage](../../aspose.pdf/page/backgroundimage) { get; set; } | Ottiene o imposta l'immagine di sfondo per la pagina (solo per il generatore). |
| [BleedBox](../../aspose.pdf/page/bleedbox) { get; set; } | Ottiene o imposta il riquadro al vivo della pagina. |
| [ColorType](../../aspose.pdf/page/colortype) { get; } | Imposta il tipo di colore delle pagine in base alle informazioni ottenute dagli operatori SetColor, immagini e moduli. |
| [Contents](../../aspose.pdf/page/contents) { get; } | Ottiene la raccolta di operatori nel flusso di contenuto della pagina. [`OperatorCollection`](../operatorcollection) |
| [CropBox](../../aspose.pdf/page/cropbox) { get; set; } | Ottiene o imposta la casella di ritaglio della pagina. |
| [Duration](../../aspose.pdf/page/duration) { get; set; } | Ottiene la durata di visualizzazione della pagina impostata. Questo è il tempo in secondi che la pagina deve essere visualizzata durante la presentazione. Returs -1 se la durata non è definita. |
| [FieldsInTabOrder](../../aspose.pdf/page/fieldsintaborder) { get; } | Ottiene l'elenco degli oggetti Campo in ordine di tabulazione in questa pagina. |
| [Footer](../../aspose.pdf/page/footer) { get; set; } | Ottiene o imposta il piè di pagina della pagina. |
| [Group](../../aspose.pdf/page/group) { get; set; } | Ottiene o imposta una classe di attributi di gruppo che specifica gli attributi del gruppo di pagine della pagina da utilizzare nel modello di imaging trasparente. |
| [Header](../../aspose.pdf/page/header) { get; set; } | Ottiene o imposta l'intestazione della pagina. |
| [IsAddParagraphsAfterLast](../../aspose.pdf/page/isaddparagraphsafterlast) { get; set; } | Ottiene o imposta l'aggiunta di paragrafi dopo l'ultimo paragrafo della pagina |
| [Layers](../../aspose.pdf/page/layers) { get; set; } | Ottiene o imposta la raccolta di livelli. |
| [MediaBox](../../aspose.pdf/page/mediabox) { get; set; } | Ottiene o imposta il riquadro multimediale della pagina. |
| [NoteLineStyle](../../aspose.pdf/page/notelinestyle) { get; set; } | Ottiene o imposta lo stile della linea per le note.(solo per il generatore) |
| [Number](../../aspose.pdf/page/number) { get; } | Ottieni il numero della pagina. |
| [PageInfo](../../aspose.pdf/page/pageinfo) { get; set; } | Ottiene o imposta le informazioni sulla pagina (solo per il generatore, non compilate durante la lettura del file). |
| [Paragraphs](../../aspose.pdf/page/paragraphs) { get; set; } | Ottiene i paragrafi. |
| [Rect](../../aspose.pdf/page/rect) { get; set; } | Ottiene o imposta il rettangolo della pagina. La casella di ritaglio della pagina viene restituita se specificata, altrimenti viene restituita la casella di ritaglio della pagina. Si prega di notare che questa proprietà non considera la rotazione della pagina. Per ottenere il rettangolo della pagina considerando la rotazione, utilizzare ActualRect. |
| [Resources](../../aspose.pdf/page/resources) { get; } | Ottiene le risorse della pagina. L'oggetto Risorse contiene raccolte di immagini, moduli e caratteri. [`Resources`](./resources) |
| [Rotate](../../aspose.pdf/page/rotate) { get; set; } | Ottiene o imposta la rotazione della pagina. |
| [RotationMatrix](../../aspose.pdf/page/rotationmatrix) { get; } | Ottiene la matrice di trasformazione per la pagina. |
| [TabOrder](../../aspose.pdf/page/taborder) { get; set; } | Ottiene o imposta l'ordine di tabulazione della pagina. Valori possibili: Riga, Colonna. Predefinito, Manuale |
| [TocInfo](../../aspose.pdf/page/tocinfo) { get; set; } | Ottiene o imposta le informazioni sul sommario. |
| [TrimBox](../../aspose.pdf/page/trimbox) { get; set; } | Ottiene o imposta il riquadro di ritaglio della pagina. |
| [UserUnit](../../aspose.pdf/page/userunit) { get; set; } | Ottiene o imposta il valore UserUnit. Un numero positivo che fornisce la dimensione delle unità di spazio utente predefinite, in multipli di 1 ⁄ 72 pollici. Il valore predefinito è 1. Impostare zero o un valore negativo per cancellare questa voce nella pagina. |
| [Watermark](../../aspose.pdf/page/watermark) { get; set; } | Ottiene o imposta la filigrana della pagina. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Accept](../../aspose.pdf/page/accept#accept)(AnnotationSelector) | Accetta[`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector) oggetto visitatore che fornisce funzionalità per lavorare con le annotazioni. |
| [Accept](../../aspose.pdf/page/accept#accept_1)(ImagePlacementAbsorber) | Accetta[`ImagePlacementAbsorber`](../imageplacementabsorber) oggetto visitatore che fornisce funzionalità per lavorare con oggetti posizionamento immagine. |
| [Accept](../../aspose.pdf/page/accept#accept_2)(TextAbsorber) | Accetta[`TextAbsorber`](../../aspose.pdf.text/textabsorber) oggetto visitatore che fornisce funzionalità per lavorare con oggetti di testo. |
| [Accept](../../aspose.pdf/page/accept#accept_3)(TextFragmentAbsorber) | Accetta[`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber) oggetto visitatore che fornisce funzionalità per lavorare con oggetti di testo. |
| [AddImage](../../aspose.pdf/page/addimage#addimage)(Stream, Rectangle) | Aggiunge l'immagine alla pagina e la posiziona al centro del rettangolo specificato salvando la proporzione dell'immagine. |
| [AddImage](../../aspose.pdf/page/addimage#addimage_2)(string, Rectangle) | Aggiunge l'immagine alla pagina e la posiziona al centro del rettangolo specificato salvando la proporzione dell'immagine. |
| [AddImage](../../aspose.pdf/page/addimage#addimage_3)(string, Stream, Rectangle) | Aggiunge un'immagine ricercabile alla pagina e la individua al centro del rettangolo specificato salvando la proporzione dell'immagine. |
| [AddImage](../../aspose.pdf/page/addimage#addimage_1)(Stream, Rectangle, int, int, bool) | Aggiunge l'immagine alla pagina e la posiziona in base alla posizione del rettangolo dell'immagine. |
| [AddStamp](../../aspose.pdf/page/addstamp)(Stamp) | Metti il timbro nella pagina. Il timbro può essere un numero di pagina, un'immagine o un semplice testo, ad esempio un logo. |
| [AsByteArray](../../aspose.pdf/page/asbytearray)(Resolution) | Converte la pagina corrente come bitmap e quindi restituisce un array di byte. |
| [AsXml](../../aspose.pdf/page/asxml)() | Converte la pagina corrente come xml nella codifica utf8. |
| [CalculateContentBBox](../../aspose.pdf/page/calculatecontentbbox)() | Calcola il valore bbox - rettangolo contenente contenuto senza margini visibili. |
| [ConvertToPNGMemoryStream](../../aspose.pdf/page/converttopngmemorystream)() | Converti la pagina in PNG per il flusso di immagini DSR, OMR, OCR. |
| [Dispose](../../aspose.pdf/page/dispose)() | Libera memoria |
| [Flatten](../../aspose.pdf/page/flatten)() | Rimuove tutti i campi che si trovano nella pagina e ne inserisce i valori. |
| [FreeMemory](../../aspose.pdf/page/freememory)() | Cancella i dati memorizzati nella cache |
| [GetNotifications](../../aspose.pdf/page/getnotifications)() | Restituisce notifiche sulle operazioni interne con il contenuto della pagina. (Ora sono supportate solo le notifiche sugli eventi di paragrafo negli scenari di aggiunta di testo.) |
| [GetPageRect](../../aspose.pdf/page/getpagerect)(bool) | Restituisce il rettangolo della pagina. |
| [IsBlank](../../aspose.pdf/page/isblank)(double) | Ottiene il flag se la pagina è vuota o meno. |
| [MakeGrayscale](../../aspose.pdf/page/makegrayscale)() | Converte la pagina in scala di grigi. |
| [SendTo](../../aspose.pdf/page/sendto#sendto)(PageDevice, Stream) | Invia la pagina da elaborare con un determinato dispositivo di pagina. |
| [SendTo](../../aspose.pdf/page/sendto#sendto_1)(PageDevice, string) | Invia la pagina da elaborare con un determinato dispositivo di pagina. |
| [SetPageSize](../../aspose.pdf/page/setpagesize)(double, double) | Imposta la dimensione della pagina per la pagina. |
| static [IntToRotation](../../aspose.pdf/page/inttorotation)(int) | Converte il valore intero nel corrispondente membro dell'enumerazione della rotazione. |
| static [RotationToInt](../../aspose.pdf/page/rotationtoint)(Rotation) | Converte il membro dell'enumerazione della rotazione in un valore intero. |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| delegate [BeforePageGenerate](page.beforepagegenerate) | Procedura per personalizzare intestazione e piè di pagina. |

### Guarda anche

* spazio dei nomi [Aspose.Pdf](../../aspose.pdf)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
