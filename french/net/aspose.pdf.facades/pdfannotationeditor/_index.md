---
title: PdfAnnotationEditor
second_title: Référence de l'API Aspose.PDF pour .NET
description: Représente une classe pour travailler avec des annotations de document PDF commentaires.
type: docs
weight: 2420
url: /fr/net/aspose.pdf.facades/pdfannotationeditor/
---
## PdfAnnotationEditor class

Représente une classe pour travailler avec des annotations de document PDF (commentaires).

```csharp
public sealed class PdfAnnotationEditor : SaveableFacade
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PdfAnnotationEditor](pdfannotationeditor#constructor)() | Initialise nouveau[`PdfAnnotationEditor`](../pdfannotationeditor) objet. |
| [PdfAnnotationEditor](pdfannotationeditor#constructor_1)(Document) | Initialise nouveau[`PdfAnnotationEditor`](../pdfannotationeditor) objet sur la base de la*document* . |

## Propriétés

| Nom | La description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Obtient la façade du document sur laquelle travaille. |

## Méthodes

| Nom | La description |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Initialise la façade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Initialise la façade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Initialise la façade. |
| virtual [Close](../../aspose.pdf.facades/facade/close)() | Dispose Aspose.Pdf.Document relié avec une façade. |
| [DeleteAnnotation](../../aspose.pdf.facades/pdfannotationeditor/deleteannotation)(string) | Supprime l'annotation avec le nom d'annotation spécifié. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations#deleteannotations)() | Supprime toutes les annotations du document. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations#deleteannotations_1)(string) | Supprime toutes les annotations du type spécifié dans le document. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Dispose la façade. |
| [ExportAnnotationsToXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationstoxfdf)(Stream) | Exporte les annotations vers le flux. |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf#exportannotationsxfdf)(Stream, int, int, AnnotationType[]) | Exporte le contenu des types d'annotations spécifiés dans XFDF |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf#exportannotationsxfdf_1)(Stream, int, int, string[]) | Exporte le contenu des types d'annotations spécifiés dans XFDF |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations#extractannotations)(int, int, AnnotationType[]) | Obtient la liste des annotations des types spécifiés. |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations#extractannotations_1)(int, int, string[]) | Obtient la liste des annotations des types spécifiés. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations#flatteningannotations)() | Aplatit toutes les annotations du document. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations#flatteningannotations_1)(FlattenSettings) | Aplatit toutes les annotations du document. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations#flatteningannotations_2)(int, int, AnnotationType[]) | Aplatit les annotations des types spécifiés. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf#importannotationfromxfdf_1)(Stream, AnnotationType[]) | Importe les annotations spécifiées à partir du flux de données XFDF. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf#importannotationfromxfdf_3)(string, AnnotationType[]) | Importe les annotations spécifiées à partir du fichier XFDF. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations#importannotations)(Stream[]) | Importe des annotations dans le document à partir d'un tableau d'autres flux de documents PDF. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations#importannotations_2)(string[]) | Importe des annotations dans le document à partir d'un tableau d'autres documents PDF. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations#importannotations_1)(Stream[], AnnotationType[]) | Importe les annotations spécifiées dans le document à partir d'un tableau d'autres flux de documents PDF. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations#importannotations_3)(string[], AnnotationType[]) | Importe les annotations spécifiées dans le document à partir d'un tableau d'autres documents PDF. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf#importannotationsfromxfdf)(Stream) | Importe toutes les annotations du flux de données XFDF. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf#importannotationsfromxfdf_1)(string) | Importe toutes les annotations du fichier XFDF. |
| [ModifyAnnotations](../../aspose.pdf.facades/pdfannotationeditor/modifyannotations#modifyannotations)(int, int, Annotation) | Modifie les annotations du type spécifié sur la plage de pages spécifiée. Il prend en charge la modification des propriétés d'annotation suivantes : Modifié, Titre, Contenu, Couleur, Objet et Ouvrir. |
| [ModifyAnnotationsAuthor](../../aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor)(int, int, string, string) | Modifie l'auteur des annotations sur la plage de pages spécifiée. |
| [RedactArea](../../aspose.pdf.facades/pdfannotationeditor/redactarea)(int, Rectangle, Color) | Caviarde la zone sur la page spécifiée. Tout le contenu est supprimé. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | Enregistre le document PDF dans le flux spécifié. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | Enregistre le document PDF dans le fichier spécifié. |

### Voir également

* class [SaveableFacade](../saveablefacade)
* espace de noms [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
