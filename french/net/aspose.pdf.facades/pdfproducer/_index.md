---
title: "Classe PdfProducer"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Facades.PdfProducer. Représente une classe permettant de produire des PDF à partir d'autres formats. Cet exemple montre comment produire un fichier Pdf à partir d'un fichier CGM."
type: docs
weight: 4730
url: /fr/net/aspose.pdf.facades/pdfproducer/
---
## PdfProducer class

Représente une classe permettant de produire du PDF à partir d'autres formats. Cet exemple montre comment produire un fichier Pdf à partir d'un fichier CGM.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
try
{
    PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputFile);
    // Fichier pdf produit avec succès.
}
catch (InvalidCgmFileFormatException e)
{
    //  Faire quelque chose...
}
```

```csharp
public abstract class PdfProducer
```

## Méthodes

| Nom | Description |
| --- | --- |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce)(Stream, ImportFormat, Stream) | Produit le flux PDF en utilisant le format d'importation spécifié. Cet exemple montre comment produire un flux Pdf à partir d'un flux CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_1)(Stream, ImportFormat, string) | Produit le fichier PDF en utilisant le format d'importation spécifié. Cet exemple montre comment produire un fichier Pdf à partir d'un flux CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_2)(Stream, ImportOptions, Stream) | Produit le fichier PDF en utilisant l'option d'importation spécifiée. Cet exemple montre comment produire un flux Pdf à partir d'un flux CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_3)(Stream, ImportOptions, string) | Produit le fichier PDF en utilisant l'option d'importation spécifiée. Cet exemple montre comment produire un fichier Pdf à partir d'un flux CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_4)(string, ImportFormat, Stream) | Produit le flux PDF en utilisant le format d'importation spécifié. Cet exemple montre comment produire un flux Pdf à partir d'un fichier CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_5)(string, ImportFormat, string) | Produit le fichier PDF en utilisant le format d'importation spécifié. Cet exemple montre comment produire un fichier Pdf à partir d'un fichier CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_6)(string, ImportOptions, Stream) | Produit le flux PDF en utilisant l'option d'importation spécifiée. Cet exemple montre comment produire un flux Pdf à partir d'un fichier CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_7)(string, ImportOptions, string) | Produit le fichier PDF en utilisant l'option d'importation spécifiée. Cet exemple montre comment produire un fichier Pdf à partir d'un fichier CGM. |

### Voir aussi

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


