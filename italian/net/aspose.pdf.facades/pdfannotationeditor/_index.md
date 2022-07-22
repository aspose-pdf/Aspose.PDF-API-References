---
title: PdfAnnotationEditor
second_title: Aspose.PDF per .NET API Reference
description: Rappresenta una classe per lavorare con le annotazioni di documenti PDF commenti.
type: docs
weight: 2420
url: /it/net/aspose.pdf.facades/pdfannotationeditor/
---
## PdfAnnotationEditor class

Rappresenta una classe per lavorare con le annotazioni di documenti PDF (commenti).

```csharp
public sealed class PdfAnnotationEditor : SaveableFacade
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfAnnotationEditor](pdfannotationeditor#constructor)() | Inizializza nuovo[`PdfAnnotationEditor`](../pdfannotationeditor) oggetto. |
| [PdfAnnotationEditor](pdfannotationeditor#constructor_1)(Document) | Inizializza nuovo[`PdfAnnotationEditor`](../pdfannotationeditor) oggetto sulla base del*document* . |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Ottiene la facciata del documento su cui sta lavorando. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Inizializza la facciata. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Inizializza la facciata. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Inizializza la facciata. |
| virtual [Close](../../aspose.pdf.facades/facade/close)() | Dispose Aspose.Pdf.Document rilegato con una facciata. |
| [DeleteAnnotation](../../aspose.pdf.facades/pdfannotationeditor/deleteannotation)(string) | Elimina l'annotazione con il nome dell'annotazione specificato. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations#deleteannotations)() | Elimina tutte le annotazioni nel documento. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations#deleteannotations_1)(string) | Elimina tutte le annotazioni del tipo specificato nel documento. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Elimina la facciata. |
| [ExportAnnotationsToXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationstoxfdf)(Stream) | Esporta le annotazioni nello stream. |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf#exportannotationsxfdf)(Stream, int, int, AnnotationType[]) | Esporta il contenuto dei tipi di annotazioni specificati in XFDF |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf#exportannotationsxfdf_1)(Stream, int, int, string[]) | Esporta il contenuto dei tipi di annotazioni specificati in XFDF |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations#extractannotations)(int, int, AnnotationType[]) | Ottiene l'elenco delle annotazioni dei tipi specificati. |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations#extractannotations_1)(int, int, string[]) | Ottiene l'elenco delle annotazioni dei tipi specificati. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations#flatteningannotations)() | Appiattisce tutte le annotazioni nel documento. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations#flatteningannotations_1)(FlattenSettings) | Appiattisce tutte le annotazioni nel documento. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations#flatteningannotations_2)(int, int, AnnotationType[]) | Appiattisce le annotazioni dei tipi specificati. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf#importannotationfromxfdf_1)(Stream, AnnotationType[]) | Importa le annotazioni specificate dal flusso di dati XFDF. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf#importannotationfromxfdf_3)(string, AnnotationType[]) | Importa le annotazioni specificate dal file XFDF. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations#importannotations)(Stream[]) | Importa le annotazioni nel documento dall'array di un altro flusso di documenti PDF. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations#importannotations_2)(string[]) | Importa le annotazioni nel documento dall'array di altri documenti PDF. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations#importannotations_1)(Stream[], AnnotationType[]) | Importa le annotazioni specificate nel documento dall'array di un altro flusso di documenti PDF. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations#importannotations_3)(string[], AnnotationType[]) | Importa le annotazioni specificate nel documento dall'array di altri documenti PDF. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf#importannotationsfromxfdf)(Stream) | Importa tutte le annotazioni dal flusso di dati XFDF. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf#importannotationsfromxfdf_1)(string) | Importa tutte le annotazioni dal file XFDF. |
| [ModifyAnnotations](../../aspose.pdf.facades/pdfannotationeditor/modifyannotations#modifyannotations)(int, int, Annotation) | Modifica le annotazioni del tipo specificato nell'intervallo di pagine specificato. Supporta la modifica delle proprietà delle successive annotazioni: Modificato, Titolo, Contenuto, Colore, Oggetto e Apri. |
| [ModifyAnnotationsAuthor](../../aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor)(int, int, string, string) | Modifica l'autore delle annotazioni nell'intervallo di pagine specificato. |
| [RedactArea](../../aspose.pdf.facades/pdfannotationeditor/redactarea)(int, Rectangle, Color) | Redige l'area nella pagina specificata. Tutti i contenuti vengono rimossi. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | Salva il documento PDF nel flusso specificato. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | Salva il documento PDF nel file specificato. |

### Guarda anche

* class [SaveableFacade](../saveablefacade)
* spazio dei nomi [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
