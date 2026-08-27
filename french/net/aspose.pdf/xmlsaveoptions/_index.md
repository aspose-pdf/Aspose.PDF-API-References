---
title: "Class XmlSaveOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.XmlSaveOptions class. Options d’enregistrement pour l’exportation au format Xml"
type: docs
weight: 11590
url: /fr/net/aspose.pdf/xmlsaveoptions/
---
## XmlSaveOptions class

Options d'enregistrement pour l'exportation au format Xml

```csharp
public class XmlSaveOptions : SaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [XmlSaveOptions](xmlsaveoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Obtient ou définit la valeur booléenne qui indique si les glyphes de police seront mis en cache lors de la préparation des pages aps. Améliore les performances de la conversion pdf vers d’autres formats mais augmente la consommation de mémoire. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Obtient ou définit la valeur booléenne qui indique si l’objet Response sera fermé après que le document ait été enregistré dans la réponse. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format d’enregistrement des données. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Rappel pour gérer les avertissements générés. Le WarningHandler renvoie l’élément d’énumération ReturnAction spécifiant soit Continue, soit Abort. Continue est l’action par défaut et l’opération Save se poursuit, cependant l’utilisateur peut également renvoyer Abort auquel cas l’opération Save doit s’arrêter. |

## Exemples

L’exemple suivant montre comment convertir un fichier PDF en fichier XML

```csharp
[C#]
	// Le chemin du répertoire des documents.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Le chemin vers votre fichier PDF.
	var pdfFile = Path.Combine(dataDir, "PDF-to-XML.pdf");

	// Le chemin du fichier XML de sortie.
	var xmlFile= Path.Combine(dataDir, "PDF-to-XML.xml");
		
	using (Document pdfDocument = new Document(pdfFile)){
		// Initialiser XmlSaveOptions	
		XmlSaveOptions saveOptions = new XmlSaveOptions();
		
		// Enregistrer le fichier XML
		pdfDocument.Save(xmlFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-XML.pdf")

    ' The path to output XML File.
    Dim xmlFile = Path.Combine(dataDir, "PDF-to-XML.xml")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize XmlSaveOptions
        Dim saveOptions As XmlSaveOptions = New XmlSaveOptions()
 
        ' Save XML file
        pdfDocument.Save(xmlFile, saveOptions)
    End Using
```

### Voir aussi

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


