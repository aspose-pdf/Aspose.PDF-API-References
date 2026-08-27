---
title: "ImagePlacementAbsorber"
linktitle: "ImagePlacementAbsorber"
second_title: "Riferimento API Aspose.PDF per Java"
description: "<p> Rappresenta un oggetto assorbitore di oggetti di posizionamento immagine. Esegue la ricerca degli utilizzi delle immagini e fornisce l'accesso ai risultati della ricerca tramite {@code."
type: docs
weight: 2340
url: /it/java/com.aspose.pdf/imageplacementabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ImagePlacementAbsorber

```
public final class ImagePlacementAbsorber extends Object
```

<p> Rappresenta un oggetto assorbitore di oggetti di posizionamento immagine. Esegue la ricerca degli utilizzi delle immagini e fornisce l'accesso ai risultati della ricerca tramite la collezione {@code ImagePlacementAbsorber.ImagePlacements}. </p> <hr> <pre> L'esempio dimostra come trovare le immagini nella prima pagina del documento PDF e ottenere le proprietà di posizionamento dell'immagine. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Display image placement properties for all placements for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { System.out.println("image width:" + imagePlacement.getRectangle().getWidth()); System.out.println("image height:" + imagePlacement.getRectangle().getHeight()); System.out.println("image LLX:" + imagePlacement.getRectangle(0).getX()); System.out.println("image LLY:" + imagePlacement.getRectangle.getY()); System.out.println("image horizontal resolution:" + imagePlacement.getResolution().getX()); System.out.println("image vertical resolution:" + imagePlacement.getResolution().getY()); } </pre> <hr> <p> L'oggetto {@code ImagePlacementAbsorber} è fondamentalmente utilizzato nello scenario di ricerca delle immagini. Quando la ricerca è completata le occorrenze sono rappresentate con oggetti {@code ImagePlacement} contenuti nella collezione {@code ImagePlacementAbsorber.ImagePlacements}. L'oggetto {@code ImagePlacement} fornisce l'accesso alle proprietà di posizionamento dell'immagine: dimensioni, risoluzione ecc. </p> La rotazione positiva dell'immagine è in senso antiorario, per la pagina è in senso orario. Qui, è necessario rappresentare l'angolo di rotazione dell'immagine, quindi sottraiamo l'angolo della pagina dall'angolo dell'immagine.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ImagePlacementAbsorber](#ImagePlacementAbsorber--) | Inizializza una nuova istanza dell'oggetto {@code ImagePlacementAbsorber}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getImagePlacements](#getImagePlacements--) | Ottiene la collezione di occorrenze di posizionamento immagine che sono presentate con oggetti {@code ImagePlacement}. |
| [isReadOnlyMode](#isReadOnlyMode--) | Ottiene/imposta la modalità di sola lettura per la collezione di operazioni di parsing. Può aiutare a prevenire eccezioni di out of memory. |
| [setReadOnlyMode](#setReadOnlyMode-boolean-) | Ottiene/imposta la modalità di sola lettura per la collezione di operazioni di parsing. Può aiutare a prevenire eccezioni di out of memory. |
| [visit](#visit-com.aspose.pdf.IDocument-) | Esegue la ricerca sul documento specificato. |
| [visit](#visit-com.aspose.pdf.Page-) | Esegue la ricerca nella pagina specificata. |

### ImagePlacementAbsorber {#ImagePlacementAbsorber--}
```
public ImagePlacementAbsorber()
```

Inizializza una nuova istanza dell'oggetto {@code ImagePlacementAbsorber}.

### getImagePlacements {#getImagePlacements--}
```
public ImagePlacementCollection getImagePlacements()
```

Ottiene la collezione di occorrenze di posizionamento immagine che sono presentate con oggetti {@code ImagePlacement}.

**Returns:**
oggetto ImagePlacementCollection

### isReadOnlyMode {#isReadOnlyMode--}
```
public final boolean isReadOnlyMode()
```

Ottiene/imposta la modalità di sola lettura per la collezione di operazioni di parsing. Può aiutare a prevenire eccezioni di out of memory.

**Returns:**
valore booleano

### setReadOnlyMode {#setReadOnlyMode-boolean-}
```
public final void setReadOnlyMode(boolean value)
```

Ottiene/imposta la modalità di sola lettura per la collezione di operazioni di parsing. Può aiutare a prevenire eccezioni di out of memory.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### visit {#visit-com.aspose.pdf.IDocument-}
Esegue la ricerca sul documento specificato.

### visit {#visit-com.aspose.pdf.Page-}
Esegue la ricerca nella pagina specificata.
