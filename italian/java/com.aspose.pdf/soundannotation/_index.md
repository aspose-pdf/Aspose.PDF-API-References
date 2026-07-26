---
title: "SoundAnnotation"
linktitle: "SoundAnnotation"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta un'annotazione audio che contiene suono registrato dal microfono del computer o importato da un file."
type: docs
weight: 4530
url: /it/java/com.aspose.pdf/soundannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.SoundAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.SoundAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.SoundAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.SoundAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class SoundAnnotation extends MarkupAnnotation
```

Rappresenta un'annotazione audio che contiene suono registrato dal microfono del computer o importato da un file.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SoundAnnotation](#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-) | Crea una nuova annotazione Sound nella pagina specificata. |
| [SoundAnnotation](#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-com.aspose.pdf.SoundSampleData-) | Crea una nuova annotazione Sound nella pagina specificata. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accetta un oggetto visitor per elaborare l'annotazione. |
| [getAnnotationType](#getAnnotationType--) | Ottiene il tipo di annotazione. |
| [getIcon](#getIcon--) | Ottiene un'icona da utilizzare nella visualizzazione dell'annotazione. |
| [getSoundData](#getSoundData--) | Ottiene un oggetto audio che definisce il suono da riprodurre quando l'annotazione è attivata. |
| [setIcon](#setIcon-int-) | Imposta un'icona da utilizzare nella visualizzazione dell'annotazione. |

### SoundAnnotation {#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-}
Crea una nuova annotazione Sound nella pagina specificata.

### SoundAnnotation {#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-com.aspose.pdf.SoundSampleData-}
Crea una nuova annotazione Sound nella pagina specificata.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accetta un oggetto visitor per elaborare l'annotazione.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Ottiene il tipo di annotazione.

**Returns:**
Valore AnnotationType @see AnnotationType

### getIcon {#getIcon--}
```
public int getIcon()
```

Ottiene un'icona da utilizzare nella visualizzazione dell'annotazione.

**Returns:**
Valore SoundIcon @see SoundIcon

### getSoundData {#getSoundData--}
```
public SoundData getSoundData()
```

Ottiene un oggetto audio che definisce il suono da riprodurre quando l'annotazione è attivata.

**Returns:**
Valore SoundData

### setIcon {#setIcon-int-}
```
public void setIcon(int value)
```

Imposta un'icona da utilizzare nella visualizzazione dell'annotazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Valore SoundIcon @see SoundIcon |
