---
title: "AnnotationSelector"
linktitle: "AnnotationSelector"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Questa classe è usata per selezionare le annotazioni utilizzando l'idea del modello Visitor."
type: docs
weight: 100
url: /it/java/com.aspose.pdf/annotationselector/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AnnotationSelector

**All Implemented Interfaces:**
IAnnotationVisitor

```
public final class AnnotationSelector extends Object implements IAnnotationVisitor
```

Questa classe è usata per selezionare le annotazioni utilizzando l'idea del modello Visitor.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [AnnotationSelector](#AnnotationSelector--) | Inizializza una nuova istanza della classe AnnotationSelector. |
| [AnnotationSelector](#AnnotationSelector-com.aspose.pdf.Annotation-) | Inizializza una nuova istanza della classe AnnotationSelector. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSelected](#getSelected--) | L'elenco degli oggetti selezionati. |
| [visit](#visit-com.aspose.pdf.BleedMarkAnnotation-) | Seleziona il {@code bleedMark} se il {@link AnnotationSelector} è stato inizializzato con un oggetto {@link BleedMarkAnnotation}. |
| [visit](#visit-com.aspose.pdf.CaretAnnotation-) | Seleziona l'annotazione caret se AnnotationSelector è stato inizializzato con un oggetto CaretAnnotation. |
| [visit](#visit-com.aspose.pdf.CircleAnnotation-) | Seleziona l'annotazione cerchio se AnnotationSelector è stato inizializzato con un oggetto CircleAnnotation. |
| [visit](#visit-com.aspose.pdf.ColorBarAnnotation-) | Seleziona l'annotazione ColorBar se AnnotationSelector è stato inizializzato con un oggetto ColorBar. |
| [visit](#visit-com.aspose.pdf.FileAttachmentAnnotation-) | Seleziona l'annotazione allegato se AnnotationSelector è stato inizializzato con un oggetto FileAttachmentAnnotation. |
| [visit](#visit-com.aspose.pdf.FreeTextAnnotation-) | Seleziona l'annotazione testo libero se AnnotationSelector è stato inizializzato con un oggetto FreeTextAnnotation. |
| [visit](#visit-com.aspose.pdf.HighlightAnnotation-) | Seleziona l'annotazione allegato se AnnotationSelector è stato inizializzato con un oggetto FreeTextAnnotation. |
| [visit](#visit-com.aspose.pdf.InkAnnotation-) | Seleziona l'annotazione inchiostro se AnnotationSelector è stato inizializzato con un oggetto InkAnnotation. |
| [visit](#visit-com.aspose.pdf.LineAnnotation-) | Seleziona l'annotazione linea se AnnotationSelector è stato inizializzato con un oggetto LineAnnotation. |
| [visit](#visit-com.aspose.pdf.LinkAnnotation-) | Seleziona l'annotazione link se AnnotationSelector è stato inizializzato con un oggetto LinkAnnotation. |
| [visit](#visit-com.aspose.pdf.MovieAnnotation-) | Seleziona l'annotazione video se AnnotationSelector è stato inizializzato con un oggetto MovieAnnotation. |
| [visit](#visit-com.aspose.pdf.PageInformationAnnotation-) | Seleziona il {@code pageInformation} se il {@link AnnotationSelector} è stato inizializzato con un oggetto {@link PageInformationAnnotation}. |
| [visit](#visit-com.aspose.pdf.PDF3DAnnotation-) | Seleziona l'annotazione PDF3D se AnnotationSelector è stato inizializzato con un oggetto PDF3DAnnotation. |
| [visit](#visit-com.aspose.pdf.PolygonAnnotation-) | Seleziona l'annotazione poligono se AnnotationSelector è stato inizializzato con un oggetto PolygonAnnotation. |
| [visit](#visit-com.aspose.pdf.PolylineAnnotation-) | Seleziona l'annotazione polilinea se AnnotationSelector è stato inizializzato con l'oggetto PolylineAnnotation. |
| [visit](#visit-com.aspose.pdf.PopupAnnotation-) | Seleziona l'annotazione popup se AnnotationSelector è stato inizializzato con l'oggetto PopupAnnotation. |
| [visit](#visit-com.aspose.pdf.RedactionAnnotation-) | Seleziona l'annotazione di redazione se AnnotationSelector è stato inizializzato con l'oggetto RedactAnnotation. |
| [visit](#visit-com.aspose.pdf.RegistrationMarkAnnotation-) | Seleziona il {@code registrationMark} se il {@link AnnotationSelector} è stato inizializzato con un oggetto {@link RegistrationMarkAnnotation}. |
| [visit](#visit-com.aspose.pdf.RichMediaAnnotation-) | Seleziona l'annotazione video se AnnotationSelector è stato inizializzato con l'oggetto RichMedia annotation. |
| [visit](#visit-com.aspose.pdf.ScreenAnnotation-) | Seleziona l'annotazione schermo se AnnotationSelector è stato inizializzato con l'oggetto ScreenAnnotation. |
| [visit](#visit-com.aspose.pdf.SquareAnnotation-) | Seleziona l'annotazione quadrata se AnnotationSelector è stato inizializzato con l'oggetto SquareAnnotation. |
| [visit](#visit-com.aspose.pdf.SquigglyAnnotation-) | Seleziona l'annotazione ondulata se AnnotationSelector è stato inizializzato con l'oggetto SquigglyAnnotation. |
| [visit](#visit-com.aspose.pdf.StampAnnotation-) | Seleziona l'annotazione timbro se AnnotationSelector è stato inizializzato con l'oggetto StampAnnotation. |
| [visit](#visit-com.aspose.pdf.StrikeOutAnnotation-) | Seleziona l'annotazione barrata se AnnotationSelector è stato inizializzato con l'oggetto StrikeOutAnnotation. |
| [visit](#visit-com.aspose.pdf.TextAnnotation-) | Seleziona l'annotazione testo se AnnotationSelector è stato inizializzato con l'oggetto TextAnnotation. |
| [visit](#visit-com.aspose.pdf.TrimMarkAnnotation-) | Seleziona il {@code trimMark} se il {@link AnnotationSelector} è stato inizializzato con un oggetto {@link TrimMarkAnnotation}. |
| [visit](#visit-com.aspose.pdf.UnderlineAnnotation-) | Seleziona l'annotazione sottolineata se AnnotationSelector è stato inizializzato con l'oggetto UnderlineAnnotation. |
| [visit](#visit-com.aspose.pdf.WatermarkAnnotation-) | Seleziona l'annotazione filigrana se AnnotationSelector è stato inizializzato con l'oggetto WatermarkAnnotation. |
| [visit](#visit-com.aspose.pdf.WidgetAnnotation-) | Seleziona l'annotazione widget se AnnotationSelector è stato inizializzato con l'oggetto WidgetAnnotation. |

### AnnotationSelector {#AnnotationSelector--}
```
public AnnotationSelector()
```

Inizializza una nuova istanza della classe AnnotationSelector.

### AnnotationSelector {#AnnotationSelector-com.aspose.pdf.Annotation-}
Inizializza una nuova istanza della classe AnnotationSelector.

### getSelected {#getSelected--}
```
public List < Annotation > getSelected()
```

L'elenco degli oggetti selezionati.

**Returns:**
Elenco delle istanze di Annotation

### visit {#visit-com.aspose.pdf.BleedMarkAnnotation-}
Seleziona il {@code bleedMark} se il {@link AnnotationSelector} è stato inizializzato con un oggetto {@link BleedMarkAnnotation}.

### visit {#visit-com.aspose.pdf.CaretAnnotation-}
Seleziona l'annotazione caret se AnnotationSelector è stato inizializzato con un oggetto CaretAnnotation.

### visit {#visit-com.aspose.pdf.CircleAnnotation-}
Seleziona l'annotazione cerchio se AnnotationSelector è stato inizializzato con un oggetto CircleAnnotation.

### visit {#visit-com.aspose.pdf.ColorBarAnnotation-}
Seleziona l'annotazione ColorBar se AnnotationSelector è stato inizializzato con un oggetto ColorBar.

### visit {#visit-com.aspose.pdf.FileAttachmentAnnotation-}
Seleziona l'annotazione allegato se AnnotationSelector è stato inizializzato con un oggetto FileAttachmentAnnotation.

### visit {#visit-com.aspose.pdf.FreeTextAnnotation-}
Seleziona l'annotazione testo libero se AnnotationSelector è stato inizializzato con un oggetto FreeTextAnnotation.

### visit {#visit-com.aspose.pdf.HighlightAnnotation-}
Seleziona l'annotazione allegato se AnnotationSelector è stato inizializzato con un oggetto FreeTextAnnotation.

### visit {#visit-com.aspose.pdf.InkAnnotation-}
Seleziona l'annotazione inchiostro se AnnotationSelector è stato inizializzato con un oggetto InkAnnotation.

### visit {#visit-com.aspose.pdf.LineAnnotation-}
Seleziona l'annotazione linea se AnnotationSelector è stato inizializzato con un oggetto LineAnnotation.

### visit {#visit-com.aspose.pdf.LinkAnnotation-}
Seleziona l'annotazione link se AnnotationSelector è stato inizializzato con un oggetto LinkAnnotation.

### visit {#visit-com.aspose.pdf.MovieAnnotation-}
Seleziona l'annotazione video se AnnotationSelector è stato inizializzato con un oggetto MovieAnnotation.

### visit {#visit-com.aspose.pdf.PageInformationAnnotation-}
Seleziona il {@code pageInformation} se il {@link AnnotationSelector} è stato inizializzato con un oggetto {@link PageInformationAnnotation}.

### visit {#visit-com.aspose.pdf.PDF3DAnnotation-}
Seleziona l'annotazione PDF3D se AnnotationSelector è stato inizializzato con un oggetto PDF3DAnnotation.

### visit {#visit-com.aspose.pdf.PolygonAnnotation-}
Seleziona l'annotazione poligono se AnnotationSelector è stato inizializzato con un oggetto PolygonAnnotation.

### visit {#visit-com.aspose.pdf.PolylineAnnotation-}
Seleziona l'annotazione polilinea se AnnotationSelector è stato inizializzato con l'oggetto PolylineAnnotation.

### visit {#visit-com.aspose.pdf.PopupAnnotation-}
Seleziona l'annotazione popup se AnnotationSelector è stato inizializzato con l'oggetto PopupAnnotation.

### visit {#visit-com.aspose.pdf.RedactionAnnotation-}
Seleziona l'annotazione di redazione se AnnotationSelector è stato inizializzato con l'oggetto RedactAnnotation.

### visit {#visit-com.aspose.pdf.RegistrationMarkAnnotation-}
Seleziona il {@code registrationMark} se il {@link AnnotationSelector} è stato inizializzato con un oggetto {@link RegistrationMarkAnnotation}.

### visit {#visit-com.aspose.pdf.RichMediaAnnotation-}
Seleziona l'annotazione video se AnnotationSelector è stato inizializzato con l'oggetto RichMedia annotation.

### visit {#visit-com.aspose.pdf.ScreenAnnotation-}
Seleziona l'annotazione schermo se AnnotationSelector è stato inizializzato con l'oggetto ScreenAnnotation.

### visit {#visit-com.aspose.pdf.SquareAnnotation-}
Seleziona l'annotazione quadrata se AnnotationSelector è stato inizializzato con l'oggetto SquareAnnotation.

### visit {#visit-com.aspose.pdf.SquigglyAnnotation-}
Seleziona l'annotazione ondulata se AnnotationSelector è stato inizializzato con l'oggetto SquigglyAnnotation.

### visit {#visit-com.aspose.pdf.StampAnnotation-}
Seleziona l'annotazione timbro se AnnotationSelector è stato inizializzato con l'oggetto StampAnnotation.

### visit {#visit-com.aspose.pdf.StrikeOutAnnotation-}
Seleziona l'annotazione barrata se AnnotationSelector è stato inizializzato con l'oggetto StrikeOutAnnotation.

### visit {#visit-com.aspose.pdf.TextAnnotation-}
Seleziona l'annotazione testo se AnnotationSelector è stato inizializzato con l'oggetto TextAnnotation.

### visit {#visit-com.aspose.pdf.TrimMarkAnnotation-}
Seleziona il {@code trimMark} se il {@link AnnotationSelector} è stato inizializzato con un oggetto {@link TrimMarkAnnotation}.

### visit {#visit-com.aspose.pdf.UnderlineAnnotation-}
Seleziona l'annotazione sottolineata se AnnotationSelector è stato inizializzato con l'oggetto UnderlineAnnotation.

### visit {#visit-com.aspose.pdf.WatermarkAnnotation-}
Seleziona l'annotazione filigrana se AnnotationSelector è stato inizializzato con l'oggetto WatermarkAnnotation.

### visit {#visit-com.aspose.pdf.WidgetAnnotation-}
Seleziona l'annotazione widget se AnnotationSelector è stato inizializzato con l'oggetto WidgetAnnotation.
