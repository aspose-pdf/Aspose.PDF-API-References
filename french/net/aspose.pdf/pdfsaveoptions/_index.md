---
title: "Classe PdfSaveOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.PdfSaveOptions. Options d'enregistrement pour l'exportation au format Pdf"
type: docs
weight: 8570
url: /fr/net/aspose.pdf/pdfsaveoptions/
---
## PdfSaveOptions class

Options d'enregistrement pour l'exportation au format Pdf

```csharp
public class PdfSaveOptions : SaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Obtient ou définit la valeur booléenne qui indique si les glyphes de police seront mis en cache lors de la préparation des pages aps. Améliore les performances de la conversion pdf vers d’autres formats mais augmente la consommation de mémoire. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Obtient ou définit la valeur booléenne qui indique si l’objet Response sera fermé après que le document ait été enregistré dans la réponse. |
| [DefaultFontName](../../aspose.pdf/pdfsaveoptions/defaultfontname/) { get; set; } | Nom de police utilisé par défaut pour les polices qui sont absentes sur l'ordinateur. Lorsque le document PDF qui est enregistré au format PDF contient des polices qui ne sont pas disponibles dans le document lui‑même ni sur l'appareil, l'API remplace ces polices par la police par défaut (si une police avec [`DefaultFontName`](./defaultfontname/) est trouvée sur l'appareil). |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format d’enregistrement des données. |
| [TempPath](../../aspose.pdf/pdfsaveoptions/temppath/) { get; set; } | Chemin pour les fichiers temporaires. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Rappel pour gérer les avertissements générés. Le WarningHandler renvoie l’élément d’énumération ReturnAction spécifiant soit Continue, soit Abort. Continue est l’action par défaut et l’opération Save se poursuit, cependant l’utilisateur peut également renvoyer Abort auquel cas l’opération Save doit s’arrêter. |

## Exemples

L'exemple suivant montre comment définir le nom de police par défaut lors de l'enregistrement du PDF

```csharp
[C#]
	// Le chemin du répertoire des documents.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Charger un document PDF existant avec une police manquante
	string documentName = dataDir + "input.pdf";
	string fontName = "Arial";
	using (System.IO.FileStream fs = new System.IO.FileStream(documentName, System.IO.FileMode.Open))
	using (Document document = new Document(fs))
	{
		PdfSaveOptions pdfSaveOptions = new PdfSaveOptions();

		// Spécifier le nom de police par défaut
		pdfSaveOptions.DefaultFontName = fontName;
		document.Save(dataDir + "output_out.pdf", pdfSaveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' Load an existing PDF document with missing font
    Dim documentName = dataDir & "input.pdf"
    Dim fontName = "Arial"
 
    Using fs As FileStream = New FileStream(documentName, FileMode.Open)
 
        Using document As Document = New Document(fs)
            Dim pdfSaveOptions As PdfSaveOptions = New PdfSaveOptions()

            ' Specify Default Font Name
            pdfSaveOptions.DefaultFontName = fontName
            document.Save(dataDir & "output_out.pdf", pdfSaveOptions)
        End Using
    End Using
```

### Voir aussi

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


