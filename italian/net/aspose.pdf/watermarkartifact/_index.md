---
title: Class WatermarkArtifact
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.WatermarkArtifact. La classe descrive l'artefatto watermark. Questo può essere utilizzato per
type: docs
weight: 11310
url: /it/net/aspose.pdf/watermarkartifact/
---
## Classe WatermarkArtifact

La classe descrive l'artefatto watermark. Questo può essere utilizzato per

```csharp
public class WatermarkArtifact : Artifact
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [WatermarkArtifact](watermarkartifact/)() | Crea un'istanza dell'artefatto Watermark. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | Allineamento orizzontale dell'artefatto. Se la posizione è specificata esplicitamente (nella proprietà Position) questo valore viene ignorato. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | Allineamento verticale dell'artefatto. Se la posizione è specificata esplicitamente (nella proprietà Position) questo valore viene ignorato. |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | Margine inferiore dell'artefatto. Se la posizione è specificata esplicitamente (nella proprietà Position) questo valore viene ignorato. |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | Ottiene la collezione degli operatori interni dell'artefatto. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | Ottiene il nome del sottotipo dell'artefatto. Può essere utilizzato se il sottotipo dell'artefatto non è un sottotipo standard. |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | Ottiene il nome del tipo di artefatto. Può essere utilizzato se il tipo di artefatto non è standard. |
| [Form](../../aspose.pdf/artifact/form/) { get; } | Ottiene l'XForm dell'artefatto (se l'XForm è utilizzato). |
| [Image](../../aspose.pdf/artifact/image/) { get; } | Ottiene l'immagine dell'artefatto (se presente). |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | Se vero, l'artefatto è posizionato dietro i contenuti della pagina. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | Margine sinistro dell'artefatto. Se la posizione è specificata esplicitamente (nella proprietà Position) questo valore viene ignorato. |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | Linee dell'artefatto di testo multilinea. |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | Ottiene o imposta l'opacità dell'artefatto. I valori possibili sono nell'intervallo 0..1. |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | Ottiene o imposta la posizione dell'artefatto. Se questa proprietà è specificata, allora i margini e gli allineamenti vengono ignorati. |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | Ottiene il rettangolo dell'artefatto. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | Margine destro dell'artefatto. Se la posizione è specificata esplicitamente (nella proprietà Position) questo valore viene ignorato. |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | Ottiene o imposta l'angolo di rotazione dell'artefatto. |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | Ottiene il sottotipo dell'artefatto. Se l'artefatto ha un sottotipo non standard, il nome del sottotipo può essere letto tramite CustomSubtype. |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | Ottiene il testo dell'artefatto. |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | Stato del testo per il testo dell'artefatto. |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | Margine superiore dell'artefatto. Se la posizione è specificata esplicitamente (nella proprietà Position) questo valore viene ignorato. |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | Ottiene il tipo di artefatto. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | Inizia aggiornamenti ritardati. Usa questa funzione se hai bisogno di apportare diverse modifiche allo stesso artefatto per migliorare le prestazioni. Di solito, gli operatori dell'artefatto vengono cambiati ogni volta che la proprietà dell'artefatto viene cambiata. Questo causa la modifica dei contenuti della pagina ogni volta che l'artefatto viene cambiato. Per evitare questo effetto, inserisci tutti gli aggiornamenti dell'artefatto tra le chiamate StartUpdates/SaveUpdates. Questo consente di modificare i contenuti della pagina solo una volta. |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | Dispose l'artefatto. |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | Ottiene il valore personalizzato dell'artefatto. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | Rimuove il valore personalizzato dall'artefatto. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | Salva tutti gli aggiornamenti nell'artefatto che sono stati effettuati dopo la chiamata a BeginUpdates(). |
| [SetImage](../../aspose.pdf/artifact/setimage/)(Stream) | Imposta l'immagine dell'artefatto. |
| [SetImage](../../aspose.pdf/artifact/setimage/)(string) | Imposta l'immagine dell'artefatto. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | Imposta il testo e le proprietà del testo dell'artefatto. Consente di specificare più righe. |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | Imposta quale stringa sarà sostituita con il numero di pagina. Il valore predefinito è #. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | Imposta la pagina PDF che è posizionata sulla pagina del documento come artefatto. |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | Imposta il testo dell'artefatto. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | Imposta il testo e le proprietà del testo dell'artefatto. |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | Imposta il valore personalizzato dell'artefatto. |

### Vedi Anche

* classe [Artifact](../artifact/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)