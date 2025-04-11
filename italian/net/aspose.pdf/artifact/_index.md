---
title: Class Artifact
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Artifact. La classe rappresenta l'oggetto PDF Artifact
type: docs
weight: 2770
url: /it/net/aspose.pdf/artifact/
---
## Classe Artifact

La classe rappresenta l'oggetto PDF Artifact.

```csharp
public class Artifact : IDisposable
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Artifact](artifact/#constructor)(ArtifactType, ArtifactSubtype) | Costruttore di artifact con tipo e sottotipo specificati |
| [Artifact](artifact/#constructor_1)(string, string) | Costruttore di artifact con tipo e sottotipo specificati |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | Allineamento orizzontale dell'artifact. Se la posizione è specificata esplicitamente (nella proprietà Position) questo valore viene ignorato. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | Allineamento verticale dell'artifact. Se la posizione è specificata esplicitamente (nella proprietà Position) questo valore viene ignorato. |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | Margine inferiore dell'artifact. Se la posizione è specificata esplicitamente (nella proprietà Position) questo valore viene ignorato. |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | Ottiene la collezione degli operatori interni dell'artifact. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | Ottiene il nome del sottotipo dell'artifact. Può essere utilizzato se il sottotipo dell'artifact non è uno standard. |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | Ottiene il nome del tipo dell'artifact. Può essere utilizzato se il tipo dell'artifact non è standard. |
| [Form](../../aspose.pdf/artifact/form/) { get; } | Ottiene l'XForm dell'artifact (se l'XForm è utilizzato). |
| [Image](../../aspose.pdf/artifact/image/) { get; } | Ottiene l'immagine dell'artifact (se presente). |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | Se vero, l'Artifact è posizionato dietro i contenuti della pagina. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | Margine sinistro dell'artifact. Se la posizione è specificata esplicitamente (nella proprietà Position) questo valore viene ignorato. |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | Linee dell'artifact di testo multilinea. |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | Ottiene o imposta l'opacità dell'artifact. I valori possibili sono nell'intervallo 0..1. |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | Ottiene o imposta la posizione dell'artifact. Se questa proprietà è specificata, allora i margini e gli allineamenti vengono ignorati. |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | Ottiene il rettangolo dell'artifact. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | Margine destro dell'artifact. Se la posizione è specificata esplicitamente (nella proprietà Position) questo valore viene ignorato. |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | Ottiene o imposta l'angolo di rotazione dell'artifact. |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | Ottiene il sottotipo dell'artifact. Se l'artifact ha un sottotipo non standard, il nome del sottotipo può essere letto tramite CustomSubtype. |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | Ottiene il testo dell'artifact. |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | Stato del testo per il testo dell'artifact. |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | Margine superiore dell'artifact. Se la posizione è specificata esplicitamente (nella proprietà Position) questo valore viene ignorato. |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | Ottiene il tipo dell'artifact. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | Inizia aggiornamenti ritardati. Usa questa funzione se devi apportare diverse modifiche allo stesso artifact per migliorare le prestazioni. Di solito, gli operatori dell'artifact vengono cambiati ogni volta che una proprietà dell'artifact viene cambiata. Questo causa la modifica dei contenuti della pagina ogni volta che l'artifact viene cambiato. Per evitare questo effetto, metti tutti gli aggiornamenti dell'artifact tra le chiamate StartUpdates/SaveUpdates. Questo consente di cambiare i contenuti della pagina solo una volta. |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | Dispone l'artifact. |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | Ottiene il valore personalizzato dell'artifact. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | Rimuove il valore personalizzato dall'artifact. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | Salva tutti gli aggiornamenti nell'artifact che sono stati effettuati dopo la chiamata a BeginUpdates(). |
| [SetImage](../../aspose.pdf/artifact/setimage/#setimage)(Stream) | Imposta l'immagine dell'artifact. |
| [SetImage](../../aspose.pdf/artifact/setimage/#setimage_1)(string) | Imposta l'immagine dell'artifact. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | Imposta il testo e le proprietà del testo dell'artifact. Consente di specificare più righe. |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | Imposta quale stringa sarà sostituita con il numero di pagina. Il valore predefinito è #. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | Imposta la pagina PDF che è posizionata sulla pagina del documento come artifact. |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | Imposta il testo dell'artifact. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | Imposta il testo e le proprietà del testo dell'artifact. |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | Imposta il valore personalizzato dell'artifact. |

## Altri Membri

| Nome | Descrizione |
| --- | --- |
| enum [ArtifactSubtype](../../aspose.pdf/artifact.artifactsubtype) | Enumerazione dei possibili sottotipi di artifact. |
| enum [ArtifactType](../../aspose.pdf/artifact.artifacttype) | Enumerazione dei possibili tipi di artifact. |

### Vedi Anche

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)