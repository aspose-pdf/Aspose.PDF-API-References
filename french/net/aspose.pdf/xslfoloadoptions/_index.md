---
title: Class XslFoLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.XslFoLoadOptions. Représente les options pour charger/importer un fichier XSLFO dans un document pdf
type: docs
weight: 11530
url: /fr/net/aspose.pdf/xslfoloadoptions/
---
## Classe XslFoLoadOptions

Représente les options pour charger/importer un fichier XSL-FO dans un document pdf.

```csharp
public sealed class XslFoLoadOptions : XmlLoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [XslFoLoadOptions](xslfoloadoptions/#constructor)() | Crée un objet `XslFoLoadOptions` sans données xsl. |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_1)(Stream) | Crée un objet `XslFoLoadOptions` avec des données xsl. |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_2)(string) | Crée un objet `XslFoLoadOptions` avec des données xsl. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BasePath](../../aspose.pdf/xslfoloadoptions/basepath/) { get; set; } | Le chemin/url de base à partir duquel sont recherchés les chemins relatifs vers les ressources externes (le cas échéant) référencées dans le fichier SVG chargé. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtient ou définit un indicateur pour désactiver toutes les restrictions de licence pour toutes les polices lors du chargement du fichier. Lorsque `true`, permet d'exécuter des opérations avec des polices qui sont interdites par une licence de cette police, par exemple permet d'incorporer une police dans un document PDF même si les règles de licence interdisent l'incorporation pour cette police. Par défaut `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Représente le format de fichier que décrit [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback pour gérer les avertissements générés. Le WarningHandler retourne un élément de l'énumération ReturnAction spécifiant soit Continuer soit Abandonner. Continuer est l'action par défaut et l'opération de chargement continue, cependant l'utilisateur peut également retourner Abandonner dans ce cas l'opération de chargement doit cesser. |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | Obtient les données xsl pour convertir xml en document pdf. |
| [XsltArgumentList](../../aspose.pdf/xslfoloadoptions/xsltargumentlist/) { get; set; } | XsltArgumentList pour insérer des valeurs dans les paramètres xls existants. Le fichier XLS a le paramètre 'animal' sans valeur : XsltArgumentList args = new XsltArgumentList(); args.AddParam("animal", "", "cat"); maintenant le convertisseur suppose qu'il y a un paramètre 'animal' avec la valeur 'cat' dans le fichier XLS. |

## Champs

| Nom | Description |
| --- | --- |
| [ParsingErrorsHandlingType](../../aspose.pdf/xslfoloadoptions/parsingerrorshandlingtype/) | Le document XSLFO source peut contenir des erreurs de formatage. Cette énumération énumère les stratégies possibles de gestion de ces erreurs. |

## Exemples

L'exemple suivant montre comment convertir un fichier XSL-FO en fichier PDF

```csharp
[C#]
// The path to the documents directory.
string dataDir = @"YOUR_DATA_DIRECTORY";

// The path to your XSL-FO File.
string xslFoFile = Path.Combine(dataDir, "XSLFO-to-PDF.xslfo");

// The path to output PDF File.
string pdfFile = Path.Combine(dataDir, "XSLFO-to-PDF.pdf");

// Initialize XslFoLoadOptions	
XslFoLoadOptions xslFoLoadOptions = new XslFoLoadOptions();
    
using (Document pdfDocument = new Document(xslFoFile, xslFoLoadOptions))
{
 
    // Save PDF file
    pdfDocument.Save(pdfFile);
}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your XSL-FO File.
    Dim xslFoFile = Path.Combine(dataDir, "XSLFO-to-PDF.xslfo")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "XSLFO-to-PDF.pdf")
 
    ' Initialize XslFoLoadOptions  
    Dim xslFoLoadOptions As XslFoLoadOptions = New XslFoLoadOptions()
 
    Using pdfDocument As Document = New Document(xslFoFile, xslFoLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Voir aussi

* classe [XmlLoadOptions](../xmlloadoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)