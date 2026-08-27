---
title: "Classe PdfAnnotationEditor"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Facades.PdfAnnotationEditor. Représente une classe pour travailler avec les commentaires d'annotations de documents PDF."
type: docs
weight: 4530
url: /fr/net/aspose.pdf.facades/pdfannotationeditor/
---
## PdfAnnotationEditor class

Représente une classe pour travailler avec les annotations (commentaires) du PDF Document.

```csharp
public sealed class PdfAnnotationEditor : SaveableFacade
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PdfAnnotationEditor](pdfannotationeditor/#constructor)() | Initialise un nouvel objet `PdfAnnotationEditor`. |
| [PdfAnnotationEditor](pdfannotationeditor/#constructor_1)(Document) | Initialise un nouvel objet `PdfAnnotationEditor` basé sur le *document*. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtient la façade du document sur laquelle travaille. |

## Méthodes

| Nom | Description |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initialise la façade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initialise la façade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initialise la façade. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Libère Aspose.Pdf.Document lié à une façade. |
| [DeleteAnnotation](../../aspose.pdf.facades/pdfannotationeditor/deleteannotation/)(string) | Supprime l'annotation avec le nom d'annotation spécifié. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations/#deleteannotations)() | Supprime toutes les annotations du document. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations/#deleteannotations_1)(string) | Supprime toutes les annotations du type spécifié dans le document. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Libère la façade. |
| [ExportAnnotationsToXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationstoxfdf/)(Stream) | Exporte les annotations vers un flux. |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/#exportannotationsxfdf)(Stream, int, int, AnnotationType[]) | Exporte le contenu des types d'annotations spécifiés vers XFDF |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/#exportannotationsxfdf_1)(Stream, int, int, string[]) | Exporte le contenu des types d'annotation spécifiés vers XFDF |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations/#extractannotations)(int, int, AnnotationType[]) | Obtient la liste des annotations des types spécifiés. |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations/#extractannotations_1)(int, int, string[]) | Obtient la liste des annotations des types spécifiés. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations)() | Aplatisse toutes les annotations du document. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations_1)(FlattenSettings) | Aplatisse toutes les annotations du document. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations_2)(int, int, AnnotationType[]) | Aplatisse les annotations des types spécifiés. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/#importannotationfromxfdf_1)(Stream, AnnotationType[]) | Importe les annotations spécifiées depuis le flux de données XFDF. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/#importannotationfromxfdf_3)(string, AnnotationType[]) | Importe les annotations spécifiées depuis le fichier XFDF. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations)(Stream[]) | Importe des annotations dans le document à partir d'un tableau d'autres flux de documents PDF. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_2)(string[]) | Importe des annotations dans le document à partir d'un tableau d'autres documents PDF. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_1)(Stream[], AnnotationType[]) | Importe les annotations spécifiées dans le document à partir d'un tableau d'autres flux de documents PDF. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_3)(string[], AnnotationType[]) | Importe les annotations spécifiées dans le document à partir d'un tableau d'autres documents PDF. |
| [ImportAnnotationsFromFdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/)(string) | Importe toutes les annotations depuis le fichier FDF. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/#importannotationsfromxfdf)(Stream) | Importe toutes les annotations depuis le flux de données XFDF. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/#importannotationsfromxfdf_1)(string) | Importe toutes les annotations depuis le fichier XFDF. |
| [ModifyAnnotations](../../aspose.pdf.facades/pdfannotationeditor/modifyannotations/#modifyannotations)(int, int, Annotation) | Modifie les annotations du type spécifié sur la plage de pages spécifiée. Il prend en charge la modification des propriétés d'annotation suivantes : Modified, Title, Contents, Color, Subject et Open. |
| [ModifyAnnotationsAuthor](../../aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor/)(int, int, string, string) | Modifie l'auteur des annotations sur la plage de pages spécifiée. |
| [RedactArea](../../aspose.pdf.facades/pdfannotationeditor/redactarea/)(int, Rectangle, Color) | Masque la zone sur la page spécifiée. Tout le contenu est supprimé. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Enregistre le document PDF dans le flux spécifié. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Enregistre le document PDF dans le fichier spécifié. |

### Voir aussi

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


