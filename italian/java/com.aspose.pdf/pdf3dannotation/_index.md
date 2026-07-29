---
title: "PDF3DAnnotation"
linktitle: "PDF3DAnnotation"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe PDF3DAnnotation. Questa classe non può essere ereditata. @see Annotation"
type: docs
weight: 3560
url: /it/java/com.aspose.pdf/pdf3dannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PDF3DAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PDF3DAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PDF3DAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class PDF3DAnnotation extends Annotation
```

Classe PDF3DAnnotation. Questa classe non può essere ereditata. @see Annotation

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PDF3DAnnotation](#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-) | Inizializza una nuova istanza della classe {@code PDF3DAnnotation}. |
| [PDF3DAnnotation](#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-com.aspose.pdf.PDF3DActivation-) | Inizializza una nuova istanza della classe {@code PDF3DAnnotation}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accetta un visitor per l'elaborazione dell'annotazione. |
| [clearImagePreview](#clearImagePreview--) | Cancella l'anteprima dell'immagine. |
| [getAnnotationType](#getAnnotationType--) | Ottiene il tipo di annotazione. Valore: Il tipo dell'annotazione. |
| [getContent](#getContent--) | Ottiene o imposta il contenuto. Valore: Il contenuto. |
| [getImagePreview](#getImagePreview--) | Ottiene l'anteprima dell'immagine. |
| [getLightingScheme](#getLightingScheme--) | Ottiene lo schema di illuminazione. Valore: Lo schema di illuminazione. |
| [getPdf3DArtwork](#getPdf3DArtwork--) | Ottiene l'opera d'arte 3D. Valore: L'opera d'arte PDF3 d. |
| [getRenderMode](#getRenderMode--) | Ottiene la modalità di rendering. Valore: La modalità di rendering. |
| [getViewArray](#getViewArray--) | Ottiene l'array di visualizzazione. Valore: L'array di visualizzazione. |
| [setContent](#setContent-com.aspose.pdf.PDF3DContent-) | Ottiene o imposta il contenuto. Valore: Il contenuto. |
| [setDefaultViewIndex](#setDefaultViewIndex-int-) | Imposta l'indice della visualizzazione predefinita. |
| [setImagePreview](#setImagePreview-java.io.InputStream-) | Imposta l'anteprima dell'immagine. |
| [setImagePreview](#setImagePreview-java.lang.String-) | Imposta l'anteprima dell'immagine. |

### PDF3DAnnotation {#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-}
Inizializza una nuova istanza della classe {@code PDF3DAnnotation}.

### PDF3DAnnotation {#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-com.aspose.pdf.PDF3DActivation-}
Inizializza una nuova istanza della classe {@code PDF3DAnnotation}.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accetta un visitor per l'elaborazione dell'annotazione.

### clearImagePreview {#clearImagePreview--}
```
public void clearImagePreview()
```

Cancella l'anteprima dell'immagine.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Ottiene il tipo di annotazione. Valore: Il tipo dell'annotazione.

**Returns:**
valore int

### getContent {#getContent--}
```
public PDF3DContent getContent()
```

Ottiene o imposta il contenuto. Valore: Il contenuto.

**Returns:**
oggetto PDF3DContent

### getImagePreview {#getImagePreview--}
```
public InputStream getImagePreview()
```

Ottiene l'anteprima dell'immagine.

**Returns:**
Anteprima dell'immagine come stream.

### getLightingScheme {#getLightingScheme--}
```
public PDF3DLightingScheme getLightingScheme()
```

Ottiene lo schema di illuminazione. Valore: Lo schema di illuminazione.

**Returns:**
oggetto PDF3DLightingScheme

### getPdf3DArtwork {#getPdf3DArtwork--}
```
public PDF3DArtwork getPdf3DArtwork()
```

Ottiene l'opera d'arte 3D. Valore: L'opera d'arte PDF3 d.

**Returns:**
PDF3DArtwork oggetto

### getRenderMode {#getRenderMode--}
```
public PDF3DRenderMode getRenderMode()
```

Ottiene la modalità di rendering. Valore: La modalità di rendering.

**Returns:**
PDF3DRenderMode oggetto

### getViewArray {#getViewArray--}
```
public PDF3DViewArray getViewArray()
```

Ottiene l'array di visualizzazione. Valore: L'array di visualizzazione.

**Returns:**
PDF3DViewArray oggetto

### setContent {#setContent-com.aspose.pdf.PDF3DContent-}
Ottiene o imposta il contenuto. Valore: Il contenuto.

### setDefaultViewIndex {#setDefaultViewIndex-int-}
```
public void setDefaultViewIndex(int index)
```

Imposta l'indice della visualizzazione predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | L'indice di visualizzazione predefinito. |

### setImagePreview {#setImagePreview-java.io.InputStream-}
Imposta l'anteprima dell'immagine.

### setImagePreview {#setImagePreview-java.lang.String-}
Imposta l'anteprima dell'immagine.
