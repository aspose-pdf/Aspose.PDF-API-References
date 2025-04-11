---
title: Class PdfAnnotationEditor
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfAnnotationEditor. Rappresenta una classe per lavorare con i commenti delle annotazioni dei documenti PDF
type: docs
weight: 4410
url: /it/net/aspose.pdf.facades/pdfannotationeditor/
---
## Classe PdfAnnotationEditor

Rappresenta una classe per lavorare con le annotazioni (commenti) dei documenti PDF.

```csharp
public sealed class PdfAnnotationEditor : SaveableFacade
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfAnnotationEditor](pdfannotationeditor/#constructor)() | Inizializza un nuovo oggetto `PdfAnnotationEditor`. |
| [PdfAnnotationEditor](pdfannotationeditor/#constructor_1)(Document) | Inizializza un nuovo oggetto `PdfAnnotationEditor` sulla base del *documento*. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Ottiene il facciata del documento su cui si sta lavorando. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inizializza la facciata. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Inizializza la facciata. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Inizializza la facciata. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Smaltisce Aspose.Pdf.Document legato a una facciata. |
| [DeleteAnnotation](../../aspose.pdf.facades/pdfannotationeditor/deleteannotation/)(string) | Elimina l'annotazione con il nome specificato. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations/#deleteannotations)() | Elimina tutte le annotazioni nel documento. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations/#deleteannotations_1)(string) | Elimina tutte le annotazioni del tipo specificato nel documento. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Smaltisce la facciata. |
| [ExportAnnotationsToXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationstoxfdf/)(Stream) | Esporta le annotazioni nello stream. |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/#exportannotationsxfdf)(Stream, int, int, AnnotationType[]) | Esporta il contenuto dei tipi di annotazione specificati in XFDF |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/#exportannotationsxfdf_1)(Stream, int, int, string[]) | Esporta il contenuto dei tipi di annotazione specificati in XFDF |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations/#extractannotations)(int, int, AnnotationType[]) | Ottiene l'elenco delle annotazioni dei tipi specificati. |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations/#extractannotations_1)(int, int, string[]) | Ottiene l'elenco delle annotazioni dei tipi specificati. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations)() | Appiattisce tutte le annotazioni nel documento. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations_1)(FlattenSettings) | Appiattisce tutte le annotazioni nel documento. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations_2)(int, int, AnnotationType[]) | Appiattisce le annotazioni dei tipi specificati. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/#importannotationfromxfdf_1)(Stream, AnnotationType[]) | Importa le annotazioni specificate dal flusso di dati XFDF. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/#importannotationfromxfdf_3)(string, AnnotationType[]) | Importa le annotazioni specificate dal file XFDF. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations)(Stream[]) | Importa annotazioni nel documento da un array di flussi di altri documenti PDF. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_2)(string[]) | Importa annotazioni nel documento da un array di altri documenti PDF. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_1)(Stream[], AnnotationType[]) | Importa le annotazioni specificate nel documento da un array di flussi di altri documenti PDF. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_3)(string[], AnnotationType[]) | Importa le annotazioni specificate nel documento da un array di altri documenti PDF. |
| [ImportAnnotationsFromFdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/)(string) | Importa tutte le annotazioni dal file FDF. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/#importannotationsfromxfdf)(Stream) | Importa tutte le annotazioni dal flusso di dati XFDF. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/#importannotationsfromxfdf_1)(string) | Importa tutte le annotazioni dal file XFDF. |
| [ModifyAnnotations](../../aspose.pdf.facades/pdfannotationeditor/modifyannotations/#modifyannotations)(int, int, Annotation) | Modifica le annotazioni del tipo specificato nell'intervallo di pagine specificato. Supporta la modifica delle seguenti proprietà delle annotazioni: Modificato, Titolo, Contenuti, Colore, Oggetto e Aperto. |
| [ModifyAnnotationsAuthor](../../aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor/)(int, int, string, string) | Modifica l'autore delle annotazioni nell'intervallo di pagine specificato. |
| [RedactArea](../../aspose.pdf.facades/pdfannotationeditor/redactarea/)(int, Rectangle, Color) | Censura l'area nella pagina specificata. Tutti i contenuti vengono rimossi. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Salva il documento PDF nello stream specificato. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Salva il documento PDF nel file specificato. |

### Vedi Anche

* classe [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)