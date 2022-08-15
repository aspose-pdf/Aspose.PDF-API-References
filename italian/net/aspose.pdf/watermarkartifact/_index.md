---
title: WatermarkArtifact
second_title: Aspose.PDF per .NET API Reference
description: La classe descrive lartefatto filigrana. Questo può essere utilizzato per
type: docs
weight: 7360
url: /it/net/aspose.pdf/watermarkartifact/
---
## WatermarkArtifact class

La classe descrive l'artefatto filigrana. Questo può essere utilizzato per

```csharp
public class WatermarkArtifact : Artifact
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [WatermarkArtifact](watermarkartifact)() | Crea un'istanza dell'artefatto Watermark. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment) { get; set; } | Allineamento orizzontale dell'artefatto. Se la posizione è specificata in modo esplicito (nella proprietà Posizione) questo valore viene ignorato. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment) { get; set; } | Allineamento verticale dell'artefatto. Se la posizione è specificata in modo esplicito (nella proprietà Posizione) questo valore viene ignorato. |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin) { get; set; } | Margine inferiore dell'artefatto. Se la posizione è specificata in modo esplicito (nella proprietà Posizione) questo valore viene ignorato. |
| [Contents](../../aspose.pdf/artifact/contents) { get; } | Ottiene la raccolta di operatori interni degli artefatti. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype) { get; set; } | Ottiene il nome del sottotipo di artefatto. Può essere utilizzato se il sottotipo di artefatto non è un sottotipo standard. |
| [CustomType](../../aspose.pdf/artifact/customtype) { get; set; } | Ottiene il nome del tipo di artefatto. Può essere utilizzato se il tipo di artefatto non è standard. |
| [Form](../../aspose.pdf/artifact/form) { get; } | Ottiene XForm dell'artefatto (se viene utilizzato XForm). |
| [Image](../../aspose.pdf/artifact/image) { get; } | Ottiene l'immagine dell'artefatto (se presente). |
| [IsBackground](../../aspose.pdf/artifact/isbackground) { get; set; } | Se vero Artefatto è posizionato dietro il contenuto della pagina. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin) { get; set; } | Margine sinistro dell'artefatto. Se la posizione è specificata in modo esplicito (nella proprietà Posizione) questo valore viene ignorato. |
| [Lines](../../aspose.pdf/artifact/lines) { get; } | Righe di artefatto di testo multilinea. |
| [Opacity](../../aspose.pdf/artifact/opacity) { get; set; } | Ottiene o imposta l'opacità dell'artefatto. I valori possibili sono compresi nell'intervallo 0..1. |
| [Position](../../aspose.pdf/artifact/position) { get; set; } | Ottiene o imposta la posizione dell'artefatto. Se viene specificata questa proprietà, i margini e gli allineamenti vengono ignorati. |
| [Rectangle](../../aspose.pdf/artifact/rectangle) { get; } | Ottiene il rettangolo dell'artefatto. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin) { get; set; } | Margine destro dell'artefatto. Se la posizione è specificata in modo esplicito (nella proprietà Posizione) questo valore viene ignorato. |
| [Rotation](../../aspose.pdf/artifact/rotation) { get; set; } | Ottiene o imposta l'angolo di rotazione dell'artefatto. |
| [Subtype](../../aspose.pdf/artifact/subtype) { get; set; } | Ottiene il sottotipo di artefatto. Se l'artefatto ha un sottotipo non standard, il nome del sottotipo può essere letto tramite CustomSubtype. |
| [Text](../../aspose.pdf/artifact/text) { get; set; } | Ottiene il testo dell'artefatto. |
| [TextState](../../aspose.pdf/artifact/textstate) { get; set; } | Stato del testo per il testo dell'artefatto. |
| [TopMargin](../../aspose.pdf/artifact/topmargin) { get; set; } | Margine superiore dell'artefatto. Se la posizione è specificata in modo esplicito (nella proprietà Posizione) questo valore viene ignorato. |
| [Type](../../aspose.pdf/artifact/type) { get; set; } | Ottiene il tipo di artefatto. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates)() | Avvia aggiornamenti ritardati. Utilizzare questa funzione se è necessario apportare diverse modifiche allo stesso artefatto per migliorare le prestazioni. Solitamente gli operatori degli artefatti vengono modificati in qualsiasi momento quando la proprietà degli artefatti è stata modificata. Ciò provoca la modifica del contenuto della pagina ogni volta che l'artefatto è stato modificato. Per evitare questo effetto, inserisci tutti gli aggiornamenti degli artefatti tra le chiamate StartUpdates/SaveUpdates. Ciò consente di modificare il contenuto della pagina solo una volta. |
| [Dispose](../../aspose.pdf/artifact/dispose)() | Elimina l'artefatto. |
| [GetValue](../../aspose.pdf/artifact/getvalue)(string) | Ottiene il valore personalizzato dell'artefatto. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue)(string) | Rimuovi il valore personalizzato dall'artefatto. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates)() | Salva tutti gli aggiornamenti nell'artefatto che sono stati effettuati dopo la chiamata BeginUpdates(). |
| [SetImage](../../aspose.pdf/artifact/setimage)(Stream) | Imposta l'immagine dell'artefatto. |
| [SetImage](../../aspose.pdf/artifact/setimage)(string) | Imposta l'immagine dell'artefatto. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate)(string[], TextState) | Imposta il testo e le proprietà del testo dell'artefatto. Consente di specificare più righe. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage)(Page) | Imposta la pagina PDF che viene inserita nella pagina del documento come artefatto. |
| [SetText](../../aspose.pdf/artifact/settext)(FormattedText) | Imposta il testo dell'artefatto. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate)(string, TextState) | Imposta il testo e le proprietà del testo dell'artefatto. |
| [SetValue](../../aspose.pdf/artifact/setvalue)(string, string) | Imposta il valore personalizzato dell'artefatto. |

### Guarda anche

* class [Artifact](../artifact)
* spazio dei nomi [Aspose.Pdf](../../aspose.pdf)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
