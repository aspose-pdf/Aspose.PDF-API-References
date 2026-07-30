---
title: "Classe XmlLoadOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.XmlLoadOptions. Représente les options de chargement/importation d'un fichier XML dans un document PDF"
type: docs
weight: 11580
url: /fr/net/aspose.pdf/xmlloadoptions/
---
## XmlLoadOptions class

Représente les options de chargement/importation d'un fichier XML dans un document pdf.

```csharp
public class XmlLoadOptions : LoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [XmlLoadOptions](xmlloadoptions/#constructor)() | Crée l'objet `XmlLoadOptions` sans données xsl. |
| [XmlLoadOptions](xmlloadoptions/#constructor_1)(Stream) | Crée l'objet `XmlLoadOptions` avec des données xsl. |
| [XmlLoadOptions](xmlloadoptions/#constructor_2)(string) | Crée l'objet `XmlLoadOptions` avec des données xsl. |

## Propriétés

| Nom | Description |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtient ou définit le drapeau permettant de désactiver toutes les restrictions de licence pour toutes les polices lors du chargement du fichier. Lorsque `true`, autorise l’exécution d’opérations avec une police qui sont interdites par la licence de cette police, par exemple autorise l’intégration d’une police dans un document PDF même si les règles de licence désactivent l’intégration pour cette police. Par défaut `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Représente le format de fichier décrit par [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Fonction de rappel pour gérer les avertissements générés. Le WarningHandler renvoie un élément de l’énumération ReturnAction spécifiant soit Continue, soit Abort. Continue est l’action par défaut et l’opération de chargement se poursuit, cependant l’utilisateur peut également renvoyer Abort, auquel cas l’opération de chargement doit s’arrêter. |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | Obtient les données xsl pour convertir le xml en document PDF. |

## Exemples

L'exemple suivant montre comment convertir un fichier XML en fichier PDF

```csharp
[C#]
	// Le chemin du répertoire des documents.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Le chemin vers votre fichier XML.
	string xmlFile = Path.Combine(dataDir, "XML-to-PDF.xml");

	// Le chemin du fichier PDF de sortie.
	string pdfFile = Path.Combine(dataDir, "XML-to-PDF.pdf");

	// Initialiser XmlLoadOptions	
	XmlLoadOptions xmlLoadOptions = new XmlLoadOptions();
		
	using (Document pdfDocument = new Document(xmlFile, xmlLoadOptions))
	{
	 
		// Enregistrer le fichier XML
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your XML File.
    Dim xmlFile = Path.Combine(dataDir, "XML-to-PDF.xml")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "XML-to-PDF.pdf")
 
    ' Initialize XmlLoadOptions
    Dim xmlLoadOptions As XmlLoadOptions = New XmlLoadOptions()
 
    Using pdfDocument As Document = New Document(xmlFile, xmlLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Voir aussi

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


