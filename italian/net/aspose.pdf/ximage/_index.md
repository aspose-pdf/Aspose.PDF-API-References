---
title: "Classe XImage"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.XImage. Classe che rappresenta un XObject immagine"
type: docs
weight: 11540
url: /it/net/aspose.pdf/ximage/
---
## XImage class

Classe che rappresenta l'X-Object immagine.

```csharp
public sealed class XImage
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ContainsTransparency](../../aspose.pdf/ximage/containstransparency/) { get; } | Se l'immagine contiene trasparenza restituisce true; altrimenti, false. |
| [FilterType](../../aspose.pdf/ximage/filtertype/) { get; } | Ottiene il tipo di filtro dell'immagine. |
| [Grayscaled](../../aspose.pdf/ximage/grayscaled/) { get; } | Ottiene la versione in scala di grigi dell'immagine. |
| [Height](../../aspose.pdf/ximage/height/) { get; } | Ottiene l'altezza dell'immagine. |
| [ImageMask](../../aspose.pdf/ximage/imagemask/) { get; } | Ottiene un flag che indica se l'immagine deve essere trattata come una maschera immagine (vedi 8.9.6, "Masked Images"). Se questo flag è true, il valore di BitsPerComponent deve essere 1 e Mask e ColorSpace non devono essere specificati; le aree non mascherate devono essere dipinte usando il colore corrente non di riempimento. Valore predefinito: false. |
| [Metadata](../../aspose.pdf/ximage/metadata/) { get; } | Metadati dell'immagine. |
| [Name](../../aspose.pdf/ximage/name/) { get; set; } | Ottiene o imposta il nome dell'immagine. Si prega di notare che se si cambia il nome dell'immagine che ha riferimenti nei contenuti della pagina, il documento potrebbe diventare non corretto. Si prega di usare il metodo **XImage.Rename** in questo caso. |
| [Width](../../aspose.pdf/ximage/width/) { get; } | Ottiene la larghezza dell'immagine. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddStencilMask](../../aspose.pdf/ximage/addstencilmask/)(Stream) | Aggiunge una maschera stencil al XImage. |
| [GetAlternativeText](../../aspose.pdf/ximage/getalternativetext/)(Page) | Restituisce un elenco di stringhe con Testo Alternativo per un XImage. |
| [GetColorType](../../aspose.pdf/ximage/getcolortype/)() | Restituisce il tipo di colore dell'immagine. |
| [GetNameInCollection](../../aspose.pdf/ximage/getnameincollection/)() | Restituisce il nome dell'immagine nella sua collezione. |
| [GetRawImageData](../../aspose.pdf/ximage/getrawimagedata/)() | Recupera i dati grezzi dell'immagine dall'immagine di origine. |
| [IsTheSameObject](../../aspose.pdf/ximage/isthesameobject/)(XImage) | Restituisce true se entrambe le immagini fanno riferimento allo stesso oggetto. |
| [Rename](../../aspose.pdf/ximage/rename/)(string) | Rinomina l'immagine e sostituisce tutti i riferimenti all'immagine con il nuovo nome |
| [Save](../../aspose.pdf/ximage/save/#save)(Stream) | Salva i dati dell'immagine nello stream come immagine JPEG. |
| [Save](../../aspose.pdf/ximage/save/#save_2)(Stream, ImageFormat) | Salva l'immagine nello stream con il formato richiesto. |
| [Save](../../aspose.pdf/ximage/save/#save_1)(Stream, int) | Salva i dati dell'immagine nello stream come immagine JPEG con risoluzione specificata. |
| [Save](../../aspose.pdf/ximage/save/#save_3)(Stream, ImageFormat, int) | Salva l'immagine nello stream con il formato richiesto e con risoluzione specificata. |
| [ToStream](../../aspose.pdf/ximage/tostream/)() | Restituisce lo stream originale dell'immagine. |
| [TrySetAlternativeText](../../aspose.pdf/ximage/trysetalternativetext/)(string, Page) | Imposta il testo alternativo per un XImage nella pagina. |
| static [DetectColorType](../../aspose.pdf/ximage/detectcolortype/)(Bitmap) |  |

### Vedi anche

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


