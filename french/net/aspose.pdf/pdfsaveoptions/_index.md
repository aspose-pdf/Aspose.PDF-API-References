---
title: Class PdfSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.PdfSaveOptions. Options d'enregistrement pour l'exportation au format Pdf
type: docs
weight: 8430
url: /fr/net/aspose.pdf/pdfsaveoptions/
---
## Classe PdfSaveOptions

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
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si les glyphes de police seront mis en cache lors de la préparation des pages aps. Améliore les performances de conversion du pdf vers d'autres formats mais augmente la consommation de mémoire. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si l'objet Response sera fermé après que le document ait été enregistré dans la réponse. |
| [DefaultFontName](../../aspose.pdf/pdfsaveoptions/defaultfontname/) { get; set; } | Nom de la police utilisé par défaut pour les polices qui sont absentes sur l'ordinateur. Lorsque le document PDF enregistré contient des polices qui ne sont pas disponibles dans le document lui-même et sur l'appareil, l'API remplace ces polices par la police par défaut (si une police avec [`DefaultFontName`](./defaultfontname/) est trouvée sur l'appareil) |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format de sauvegarde des données. |
| [TempPath](../../aspose.pdf/pdfsaveoptions/temppath/) { get; set; } | Chemin pour les fichiers temporaires. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback pour gérer les avertissements générés. Le WarningHandler retourne un élément de l'énumération ReturnAction spécifiant soit Continuer soit Abandonner. Continuer est l'action par défaut et l'opération de sauvegarde continue, cependant l'utilisateur peut également retourner Abandonner, auquel cas l'opération de sauvegarde doit cesser. |

## Exemples

L'exemple suivant montre comment définir le nom de la police par défaut lors de l'enregistrement d'un PDF

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Load an existing PDF document with missing font
	string documentName = dataDir + "input.pdf";
	string fontName = "Arial";
	using (System.IO.FileStream fs = new System.IO.FileStream(documentName, System.IO.FileMode.Open))
	using (Document document = new Document(fs))
	{
		PdfSaveOptions pdfSaveOptions = new PdfSaveOptions();

		// Specify Default Font Name
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

* classe [SaveOptions](../saveoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)