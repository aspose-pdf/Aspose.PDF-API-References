---
title: "Classe XslFoLoadOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.XslFoLoadOptions classe. Représente les options de chargement/importation du fichier XSLFO dans un document pdf"
type: docs
weight: 11720
url: /fr/net/aspose.pdf/xslfoloadoptions/
---
## XslFoLoadOptions class

Représente les options de chargement/importation du fichier XSL-FO dans le document pdf.

```csharp
public sealed class XslFoLoadOptions : XmlLoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [XslFoLoadOptions](xslfoloadoptions/#constructor)() | Crée l'objet `XslFoLoadOptions` sans données xsl. |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_1)(Stream) | Crée l'objet `XslFoLoadOptions` avec des données xsl. |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_2)(string) | Crée l'objet `XslFoLoadOptions` avec des données xsl. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BasePath](../../aspose.pdf/xslfoloadoptions/basepath/) { get; set; } | Le chemin/base URL à partir duquel sont recherchés les chemins relatifs vers les ressources externes (le cas échéant) référencées dans le fichier SVG chargé. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtient ou définit le drapeau permettant de désactiver toutes les restrictions de licence pour toutes les polices lors du chargement du fichier. Lorsque `true`, autorise l’exécution d’opérations avec une police qui sont interdites par la licence de cette police, par exemple autorise l’intégration d’une police dans un document PDF même si les règles de licence désactivent l’intégration pour cette police. Par défaut `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Représente le format de fichier décrit par [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Fonction de rappel pour gérer les avertissements générés. Le WarningHandler renvoie un élément de l’énumération ReturnAction spécifiant soit Continue, soit Abort. Continue est l’action par défaut et l’opération de chargement se poursuit, cependant l’utilisateur peut également renvoyer Abort, auquel cas l’opération de chargement doit s’arrêter. |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | Obtient les données xsl pour convertir le xml en document PDF. |
| [XsltArgumentList](../../aspose.pdf/xslfoloadoptions/xsltargumentlist/) { get; set; } | XsltArgumentList pour insérer des valeurs dans les paramètres xls existants  Le fichier XLS a le paramètre 'animal' sans valeur : XsltArgumentList args = new XsltArgumentList(); args.AddParam("animal", "", "cat"); maintenant le convertisseur suppose qu'il existe un paramètre 'animal' avec la valeur 'cat' dans le fichier XLS. |

## Champs

| Nom | Description |
| --- | --- |
| [ParsingErrorsHandlingType](../../aspose.pdf/xslfoloadoptions/parsingerrorshandlingtype/) | Le document XSLFO source peut contenir des erreurs de formatage. Cette énumération répertorie les stratégies possibles de gestion de ces erreurs. |

## Exemples

L'exemple suivant montre comment convertir un fichier XSL-FO en fichier PDF.

```csharp
[C#]
// Le chemin du répertoire des documents.
string dataDir = @"YOUR_DATA_DIRECTORY";

// Le chemin vers votre fichier XSL-FO.
string xslFoFile = Path.Combine(dataDir, "XSLFO-to-PDF.xslfo");

// Le chemin du fichier PDF de sortie.
string pdfFile = Path.Combine(dataDir, "XSLFO-to-PDF.pdf");

// Initialiser XslFoLoadOptions	
XslFoLoadOptions xslFoLoadOptions = new XslFoLoadOptions();
    
using (Document pdfDocument = new Document(xslFoFile, xslFoLoadOptions))
{
 
    // Enregistrer le fichier PDF
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

* class [XmlLoadOptions](../xmlloadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


