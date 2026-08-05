---
title: "ImageCompressionOptions"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "La classe contiene un insieme di opzioni per la compressione delle immagini."
type: docs
weight: 10
url: /it/python-net/aspose.pdf.optimization/imagecompressionoptions/
---

## ImageCompressionOptions class

La classe contiene un insieme di opzioni per la compressione delle immagini.

Il tipo ImageCompressionOptions espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| ImageCompressionOptions() | Inizializza una nuova istanza della classe ImageCompressionOptions |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| compress_images | Se questo flag è impostato su true, le immagini saranno compresse nel documento. Il livello di compressione è specificato con la proprietà ImageQuality. |
| resize_images | Se questo flag è impostato su true e CompressImages è true, le immagini saranno ridimensionate se la risoluzione dell'immagine è maggiore del parametro MaxResolution specificato. |
| image_quality | Specifica il livello di compressione dell'immagine quando viene utilizzato il flag CompressIamges. |
| max_resolution | Specifica la risoluzione massima delle immagini. Se l'immagine ha una risoluzione più alta, verrà ridimensionata. |
| version | Versione dell'algoritmo di compressione. I valori possibili sono: 1. compressione standard, 2. veloce (compressione migliorata che è più veloce della standard ma potrebbe non essere applicabile a tutte le immagini), 3. mista (la compressione standard è applicata alle immagini che non possono essere compresse dall'algoritmo più veloce, questo può fornire la migliore compressione ma è più lenta rispetto all'algoritmo "fast". La versione "Fast" non è applicabile al ridimensionamento delle immagini (verrà utilizzato il metodo standard). Il valore predefinito è "Standard". |
| encoding | Ottiene o imposta la codifica utilizzata per memorizzare le immagini. |

### Vedi anche

* namespace [aspose.pdf.optimization](/pdf/python-net/aspose.pdf.optimization/)
* assembly [Aspose.PDF](/pdf/python-net/)

